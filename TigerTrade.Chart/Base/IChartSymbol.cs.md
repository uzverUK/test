
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartSymbol
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertTimeFromLocal`](#method-converttimefromlocal) | *Описание* |
| [`ConvertTimeToLocal`](#method-converttimetolocal) | *Описание* |
| [`CorrectSizeFilter`](#method-correctsizefilter) | *Описание* |
| [`FormatPrice`](#method-formatprice) | *Описание* |
| [`FormatRawPrice`](#method-formatrawprice) | *Описание* |
| [`FormatRawSize`](#method-formatrawsize) | *Описание* |
| [`FormatRawSizeFull`](#method-formatrawsizefull) | *Описание* |
| [`FormatRawSizeShort`](#method-formatrawsizeshort) | *Описание* |
| [`FormatSize`](#method-formatsize) | *Описание* |
| [`FormatSizeFull`](#method-formatsizefull) | *Описание* |
| [`FormatSizeShort`](#method-formatsizeshort) | *Описание* |
| [`FormatTime`](#method-formattime) | *Описание* |
| [`FormatTrades`](#method-formattrades) | *Описание* |
| [`GetPrice`](#method-getprice) | *Описание* |
| [`GetSize`](#method-getsize) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Code`](#property-code) | *Описание* |
| [`Decimals`](#property-decimals) | *Описание* |
| [`Exchange`](#property-exchange) | *Описание* |
| [`Name`](#property-name) | *Описание* |
| [`StepPrice`](#property-stepprice) | *Описание* |





***  
***  
# Методы

## `ConvertTimeFromLocal`<a href="method-converttimefromlocal" id="method-converttimefromlocal"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ConvertTimeToLocal`<a href="method-converttimetolocal" id="method-converttimetolocal"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `CorrectSizeFilter`<a href="method-correctsizefilter" id="method-correctsizefilter"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long CorrectSizeFilter(double filter)
```

`filter` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `CorrectSizeFilter`<a href="method-correctsizefilter" id="method-correctsizefilter"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long CorrectSizeFilter(double filter)
long? CorrectSizeFilter(double? filter)
```

`filter` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `FormatPrice`<a href="method-formatprice" id="method-formatprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatPrice(Decimal price, bool shortDecimals = false)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

`shortDecimals` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatRawPrice`<a href="method-formatrawprice" id="method-formatrawprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawPrice(long price, bool shortDecimals = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatRawSize`<a href="method-formatrawsize" id="method-formatrawsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSize(long size, int round = 2)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`round` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `FormatRawSize`<a href="method-formatrawsize" id="method-formatrawsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSize(long size, int round = 2)
string FormatRawSize(long size, int round, bool minimize)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`round` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`minimize` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatRawSizeFull`<a href="method-formatrawsizefull" id="method-formatrawsizefull"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSizeFull(long size)
```

***  

## `FormatRawSizeShort`<a href="method-formatrawsizeshort" id="method-formatrawsizeshort"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSizeShort(long size)
```

`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatSize`<a href="method-formatsize" id="method-formatsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSize(Decimal size, int round = 2)
```
`size` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

`round` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `FormatSize`<a href="method-formatsize" id="method-formatsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSize(Decimal size, int round = 2)
string FormatSize(Decimal size, int round, bool minimize)
```
`size` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

`round` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`minimize` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatSizeFull`<a href="method-formatsizefull" id="method-formatsizefull"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSizeFull(Decimal size)
```

***  

## `FormatSizeShort`<a href="method-formatsizeshort" id="method-formatsizeshort"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSizeShort(Decimal size)
```

`size` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `FormatTime`<a href="method-formattime" id="method-formattime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTime(DateTime dt, string format)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatTrades`<a href="method-formattrades" id="method-formattrades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTrades(long trades)
```
`trades` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatTrades`<a href="method-formattrades" id="method-formattrades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTrades(long trades)
string FormatTrades(long trades, int round, bool minimize)
```
`trades` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`round` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`minimize` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetPrice`<a href="method-getprice" id="method-getprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Decimal GetPrice(long rawPrice)
```
`rawPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetSize`<a href="method-getsize" id="method-getsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Decimal GetSize(long rawSize)
```
`rawSize` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Code`<a href="property-code" id="property-code"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Code { get; }
```  
***

## `Decimals`<a href="property-decimals" id="property-decimals"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Decimals { get; }
```  
***

## `Exchange`<a href="property-exchange" id="property-exchange"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Exchange { get; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Name { get; }
```  
***

## `StepPrice`<a href="property-stepprice" id="property-stepprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Decimal StepPrice { get; }
```  
***

