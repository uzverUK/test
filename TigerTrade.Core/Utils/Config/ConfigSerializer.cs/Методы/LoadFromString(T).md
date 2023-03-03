
# ConfigSerializer.cs
```csharp
namespace TigerTrade.Core.Utils.Config  
    class ConfigSerializer
```

> Описание

### Синтаксис
```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
public static T LoadFromString<T>(byte[] data, DataContractResolver resolver = null)
public static T LoadFromString<T>(byte[] data, IEnumerable<Type> knownTypes)
```
