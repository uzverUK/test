
# ConfigSerializer.cs
## Расположение
```csharp
namespace TigerTrade.Core.Utils.Config  
    class ConfigSerializer
```

> Описание

## Синтаксис
```csharp
public static string SaveToString<T>(T o, DataContractResolver resolver = null)
public static string SaveToString<T>(T o, IEnumerable<Type> knownTypes)
```
