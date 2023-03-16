
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Config](../../../TigerTrade.Core/Utils/Config.md)


===

### Синтаксис
```csharp
public sealed class ConfigSerializer
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConfigSerializer`](#method-configserializer) | *===* |
| [`LoadFromFile(T)`](#method-loadfromfile(t)) | *===* |
| [`LoadFromString(T)`](#method-loadfromstring(t)) | *===* |
| [`SaveToFile(T)`](#method-savetofile(t)) | *===* |
| [`SaveToString(T)`](#method-savetostring(t)) | *===* |





***  
***  
# Методы

## `ConfigSerializer`<a href="method-configserializer" id="method-configserializer"></a>
===
```csharp
public ConfigSerializer()
```

***  

## `LoadFromFile(T)`<a href="method-loadfromfile(t)" id="method-loadfromfile(t)"></a>
===
```csharp
public static T LoadFromFile<T>(string fileName, DataContractResolver resolver = null)
```

`fileName` <mark style="color:red;">*`string`*</mark>  
 *===*  

`resolver` <mark style="color:red;">*`DataContractResolver`*</mark>  
 *===*  


***  

## `LoadFromString(T)`<a href="method-loadfromstring(t)" id="method-loadfromstring(t)"></a>
===
```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
```
`data` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `LoadFromString(T)`<a href="method-loadfromstring(t)" id="method-loadfromstring(t)"></a>
===
```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
```
`data` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `LoadFromString(T)`<a href="method-loadfromstring(t)" id="method-loadfromstring(t)"></a>
===
```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
public static T LoadFromString<T>(byte[] data, DataContractResolver resolver = null)
```
`data` <mark style="color:red;">*`string`*</mark>  
 *===*  

`resolver` <mark style="color:red;">*`DataContractResolver`*</mark>  
 *===*  


***  

## `LoadFromString(T)`<a href="method-loadfromstring(t)" id="method-loadfromstring(t)"></a>
===
```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
public static T LoadFromString<T>(byte[] data, DataContractResolver resolver = null)
public static T LoadFromString<T>(byte[] data, IEnumerable<Type> knownTypes)
```
`data` <mark style="color:red;">*`string`*</mark>  
 *===*  

`resolver` <mark style="color:red;">*`DataContractResolver`*</mark>  
 *===*  


***  

## `SaveToFile(T)`<a href="method-savetofile(t)" id="method-savetofile(t)"></a>
===
```csharp
public static void SaveToFile<T>(T o, string fileName, DataContractResolver resolver = null)
```
`o` <mark style="color:red;">*`T`*</mark>  
 *===*  

`fileName` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `SaveToString(T)`<a href="method-savetostring(t)" id="method-savetostring(t)"></a>
===
```csharp
public static string SaveToString<T>(T o, DataContractResolver resolver = null)
```
`resolver` <mark style="color:red;">*`DataContractResolver`*</mark>  
 *===*  


***  

## `SaveToString(T)`<a href="method-savetostring(t)" id="method-savetostring(t)"></a>
===
```csharp
public static string SaveToString<T>(T o, DataContractResolver resolver = null)
public static string SaveToString<T>(T o, IEnumerable<Type> knownTypes)
```
`resolver` <mark style="color:red;">*`DataContractResolver`*</mark>  
 *===*  

`o` <mark style="color:red;">*`T`*</mark>  
 *===*  


***  

