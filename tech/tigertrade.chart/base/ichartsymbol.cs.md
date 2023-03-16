# IChartSymbol

`namespace` [TigerTrade.Chart](../../../).[Base](./)

\===

#### Синтаксис

```csharp
public interface IChartSymbol
```

## Список методов

| Название                                                                 | Описание |
| ------------------------------------------------------------------------ | -------- |
| [`ConvertTimeFromLocal`](ichartsymbol.cs.md#method-converttimefromlocal) | _===_    |
| [`ConvertTimeToLocal`](ichartsymbol.cs.md#method-converttimetolocal)     | _===_    |
| [`CorrectSizeFilter`](ichartsymbol.cs.md#method-correctsizefilter)       | _===_    |
| [`FormatPrice`](ichartsymbol.cs.md#method-formatprice)                   | _===_    |
| [`FormatRawPrice`](ichartsymbol.cs.md#method-formatrawprice)             | _===_    |
| [`FormatRawSize`](ichartsymbol.cs.md#method-formatrawsize)               | _===_    |
| [`FormatRawSizeFull`](ichartsymbol.cs.md#method-formatrawsizefull)       | _===_    |
| [`FormatRawSizeShort`](ichartsymbol.cs.md#method-formatrawsizeshort)     | _===_    |
| [`FormatSize`](ichartsymbol.cs.md#method-formatsize)                     | _===_    |
| [`FormatSizeFull`](ichartsymbol.cs.md#method-formatsizefull)             | _===_    |
| [`FormatSizeShort`](ichartsymbol.cs.md#method-formatsizeshort)           | _===_    |
| [`FormatTime`](ichartsymbol.cs.md#method-formattime)                     | _===_    |
| [`FormatTrades`](ichartsymbol.cs.md#method-formattrades)                 | _===_    |
| [`GetPrice`](ichartsymbol.cs.md#method-getprice)                         | _===_    |
| [`GetSize`](ichartsymbol.cs.md#method-getsize)                           | _===_    |

## Список свойств

| Название                                             | Описание |
| ---------------------------------------------------- | -------- |
| [`Code`](ichartsymbol.cs.md#property-code)           | _===_    |
| [`Decimals`](ichartsymbol.cs.md#property-decimals)   | _===_    |
| [`Exchange`](ichartsymbol.cs.md#property-exchange)   | _===_    |
| [`Name`](ichartsymbol.cs.md#property-name)           | _===_    |
| [`StepPrice`](ichartsymbol.cs.md#property-stepprice) | _===_    |

***

***

## Методы

### `ConvertTimeFromLocal` <a href="#method-converttimefromlocal" id="method-converttimefromlocal"></a>

\===

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

***

### `ConvertTimeToLocal` <a href="#method-converttimetolocal" id="method-converttimetolocal"></a>

\===

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***

### `CorrectSizeFilter` <a href="#method-correctsizefilter" id="method-correctsizefilter"></a>

\===

```csharp
long CorrectSizeFilter(double filter)
```

`filter` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `CorrectSizeFilter` <a href="#method-correctsizefilter" id="method-correctsizefilter"></a>

\===

```csharp
long CorrectSizeFilter(double filter)
long? CorrectSizeFilter(double? filter)
```

`filter` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `FormatPrice` <a href="#method-formatprice" id="method-formatprice"></a>

\===

```csharp
string FormatPrice(Decimal price, bool shortDecimals = false)
```

`price` _<mark style="color:red;">`Decimal`</mark>_\
_===_

`shortDecimals` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `FormatRawPrice` <a href="#method-formatrawprice" id="method-formatrawprice"></a>

\===

```csharp
string FormatRawPrice(long price, bool shortDecimals = false)
```

`price` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `FormatRawSize` <a href="#method-formatrawsize" id="method-formatrawsize"></a>

\===

```csharp
string FormatRawSize(long size, int round = 2)
```

`size` _<mark style="color:red;">`long`</mark>_\
_===_

`round` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `FormatRawSize` <a href="#method-formatrawsize" id="method-formatrawsize"></a>

\===

```csharp
string FormatRawSize(long size, int round = 2)
string FormatRawSize(long size, int round, bool minimize)
```

`size` _<mark style="color:red;">`long`</mark>_\
_===_

`round` _<mark style="color:red;">`int`</mark>_\
_===_

`minimize` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `FormatRawSizeFull` <a href="#method-formatrawsizefull" id="method-formatrawsizefull"></a>

\===

```csharp
string FormatRawSizeFull(long size)
```

***

### `FormatRawSizeShort` <a href="#method-formatrawsizeshort" id="method-formatrawsizeshort"></a>

\===

```csharp
string FormatRawSizeShort(long size)
```

`size` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `FormatSize` <a href="#method-formatsize" id="method-formatsize"></a>

\===

```csharp
string FormatSize(Decimal size, int round = 2)
```

`size` _<mark style="color:red;">`Decimal`</mark>_\
_===_

`round` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `FormatSize` <a href="#method-formatsize" id="method-formatsize"></a>

\===

```csharp
string FormatSize(Decimal size, int round = 2)
string FormatSize(Decimal size, int round, bool minimize)
```

`size` _<mark style="color:red;">`Decimal`</mark>_\
_===_

`round` _<mark style="color:red;">`int`</mark>_\
_===_

`minimize` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `FormatSizeFull` <a href="#method-formatsizefull" id="method-formatsizefull"></a>

\===

```csharp
string FormatSizeFull(Decimal size)
```

***

### `FormatSizeShort` <a href="#method-formatsizeshort" id="method-formatsizeshort"></a>

\===

```csharp
string FormatSizeShort(Decimal size)
```

`size` _<mark style="color:red;">`Decimal`</mark>_\
_===_

***

### `FormatTime` <a href="#method-formattime" id="method-formattime"></a>

\===

```csharp
string FormatTime(DateTime dt, string format)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`format` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `FormatTrades` <a href="#method-formattrades" id="method-formattrades"></a>

\===

```csharp
string FormatTrades(long trades)
```

`trades` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `FormatTrades` <a href="#method-formattrades" id="method-formattrades"></a>

\===

```csharp
string FormatTrades(long trades)
string FormatTrades(long trades, int round, bool minimize)
```

`trades` _<mark style="color:red;">`long`</mark>_\
_===_

`round` _<mark style="color:red;">`int`</mark>_\
_===_

`minimize` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `GetPrice` <a href="#method-getprice" id="method-getprice"></a>

\===

```csharp
Decimal GetPrice(long rawPrice)
```

`rawPrice` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `GetSize` <a href="#method-getsize" id="method-getsize"></a>

\===

```csharp
Decimal GetSize(long rawSize)
```

`rawSize` _<mark style="color:red;">`long`</mark>_\
_===_

***

***

***

## Свойства

### `Code` <a href="#property-code" id="property-code"></a>

\===

```csharp
string Code { get; }
```

***

### `Decimals` <a href="#property-decimals" id="property-decimals"></a>

\===

```csharp
int Decimals { get; }
```

***

### `Exchange` <a href="#property-exchange" id="property-exchange"></a>

\===

```csharp
string Exchange { get; }
```

***

### `Name` <a href="#property-name" id="property-name"></a>

\===

```csharp
string Name { get; }
```

***

### `StepPrice` <a href="#property-stepprice" id="property-stepprice"></a>

\===

```csharp
Decimal StepPrice { get; }
```

***
