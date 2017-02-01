# ExampleGenericDelegate&lt;T1,T2,TResult&gt; delegate

A generic delegate.

```csharp
public delegate TResult ExampleGenericDelegate<in T1, in T2, out TResult>(T1 arg1, T2 arg2)
    where T1 : class, new()
    where T2 : struct;
```

| parameter | description |
| --- | --- |
| T1 | The first generic type. |
| T2 | The second generic type. |
| TResult | The result type. |
| arg1 | The first argument. |
| arg2 | The second argument. |

## Return Value

The result.

## See Also

* namespace [ExampleAssembly](../ExampleAssembly.md)
* [ExampleGenericDelegate.cs](../../tests/ExampleAssembly/ExampleGenericDelegate.cs)

<!-- DO NOT EDIT: generated by xmldocmd for ExampleAssembly.dll -->