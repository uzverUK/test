
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


===

### Синтаксис
```csharp
public interface IChartSymbol
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertTimeFromLocal`](#method-converttimefromlocal) | *===* |
| [`ConvertTimeToLocal`](#method-converttimetolocal) | *===* |
| [`CorrectSizeFilter`](#method-correctsizefilter) | *===* |
| [`FormatPrice`](#method-formatprice) | *===* |
| [`FormatRawPrice`](#method-formatrawprice) | *===* |
| [`FormatRawSize`](#method-formatrawsize) | *===* |
| [`FormatRawSizeFull`](#method-formatrawsizefull) | *===* |
| [`FormatRawSizeShort`](#method-formatrawsizeshort) | *===* |
| [`FormatSize`](#method-formatsize) | *===* |
| [`FormatSizeFull`](#method-formatsizefull) | *===* |
| [`FormatSizeShort`](#method-formatsizeshort) | *===* |
| [`FormatTime`](#method-formattime) | *===* |
| [`FormatTrades`](#method-formattrades) | *===* |
| [`GetPrice`](#method-getprice) | *===* |
| [`GetSize`](#method-getsize) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Code`](#property-code) | *===* |
| [`Decimals`](#property-decimals) | *===* |
| [`Exchange`](#property-exchange) | *===* |
| [`Name`](#property-name) | *===* |
| [`StepPrice`](#property-stepprice) | *===* |





***  
***  
# Методы

## `ConvertTimeFromLocal`<a href="method-converttimefromlocal" id="method-converttimefromlocal"></a>
===
```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  


***  

## `ConvertTimeToLocal`<a href="method-converttimetolocal" id="method-converttimetolocal"></a>
===
```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `CorrectSizeFilter`<a href="method-correctsizefilter" id="method-correctsizefilter"></a>
===
```csharp
long CorrectSizeFilter(double filter)
```

`filter` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `CorrectSizeFilter`<a href="method-correctsizefilter" id="method-correctsizefilter"></a>
===
```csharp
long CorrectSizeFilter(double filter)
long? CorrectSizeFilter(double? filter)
```

`filter` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `FormatPrice`<a href="method-formatprice" id="method-formatprice"></a>
===
```csharp
string FormatPrice(Decimal price, bool shortDecimals = false)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  

`shortDecimals` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `FormatRawPrice`<a href="method-formatrawprice" id="method-formatrawprice"></a>
===
```csharp
string FormatRawPrice(long price, bool shortDecimals = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `FormatRawSize`<a href="method-formatrawsize" id="method-formatrawsize"></a>
===
```csharp
string FormatRawSize(long size, int round = 2)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *===*  

`round` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `FormatRawSize`<a href="method-formatrawsize" id="method-formatrawsize"></a>
===
```csharp
string FormatRawSize(long size, int round = 2)
string FormatRawSize(long size, int round, bool minimize)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *===*  

`round` <mark style="color:red;">*`int`*</mark>  
 *===*  

`minimize` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `FormatRawSizeFull`<a href="method-formatrawsizefull" id="method-formatrawsizefull"></a>
===
```csharp
string FormatRawSizeFull(long size)
```

***  

## `FormatRawSizeShort`<a href="method-formatrawsizeshort" id="method-formatrawsizeshort"></a>
===
```csharp
string FormatRawSizeShort(long size)
```

`size` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `FormatSize`<a href="method-formatsize" id="method-formatsize"></a>
===
```csharp
string FormatSize(Decimal size, int round = 2)
```
`size` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  

`round` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `FormatSize`<a href="method-formatsize" id="method-formatsize"></a>
===
```csharp
string FormatSize(Decimal size, int round = 2)
string FormatSize(Decimal size, int round, bool minimize)
```
`size` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  

`round` <mark style="color:red;">*`int`*</mark>  
 *===*  

`minimize` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `FormatSizeFull`<a href="method-formatsizefull" id="method-formatsizefull"></a>
===
```csharp
string FormatSizeFull(Decimal size)
```

***  

## `FormatSizeShort`<a href="method-formatsizeshort" id="method-formatsizeshort"></a>
===
```csharp
string FormatSizeShort(Decimal size)
```

`size` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  


***  

## `FormatTime`<a href="method-formattime" id="method-formattime"></a>
===
```csharp
string FormatTime(DateTime dt, string format)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`format` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `FormatTrades`<a href="method-formattrades" id="method-formattrades"></a>
===
```csharp
string FormatTrades(long trades)
```
`trades` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `FormatTrades`<a href="method-formattrades" id="method-formattrades"></a>
===
```csharp
string FormatTrades(long trades)
string FormatTrades(long trades, int round, bool minimize)
```
`trades` <mark style="color:red;">*`long`*</mark>  
 *===*  

`round` <mark style="color:red;">*`int`*</mark>  
 *===*  

`minimize` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `GetPrice`<a href="method-getprice" id="method-getprice"></a>
===
```csharp
Decimal GetPrice(long rawPrice)
```
`rawPrice` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `GetSize`<a href="method-getsize" id="method-getsize"></a>
===
```csharp
Decimal GetSize(long rawSize)
```
`rawSize` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Code`<a href="property-code" id="property-code"></a>
===
```csharp
string Code { get; }
```  
***

## `Decimals`<a href="property-decimals" id="property-decimals"></a>
===
```csharp
int Decimals { get; }
```  
***

## `Exchange`<a href="property-exchange" id="property-exchange"></a>
===
```csharp
string Exchange { get; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
===
```csharp
string Name { get; }
```  
***

## `StepPrice`<a href="property-stepprice" id="property-stepprice"></a>
===
```csharp
Decimal StepPrice { get; }
```  
***

