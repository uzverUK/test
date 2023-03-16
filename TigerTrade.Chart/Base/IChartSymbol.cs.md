
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartSymbol
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertTimeFromLocal`](#ConvertTimeFromLocal-m) | *Описание* |
| [`ConvertTimeToLocal`](#ConvertTimeToLocal-m) | *Описание* |
| [`CorrectSizeFilter`](#CorrectSizeFilter-m) | *Описание* |
| [`FormatPrice`](#FormatPrice-m) | *Описание* |
| [`FormatRawPrice`](#FormatRawPrice-m) | *Описание* |
| [`FormatRawSize`](#FormatRawSize-m) | *Описание* |
| [`FormatRawSizeFull`](#FormatRawSizeFull-m) | *Описание* |
| [`FormatRawSizeShort`](#FormatRawSizeShort-m) | *Описание* |
| [`FormatSize`](#FormatSize-m) | *Описание* |
| [`FormatSizeFull`](#FormatSizeFull-m) | *Описание* |
| [`FormatSizeShort`](#FormatSizeShort-m) | *Описание* |
| [`FormatTime`](#FormatTime-m) | *Описание* |
| [`FormatTrades`](#FormatTrades-m) | *Описание* |
| [`GetPrice`](#GetPrice-m) | *Описание* |
| [`GetSize`](#GetSize-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Code`](#Code-p) | *Описание* |
| [`Decimals`](#Decimals-p) | *Описание* |
| [`Exchange`](#Exchange-p) | *Описание* |
| [`Name`](#Name-p) | *Описание* |
| [`StepPrice`](#StepPrice-p) | *Описание* |





***  
***  
# Методы

## `ConvertTimeFromLocal`<a href="ConvertTimeFromLocal-m" id="ConvertTimeFromLocal-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ConvertTimeToLocal`<a href="ConvertTimeToLocal-m" id="ConvertTimeToLocal-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `CorrectSizeFilter`<a href="CorrectSizeFilter-m" id="CorrectSizeFilter-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long CorrectSizeFilter(double filter)
```

`filter` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `CorrectSizeFilter`<a href="CorrectSizeFilter-m" id="CorrectSizeFilter-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long CorrectSizeFilter(double filter)
long? CorrectSizeFilter(double? filter)
```

`filter` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `FormatPrice`<a href="FormatPrice-m" id="FormatPrice-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatPrice(Decimal price, bool shortDecimals = false)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

`shortDecimals` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatRawPrice`<a href="FormatRawPrice-m" id="FormatRawPrice-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawPrice(long price, bool shortDecimals = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatRawSize`<a href="FormatRawSize-m" id="FormatRawSize-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSize(long size, int round = 2)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`round` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `FormatRawSize`<a href="FormatRawSize-m" id="FormatRawSize-m"></a>
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

## `FormatRawSizeFull`<a href="FormatRawSizeFull-m" id="FormatRawSizeFull-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSizeFull(long size)
```

***  

## `FormatRawSizeShort`<a href="FormatRawSizeShort-m" id="FormatRawSizeShort-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSizeShort(long size)
```

`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatSize`<a href="FormatSize-m" id="FormatSize-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSize(Decimal size, int round = 2)
```
`size` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

`round` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `FormatSize`<a href="FormatSize-m" id="FormatSize-m"></a>
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

## `FormatSizeFull`<a href="FormatSizeFull-m" id="FormatSizeFull-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSizeFull(Decimal size)
```

***  

## `FormatSizeShort`<a href="FormatSizeShort-m" id="FormatSizeShort-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSizeShort(Decimal size)
```

`size` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `FormatTime`<a href="FormatTime-m" id="FormatTime-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTime(DateTime dt, string format)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatTrades`<a href="FormatTrades-m" id="FormatTrades-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTrades(long trades)
```
`trades` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatTrades`<a href="FormatTrades-m" id="FormatTrades-m"></a>
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

## `GetPrice`<a href="GetPrice-m" id="GetPrice-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Decimal GetPrice(long rawPrice)
```
`rawPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetSize`<a href="GetSize-m" id="GetSize-m"></a>
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

## `Code`<a href="Code-p" id="Code-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Code { get; }
```  
***

## `Decimals`<a href="Decimals-p" id="Decimals-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Decimals { get; }
```  
***

## `Exchange`<a href="Exchange-p" id="Exchange-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Exchange { get; }
```  
***

## `Name`<a href="Name-p" id="Name-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Name { get; }
```  
***

## `StepPrice`<a href="StepPrice-p" id="StepPrice-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Decimal StepPrice { get; }
```  
***

