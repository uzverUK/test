
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Time](../../../TigerTrade.Core/Utils/Time.md)


===

### Синтаксис
```csharp
public static class TimeHelper
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertFromExchangeTimeToUtc`](#method-convertfromexchangetimetoutc) | *===* |
| [`CorrectLocalTime`](#method-correctlocaltime) | *===* |
| [`CorrectUtcTime`](#method-correctutctime) | *===* |
| [`FormatTime`](#method-formattime) | *===* |
| [`GetCityTime`](#method-getcitytime) | *===* |
| [`GetCurrDate`](#method-getcurrdate) | *===* |
| [`GetCurrTime`](#method-getcurrtime) | *===* |
| [`GetSessionDate`](#method-getsessiondate) | *===* |
| [`GetSessionOffset`](#method-getsessionoffset) | *===* |
| [`GetSessionOffsetTs`](#method-getsessionoffsetts) | *===* |
| [`IsInvalidTime`](#method-isinvalidtime) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AppLocalTime`](#property-applocaltime) | *===* |
| [`CentralTimeOffsetUtc`](#property-centraltimeoffsetutc) | *===* |
| [`EasternTimeOffsetUtc`](#property-easterntimeoffsetutc) | *===* |
| [`LocalTime`](#property-localtime) | *===* |
| [`MoscowTimeOffsetUtc`](#property-moscowtimeoffsetutc) | *===* |
| [`PlayerTimeProvider`](#property-playertimeprovider) | *===* |





***  
***  
# Методы

## `ConvertFromExchangeTimeToUtc`<a href="method-convertfromexchangetimetoutc" id="method-convertfromexchangetimetoutc"></a>
===
```csharp
public static DateTime ConvertFromExchangeTimeToUtc(DateTime dt, string exchange)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`exchange` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `CorrectLocalTime`<a href="method-correctlocaltime" id="method-correctlocaltime"></a>
===
```csharp
public static DateTime CorrectLocalTime(DateTime localTime, string exchange)
```
`localTime` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  


***  

## `CorrectUtcTime`<a href="method-correctutctime" id="method-correctutctime"></a>
===
```csharp
public static DateTime CorrectUtcTime(DateTime utcTime, string exchange)
```
`utcTime` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`exchange` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `FormatTime`<a href="method-formattime" id="method-formattime"></a>
===
```csharp
public static string FormatTime(DateTime dt, string format, string exchange)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`format` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetCityTime`<a href="method-getcitytime" id="method-getcitytime"></a>
===
```csharp
public static DateTime GetCityTime(string city)
```
`city` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetCurrDate`<a href="method-getcurrdate" id="method-getcurrdate"></a>
===
```csharp
public static DateTime GetCurrDate(string exchange)
```
`exchange` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetCurrTime`<a href="method-getcurrtime" id="method-getcurrtime"></a>
===
```csharp
public static DateTime GetCurrTime(string exchange)
```

***  

## `GetSessionDate`<a href="method-getsessiondate" id="method-getsessiondate"></a>
===
```csharp
public static DateTime GetSessionDate(string exchange)
```

`exchange` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetSessionDate`<a href="method-getsessiondate" id="method-getsessiondate"></a>
===
```csharp
public static DateTime GetSessionDate(string exchange)
public static DateTime GetSessionDate(DateTime dt, string exchange)
```

`exchange` <mark style="color:red;">*`string`*</mark>  
 *===*  

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  


***  

## `GetSessionOffset`<a href="method-getsessionoffset" id="method-getsessionoffset"></a>
===
```csharp
public static double GetSessionOffset(string exchange)
```

***  

## `GetSessionOffsetTs`<a href="method-getsessionoffsetts" id="method-getsessionoffsetts"></a>
===
```csharp
public static TimeSpan GetSessionOffsetTs(string exchange)
```

`exchange` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `IsInvalidTime`<a href="method-isinvalidtime" id="method-isinvalidtime"></a>
===
```csharp
public static bool IsInvalidTime(DateTime dt, string exchange)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `AppLocalTime`<a href="property-applocaltime" id="property-applocaltime"></a>
===
```csharp
public static bool AppLocalTime { get; set; }
```  
***

## `CentralTimeOffsetUtc`<a href="property-centraltimeoffsetutc" id="property-centraltimeoffsetutc"></a>
===
```csharp
public static TimeSpan CentralTimeOffsetUtc { get; }
```  
***

## `EasternTimeOffsetUtc`<a href="property-easterntimeoffsetutc" id="property-easterntimeoffsetutc"></a>
===
```csharp
public static TimeSpan EasternTimeOffsetUtc { get; }
```  
***

## `LocalTime`<a href="property-localtime" id="property-localtime"></a>
===
```csharp
public static DateTime LocalTime { get; }
```  
***

## `MoscowTimeOffsetUtc`<a href="property-moscowtimeoffsetutc" id="property-moscowtimeoffsetutc"></a>
===
```csharp
public static TimeSpan MoscowTimeOffsetUtc { get; }
```  
***

## `PlayerTimeProvider`<a href="property-playertimeprovider" id="property-playertimeprovider"></a>
===
```csharp
public static yr8bwSjOq2M3HqXPgkLr PlayerTimeProvider { get; set; }
```  
***

