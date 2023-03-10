
# ConfigSerializer.cs
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Config](../../../TigerTrade.Core/Utils/Config.md)  
    `class` [ConfigSerializer](../../ConfigSerializer.cs.md)

Описание

### Синтаксис
```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
public static T LoadFromString<T>(byte[] data, DataContractResolver resolver = null)
public static T LoadFromString<T>(byte[] data, IEnumerable<Type> knownTypes)
```

<mark style="color:yellow;">`data`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  
  
<mark style="color:yellow;">`resolver`</mark> <mark style="color:red;">*`DataContractResolver`*</mark>  
 *Описание*  
  

                    
                    