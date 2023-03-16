
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Time](../../../TigerTrade.Core/Utils/Time.md)


Описание

### Синтаксис
```csharp
public static class TimeHelper
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertFromExchangeTimeToUtc`](#test) | *Описание* |
| [`CorrectLocalTime`](#test) | *Описание* |
| [`CorrectUtcTime`](#test) | *Описание* |
| [`FormatTime`](#test) | *Описание* |
| [`GetCityTime`](#test) | *Описание* |
| [`GetCurrDate`](#test) | *Описание* |
| [`GetCurrTime`](#test) | *Описание* |
| [`GetSessionDate`](#test) | *Описание* |
| [`GetSessionOffset`](#test) | *Описание* |
| [`GetSessionOffsetTs`](#test) | *Описание* |
| [`IsInvalidTime`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AppLocalTime`](./TimeHelper.cs/Свойства/AppLocalTime.md) | *Описание* |
| [`CentralTimeOffsetUtc`](./TimeHelper.cs/Свойства/CentralTimeOffsetUtc.md) | *Описание* |
| [`EasternTimeOffsetUtc`](./TimeHelper.cs/Свойства/EasternTimeOffsetUtc.md) | *Описание* |
| [`LocalTime`](./TimeHelper.cs/Свойства/LocalTime.md) | *Описание* |
| [`MoscowTimeOffsetUtc`](./TimeHelper.cs/Свойства/MoscowTimeOffsetUtc.md) | *Описание* |
| [`PlayerTimeProvider`](./TimeHelper.cs/Свойства/PlayerTimeProvider.md) | *Описание* |





***  
***  
# Методы

## `ConvertFromExchangeTimeToUtc`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime ConvertFromExchangeTimeToUtc(DateTime dt, string exchange)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `CorrectLocalTime`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime CorrectLocalTime(DateTime localTime, string exchange)
```
`localTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `CorrectUtcTime`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime CorrectUtcTime(DateTime utcTime, string exchange)
```
`utcTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatTime`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string FormatTime(DateTime dt, string format, string exchange)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetCityTime`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetCityTime(string city)
```
`city` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetCurrDate`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetCurrDate(string exchange)
```
`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetCurrTime`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetCurrTime(string exchange)
```

***  

## `GetSessionDate`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetSessionDate(string exchange)
```

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetSessionDate`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetSessionDate(string exchange)
public static DateTime GetSessionDate(DateTime dt, string exchange)
```

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `GetSessionOffset`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static double GetSessionOffset(string exchange)
```

***  

## `GetSessionOffsetTs`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan GetSessionOffsetTs(string exchange)
```

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `IsInvalidTime`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsInvalidTime(DateTime dt, string exchange)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `AppLocalTime`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool AppLocalTime { get; set; }
```  
***

## `CentralTimeOffsetUtc`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan CentralTimeOffsetUtc { get; }
```  
***

## `EasternTimeOffsetUtc`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan EasternTimeOffsetUtc { get; }
```  
***

## `LocalTime`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime LocalTime { get; }
```  
***

## `MoscowTimeOffsetUtc`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan MoscowTimeOffsetUtc { get; }
```  
***

## `PlayerTimeProvider`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static yr8bwSjOq2M3HqXPgkLr PlayerTimeProvider { get; set; }
```  
***

