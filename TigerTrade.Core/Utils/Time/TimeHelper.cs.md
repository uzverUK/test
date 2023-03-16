
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Time](../../../TigerTrade.Core/Utils/Time.md)


Описание

### Синтаксис
```csharp
public static class TimeHelper
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertFromExchangeTimeToUtc`](#ConvertFromExchangeTimeToUtc-m) | *Описание* |
| [`CorrectLocalTime`](#CorrectLocalTime-m) | *Описание* |
| [`CorrectUtcTime`](#CorrectUtcTime-m) | *Описание* |
| [`FormatTime`](#FormatTime-m) | *Описание* |
| [`GetCityTime`](#GetCityTime-m) | *Описание* |
| [`GetCurrDate`](#GetCurrDate-m) | *Описание* |
| [`GetCurrTime`](#GetCurrTime-m) | *Описание* |
| [`GetSessionDate`](#GetSessionDate-m) | *Описание* |
| [`GetSessionOffset`](#GetSessionOffset-m) | *Описание* |
| [`GetSessionOffsetTs`](#GetSessionOffsetTs-m) | *Описание* |
| [`IsInvalidTime`](#IsInvalidTime-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AppLocalTime`](#AppLocalTime-p) | *Описание* |
| [`CentralTimeOffsetUtc`](#CentralTimeOffsetUtc-p) | *Описание* |
| [`EasternTimeOffsetUtc`](#EasternTimeOffsetUtc-p) | *Описание* |
| [`LocalTime`](#LocalTime-p) | *Описание* |
| [`MoscowTimeOffsetUtc`](#MoscowTimeOffsetUtc-p) | *Описание* |
| [`PlayerTimeProvider`](#PlayerTimeProvider-p) | *Описание* |





***  
***  
# Методы

## `ConvertFromExchangeTimeToUtc`<a href="ConvertFromExchangeTimeToUtc-m" id="ConvertFromExchangeTimeToUtc-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime ConvertFromExchangeTimeToUtc(DateTime dt, string exchange)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `CorrectLocalTime`<a href="CorrectLocalTime-m" id="CorrectLocalTime-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime CorrectLocalTime(DateTime localTime, string exchange)
```
`localTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `CorrectUtcTime`<a href="CorrectUtcTime-m" id="CorrectUtcTime-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime CorrectUtcTime(DateTime utcTime, string exchange)
```
`utcTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatTime`<a href="FormatTime-m" id="FormatTime-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string FormatTime(DateTime dt, string format, string exchange)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetCityTime`<a href="GetCityTime-m" id="GetCityTime-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetCityTime(string city)
```
`city` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetCurrDate`<a href="GetCurrDate-m" id="GetCurrDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetCurrDate(string exchange)
```
`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetCurrTime`<a href="GetCurrTime-m" id="GetCurrTime-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetCurrTime(string exchange)
```

***  

## `GetSessionDate`<a href="GetSessionDate-m" id="GetSessionDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime GetSessionDate(string exchange)
```

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetSessionDate`<a href="GetSessionDate-m" id="GetSessionDate-m"></a>
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

## `GetSessionOffset`<a href="GetSessionOffset-m" id="GetSessionOffset-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static double GetSessionOffset(string exchange)
```

***  

## `GetSessionOffsetTs`<a href="GetSessionOffsetTs-m" id="GetSessionOffsetTs-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan GetSessionOffsetTs(string exchange)
```

`exchange` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `IsInvalidTime`<a href="IsInvalidTime-m" id="IsInvalidTime-m"></a>
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

## `AppLocalTime`<a href="AppLocalTime-p" id="AppLocalTime-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool AppLocalTime { get; set; }
```  
***

## `CentralTimeOffsetUtc`<a href="CentralTimeOffsetUtc-p" id="CentralTimeOffsetUtc-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan CentralTimeOffsetUtc { get; }
```  
***

## `EasternTimeOffsetUtc`<a href="EasternTimeOffsetUtc-p" id="EasternTimeOffsetUtc-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan EasternTimeOffsetUtc { get; }
```  
***

## `LocalTime`<a href="LocalTime-p" id="LocalTime-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime LocalTime { get; }
```  
***

## `MoscowTimeOffsetUtc`<a href="MoscowTimeOffsetUtc-p" id="MoscowTimeOffsetUtc-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static TimeSpan MoscowTimeOffsetUtc { get; }
```  
***

## `PlayerTimeProvider`<a href="PlayerTimeProvider-p" id="PlayerTimeProvider-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static yr8bwSjOq2M3HqXPgkLr PlayerTimeProvider { get; set; }
```  
***

