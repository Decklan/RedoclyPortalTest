---
title: BillingApi Information
---

# BillingApi Information

The BillingApi openapi document is fetched from Redocly and rendered in the dropdown below this page.
We can fetch our openapi documents from Redocly and, as such, they are always up-to-date when we make 
changes to the API and push them into our main branches in GitHub. Checkout siteConfig.yaml and 
sidebars.yaml to see this in action.

## How?
When we create our API projects in the API Registry in Redocly, any time we push code to the main branch
in the repo, Redocly will run a build on the openapi document that is produced from that build to ensure
that it is valid. We can then link to that document in the portal for display in the developer portal.

CustomerApi is another example of this.