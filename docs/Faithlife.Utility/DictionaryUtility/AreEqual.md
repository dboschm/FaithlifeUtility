# DictionaryUtility.AreEqual&lt;TKey,TValue&gt; method

Returns true if there is a one-to-one relationship between every key-value pair.

```csharp
public static bool AreEqual<TKey, TValue>(IReadOnlyDictionary<TKey, TValue> left, 
    IReadOnlyDictionary<TKey, TValue> right, IEqualityComparer<TValue> comparer = null)
```

## Remarks

Uses the default equality comparer for TValue if none is specified.

## See Also

* class [DictionaryUtility](../DictionaryUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->