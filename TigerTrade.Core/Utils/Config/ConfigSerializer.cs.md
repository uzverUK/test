
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Config](../../../TigerTrade.Core/Utils/Config.md)


Описание

### Синтаксис
```csharp
public sealed class ConfigSerializer
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConfigSerializer`](#ConfigSerializer-m) | *Описание* |
| [`LoadFromFile(T)`](#LoadFromFile(T)-m) | *Описание* |
| [`LoadFromString(T)`](#LoadFromString(T)-m) | *Описание* |
| [`SaveToFile(T)`](#SaveToFile(T)-m) | *Описание* |
| [`SaveToString(T)`](#SaveToString(T)-m) | *Описание* |





***  
***  
# Методы

## `ConfigSerializer`<a href="ConfigSerializer-m" id="ConfigSerializer-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ConfigSerializer()
```

***  

## `LoadFromFile(T)`<a href="LoadFromFile(T)-m" id="LoadFromFile(T)-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static T LoadFromFile<T>(string fileName, DataContractResolver resolver = null)
```

`fileName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`resolver` <mark style="color:red;">*`DataContractResolver`*</mark>  
 *Описание*  


***  

## `LoadFromString(T)`<a href="LoadFromString(T)-m" id="LoadFromString(T)-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
```
`data` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `LoadFromString(T)`<a href="LoadFromString(T)-m" id="LoadFromString(T)-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
```
`data` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `LoadFromString(T)`<a href="LoadFromString(T)-m" id="LoadFromString(T)-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
public static T LoadFromString<T>(byte[] data, DataContractResolver resolver = null)
```
`data` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`resolver` <mark style="color:red;">*`DataContractResolver`*</mark>  
 *Описание*  


***  

## `LoadFromString(T)`<a href="LoadFromString(T)-m" id="LoadFromString(T)-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static T LoadFromString<T>(string data, DataContractResolver resolver = null)
public static T LoadFromString<T>(string data, IEnumerable<Type> knownTypes)
public static T LoadFromString<T>(byte[] data, DataContractResolver resolver = null)
public static T LoadFromString<T>(byte[] data, IEnumerable<Type> knownTypes)
```
`data` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`resolver` <mark style="color:red;">*`DataContractResolver`*</mark>  
 *Описание*  


***  

## `SaveToFile(T)`<a href="SaveToFile(T)-m" id="SaveToFile(T)-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SaveToFile<T>(T o, string fileName, DataContractResolver resolver = null)
```
`o` <mark style="color:red;">*`T`*</mark>  
 *Описание*  

`fileName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `SaveToString(T)`<a href="SaveToString(T)-m" id="SaveToString(T)-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string SaveToString<T>(T o, DataContractResolver resolver = null)
```
`resolver` <mark style="color:red;">*`DataContractResolver`*</mark>  
 *Описание*  


***  

## `SaveToString(T)`<a href="SaveToString(T)-m" id="SaveToString(T)-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string SaveToString<T>(T o, DataContractResolver resolver = null)
public static string SaveToString<T>(T o, IEnumerable<Type> knownTypes)
```
`resolver` <mark style="color:red;">*`DataContractResolver`*</mark>  
 *Описание*  

`o` <mark style="color:red;">*`T`*</mark>  
 *Описание*  


***  

