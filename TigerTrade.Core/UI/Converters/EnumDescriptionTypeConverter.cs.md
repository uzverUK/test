
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[UI](../../../TigerTrade.Core/UI.md).[Converters](../../../TigerTrade.Core/UI/Converters.md)


Описание

### Синтаксис
```csharp
public sealed class EnumDescriptionTypeConverter : EnumConverter
```


# Список методов
| Название | Описание |
| --- | --- |
| [`EnumDescriptionTypeConverter`](#EnumDescriptionTypeConverter-m) | *Описание* |
| [`GetDescription`](#GetDescription-m) | *Описание* |
| [`GetValue`](#GetValue-m) | *Описание* |





***  
***  
# Методы

## `EnumDescriptionTypeConverter`<a href="EnumDescriptionTypeConverter-m" id="EnumDescriptionTypeConverter-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public EnumDescriptionTypeConverter(Type type)
```

`type` <mark style="color:red;">*`Type`*</mark>  
 *Описание*  


***  

## `GetDescription`<a href="GetDescription-m" id="GetDescription-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string GetDescription(Type type, string fieldName)
```
`fieldName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetValue`<a href="GetValue-m" id="GetValue-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static object GetValue(Type type, string description)
```
`type` <mark style="color:red;">*`Type`*</mark>  
 *Описание*  

`description` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

