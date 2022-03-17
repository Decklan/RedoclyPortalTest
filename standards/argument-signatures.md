---
title: Argument Signatures
---

# Argument Signatures

When you only have three or less arguments it is relatively easy to look at when you leave your arguments on the same line.

```csharp
// This is OK
public class FergiesAwesomeClass {
    ...
    public FergiesAwesomeClass(IFergiesFirstDependency dependency, int someNumber, string someString) {
        ...
    }
}
```

When your signature has more than three arguments, you should new line your args.

```csharp
// This is not easy to look at
public class FergiesAwesomeClass {
    ...
    public FergiesAwesomeClass(IFergiesFirstDependency dependency, IFergiesSecondDependency secondDependency, IFergiesThirdDependency thirdDependency, IFergiesFourthDependency fourthDependency, int someNumber, string someString, bool someBoolean, string anotherString) {

    }
}
```

Putting args on a new line makes it easier to look at.

```csharp
// Ahhhh much better
public class FergiesAwesomeClass {
    ...
    public FergiesAwesomeClass(
        IFergiesFirstDependency dependency,
        IFergiesSecondDependency secondDependency,
        IFergiesThirdDependency thirdDependency,
        IFergiesFourthDependency fourthDependency,
        int someNumber,
        string someString,
        bool someBoolean,
        string anotherString
    ) {

    }
}
```

The same goes for function signatures.