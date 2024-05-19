---
description: Enumerable tools to help you manipulate with them!
---

# 📂 Enumerable Tools

Enumerable extensions can be found in the `EnumerableExtensions` static class that is found under the `Magico.Enumeration` namespace. You don't have to explicitly reference the class, because you can just place a dot after the `IEnumerable` instance, and you can access the following extensions:

* `Length()`
* `GetElementFromIndex()`

You can access the extensions in one of the forms:

```csharp
// Form 1
int length = enumerableVar.Length();

// Form 2
int length2 = EnumerableExtensions.Length(enumerableVar);
```
