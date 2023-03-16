
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Time](../../../TigerTrade.Core/Utils/Time.md)


Описание

### Синтаксис
```csharp
public static class TimeHelper
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertFromExchangeTimeToUtc`](#method-convertfromexchangetimetoutc) | *Описание* |
| [`CorrectLocalTime`](#method-correctlocaltime) | *Описание* |
| [`CorrectUtcTime`](#method-correctutctime) | *Описание* |
| [`FormatTime`](#method-formattime) | *Описание* |
| [`GetCityTime`](#method-getcitytime) | *Описание* |
| [`GetCurrDate`](#method-getcurrdate) | *Описание* |
| [`GetCurrTime`](#method-getcurrtime) | *Описание* |
| [`GetSessionDate`](#method-getsessiondate) | *Описание* |
| [`GetSessionOffset`](#method-getsessionoffset) | *Описание* |
| [`GetSessionOffsetTs`](#method-getsessionoffsetts) | *Описание* |
| [`IsInvalidTime`](#method-isinvalidtime) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AppLocalTime`](#property-applocaltime) | *Описание* |
| [`CentralTimeOffsetUtc`](#property-centraltimeoffsetutc) | *Описание* |
| [`EasternTimeOffsetUtc`](#property-easterntimeoffsetutc) | *Описание* |
| [`LocalTime`](#property-localtime) | *Описание* |
| [`MoscowTimeOffsetUtc`](#property-moscowtimeoffsetutc) | *Описание* |
| [`PlayerTimeProvider`](#property-playertimeprovider) | *Описание* |





***  
***  
# Методы

## `ConvertFromExchangeTimeToUtc`<a href="method-convertfromexchangetimetoutc" id="method-convertfromexchangetimetoutc"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime ConvertFromExchangeTimeToUtc(DateTime dt, string exchange)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `CorrectLocalTime`<a href="method-correctlocaltime" id="method-correctlocaltime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime CorrectLocalTime(DateTime localTime, string exchange)
```
`localTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `CorrectUtcTime`<a href="method-correctutctime" id="method-correctutctime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime CorrectUtcTime(DateTime utcTime, string exchange)
```
`utcTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatTime`<a href="method-formattime" id="method-formattime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string FormatTime(DateTime dt, string format, string exchange)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetCityTime`<a href="method-getcitytime" id="method-getcitytime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetCityTime(string city)
```
`city` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetCurrDate`<a href="method-getcurrdate" id="method-getcurrdate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetCurrDate(string exchange)
```
`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetCurrTime`<a href="method-getcurrtime" id="method-getcurrtime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetCurrTime(string exchange)
```

***  

## `GetSessionDate`<a href="method-getsessiondate" id="method-getsessiondate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetSessionDate(string exchange)
```

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetSessionDate`<a href="method-getsessiondate" id="method-getsessiondate"></a>
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

## `GetSessionOffset`<a href="method-getsessionoffset" id="method-getsessionoffset"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static double GetSessionOffset(string exchange)
```

***  

## `GetSessionOffsetTs`<a href="method-getsessionoffsetts" id="method-getsessionoffsetts"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan GetSessionOffsetTs(string exchange)
```

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `IsInvalidTime`<a href="method-isinvalidtime" id="method-isinvalidtime"></a>
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

## `AppLocalTime`<a href="property-applocaltime" id="property-applocaltime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool AppLocalTime { get; set; }
```  
***

## `CentralTimeOffsetUtc`<a href="property-centraltimeoffsetutc" id="property-centraltimeoffsetutc"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan CentralTimeOffsetUtc { get; }
```  
***

## `EasternTimeOffsetUtc`<a href="property-easterntimeoffsetutc" id="property-easterntimeoffsetutc"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan EasternTimeOffsetUtc { get; }
```  
***

## `LocalTime`<a href="property-localtime" id="property-localtime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime LocalTime { get; }
```  
***

## `MoscowTimeOffsetUtc`<a href="property-moscowtimeoffsetutc" id="property-moscowtimeoffsetutc"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan MoscowTimeOffsetUtc { get; }
```  
***

## `PlayerTimeProvider`<a href="property-playertimeprovider" id="property-playertimeprovider"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static yr8bwSjOq2M3HqXPgkLr PlayerTimeProvider { get; set; }
```  
***

