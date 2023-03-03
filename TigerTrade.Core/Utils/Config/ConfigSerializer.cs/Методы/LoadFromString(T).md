
# ConfigSerializer.cs
```csharp
namespace TigerTrade.Core.Utils.Config  
    class ConfigSerializer
```

Описание

### Синтаксис
```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
public static T LoadFromString<T>(byte[] data, DataContractResolver resolver = null)
public static T LoadFromString<T>(byte[] data, IEnumerable<Type> knownTypes)
```

<mark style="color:red;">**`data`**</mark> <mark style="color:yellow;">`string`</mark>  
 *Описание*  
  
<mark style="color:red;">**`resolver`**</mark> <mark style="color:yellow;">`DataContractResolver`</mark>  
 *Описание*  
  

                    
                    