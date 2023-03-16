# ConfigSerializer

`namespace` [TigerTrade.Core](../../).[Utils](../).[Config](./)

\===

#### Синтаксис

```csharp
public sealed class ConfigSerializer
```

## Список методов

| Название                                                                 | Описание |
| ------------------------------------------------------------------------ | -------- |
| [`ConfigSerializer`](configserializer.cs.md#method-configserializer)     | _===_    |
| [`LoadFromFile(T)`](configserializer.cs.md#method-loadfromfile\(t\))     | _===_    |
| [`LoadFromString(T)`](configserializer.cs.md#method-loadfromstring\(t\)) | _===_    |
| [`SaveToFile(T)`](configserializer.cs.md#method-savetofile\(t\))         | _===_    |
| [`SaveToString(T)`](configserializer.cs.md#method-savetostring\(t\))     | _===_    |

***

***

## Методы

### `ConfigSerializer` <a href="#method-configserializer" id="method-configserializer"></a>

\===

```csharp
public ConfigSerializer()
```

***

### `LoadFromFile(T)` <a href="#method-loadfromfile-t" id="method-loadfromfile-t"></a>

\===

```csharp
public static T LoadFromFile<T>(string fileName, DataContractResolver resolver = null)
```

`fileName` _<mark style="color:red;">`string`</mark>_\
_===_

`resolver` _<mark style="color:red;">`DataContractResolver`</mark>_\
_===_

***

### `LoadFromString(T)` <a href="#method-loadfromstring-t" id="method-loadfromstring-t"></a>

\===

```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
```

`data` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `LoadFromString(T)` <a href="#method-loadfromstring-t" id="method-loadfromstring-t"></a>

\===

```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
```

`data` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `LoadFromString(T)` <a href="#method-loadfromstring-t" id="method-loadfromstring-t"></a>

\===

```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
public static T LoadFromString<T>(byte[] data, DataContractResolver resolver = null)
```

`data` _<mark style="color:red;">`string`</mark>_\
_===_

`resolver` _<mark style="color:red;">`DataContractResolver`</mark>_\
_===_

***

### `LoadFromString(T)` <a href="#method-loadfromstring-t" id="method-loadfromstring-t"></a>

\===

```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
public static T LoadFromString<T>(byte[] data, DataContractResolver resolver = null)
public static T LoadFromString<T>(byte[] data, IEnumerable<Type> knownTypes)
```

`data` _<mark style="color:red;">`string`</mark>_\
_===_

`resolver` _<mark style="color:red;">`DataContractResolver`</mark>_\
_===_

***

### `SaveToFile(T)` <a href="#method-savetofile-t" id="method-savetofile-t"></a>

\===

```csharp
public static void SaveToFile<T>(T o, string fileName, DataContractResolver resolver = null)
```

`o` _<mark style="color:red;">`T`</mark>_\
_===_

`fileName` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `SaveToString(T)` <a href="#method-savetostring-t" id="method-savetostring-t"></a>

\===

```csharp
public static string SaveToString<T>(T o, DataContractResolver resolver = null)
```

`resolver` _<mark style="color:red;">`DataContractResolver`</mark>_\
_===_

***

### `SaveToString(T)` <a href="#method-savetostring-t" id="method-savetostring-t"></a>

\===

```csharp
public static string SaveToString<T>(T o, DataContractResolver resolver = null)
public static string SaveToString<T>(T o, IEnumerable<Type> knownTypes)
```

`resolver` _<mark style="color:red;">`DataContractResolver`</mark>_\
_===_

`o` _<mark style="color:red;">`T`</mark>_\
_===_

***
