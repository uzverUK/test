# TimeHelper

`namespace` [TigerTrade.Core](../../).[Utils](../).[Time](./)

\===

#### Синтаксис

```csharp
public static class TimeHelper
```

## Список методов

| Название                                                                               | Описание |
| -------------------------------------------------------------------------------------- | -------- |
| [`ConvertFromExchangeTimeToUtc`](timehelper.cs.md#method-convertfromexchangetimetoutc) | _===_    |
| [`CorrectLocalTime`](timehelper.cs.md#method-correctlocaltime)                         | _===_    |
| [`CorrectUtcTime`](timehelper.cs.md#method-correctutctime)                             | _===_    |
| [`FormatTime`](timehelper.cs.md#method-formattime)                                     | _===_    |
| [`GetCityTime`](timehelper.cs.md#method-getcitytime)                                   | _===_    |
| [`GetCurrDate`](timehelper.cs.md#method-getcurrdate)                                   | _===_    |
| [`GetCurrTime`](timehelper.cs.md#method-getcurrtime)                                   | _===_    |
| [`GetSessionDate`](timehelper.cs.md#method-getsessiondate)                             | _===_    |
| [`GetSessionOffset`](timehelper.cs.md#method-getsessionoffset)                         | _===_    |
| [`GetSessionOffsetTs`](timehelper.cs.md#method-getsessionoffsetts)                     | _===_    |
| [`IsInvalidTime`](timehelper.cs.md#method-isinvalidtime)                               | _===_    |

## Список свойств

| Название                                                                 | Описание |
| ------------------------------------------------------------------------ | -------- |
| [`AppLocalTime`](timehelper.cs.md#property-applocaltime)                 | _===_    |
| [`CentralTimeOffsetUtc`](timehelper.cs.md#property-centraltimeoffsetutc) | _===_    |
| [`EasternTimeOffsetUtc`](timehelper.cs.md#property-easterntimeoffsetutc) | _===_    |
| [`LocalTime`](timehelper.cs.md#property-localtime)                       | _===_    |
| [`MoscowTimeOffsetUtc`](timehelper.cs.md#property-moscowtimeoffsetutc)   | _===_    |
| [`PlayerTimeProvider`](timehelper.cs.md#property-playertimeprovider)     | _===_    |

***

***

## Методы

### `ConvertFromExchangeTimeToUtc` <a href="#method-convertfromexchangetimetoutc" id="method-convertfromexchangetimetoutc"></a>

\===

```csharp
public static DateTime ConvertFromExchangeTimeToUtc(DateTime dt, string exchange)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`exchange` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `CorrectLocalTime` <a href="#method-correctlocaltime" id="method-correctlocaltime"></a>

\===

```csharp
public static DateTime CorrectLocalTime(DateTime localTime, string exchange)
```

`localTime` _<mark style="color:red;">`DateTime`</mark>_\
_===_

***

### `CorrectUtcTime` <a href="#method-correctutctime" id="method-correctutctime"></a>

\===

```csharp
public static DateTime CorrectUtcTime(DateTime utcTime, string exchange)
```

`utcTime` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`exchange` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `FormatTime` <a href="#method-formattime" id="method-formattime"></a>

\===

```csharp
public static string FormatTime(DateTime dt, string format, string exchange)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`format` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetCityTime` <a href="#method-getcitytime" id="method-getcitytime"></a>

\===

```csharp
public static DateTime GetCityTime(string city)
```

`city` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetCurrDate` <a href="#method-getcurrdate" id="method-getcurrdate"></a>

\===

```csharp
public static DateTime GetCurrDate(string exchange)
```

`exchange` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetCurrTime` <a href="#method-getcurrtime" id="method-getcurrtime"></a>

\===

```csharp
public static DateTime GetCurrTime(string exchange)
```

***

### `GetSessionDate` <a href="#method-getsessiondate" id="method-getsessiondate"></a>

\===

```csharp
public static DateTime GetSessionDate(string exchange)
```

`exchange` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetSessionDate` <a href="#method-getsessiondate" id="method-getsessiondate"></a>

\===

```csharp
public static DateTime GetSessionDate(string exchange)
public static DateTime GetSessionDate(DateTime dt, string exchange)
```

`exchange` _<mark style="color:red;">`string`</mark>_\
_===_

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

***

### `GetSessionOffset` <a href="#method-getsessionoffset" id="method-getsessionoffset"></a>

\===

```csharp
public static double GetSessionOffset(string exchange)
```

***

### `GetSessionOffsetTs` <a href="#method-getsessionoffsetts" id="method-getsessionoffsetts"></a>

\===

```csharp
public static TimeSpan GetSessionOffsetTs(string exchange)
```

`exchange` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `IsInvalidTime` <a href="#method-isinvalidtime" id="method-isinvalidtime"></a>

\===

```csharp
public static bool IsInvalidTime(DateTime dt, string exchange)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

***

***

***

## Свойства

### `AppLocalTime` <a href="#property-applocaltime" id="property-applocaltime"></a>

\===

```csharp
public static bool AppLocalTime { get; set; }
```

***

### `CentralTimeOffsetUtc` <a href="#property-centraltimeoffsetutc" id="property-centraltimeoffsetutc"></a>

\===

```csharp
public static TimeSpan CentralTimeOffsetUtc { get; }
```

***

### `EasternTimeOffsetUtc` <a href="#property-easterntimeoffsetutc" id="property-easterntimeoffsetutc"></a>

\===

```csharp
public static TimeSpan EasternTimeOffsetUtc { get; }
```

***

### `LocalTime` <a href="#property-localtime" id="property-localtime"></a>

\===

```csharp
public static DateTime LocalTime { get; }
```

***

### `MoscowTimeOffsetUtc` <a href="#property-moscowtimeoffsetutc" id="property-moscowtimeoffsetutc"></a>

\===

```csharp
public static TimeSpan MoscowTimeOffsetUtc { get; }
```

***

### `PlayerTimeProvider` <a href="#property-playertimeprovider" id="property-playertimeprovider"></a>

\===

```csharp
public static yr8bwSjOq2M3HqXPgkLr PlayerTimeProvider { get; set; }
```

***
