
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartSymbol
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ConvertTimeFromLocal`](./IChartSymbol.cs/Методы/ConvertTimeFromLocal.md) | *Описание* |
| [`ConvertTimeToLocal`](./IChartSymbol.cs/Методы/ConvertTimeToLocal.md) | *Описание* |
| [`CorrectSizeFilter`](./IChartSymbol.cs/Методы/CorrectSizeFilter.md) | *Описание* |
| [`FormatPrice`](./IChartSymbol.cs/Методы/FormatPrice.md) | *Описание* |
| [`FormatRawPrice`](./IChartSymbol.cs/Методы/FormatRawPrice.md) | *Описание* |
| [`FormatRawSize`](./IChartSymbol.cs/Методы/FormatRawSize.md) | *Описание* |
| [`FormatRawSizeFull`](./IChartSymbol.cs/Методы/FormatRawSizeFull.md) | *Описание* |
| [`FormatRawSizeShort`](./IChartSymbol.cs/Методы/FormatRawSizeShort.md) | *Описание* |
| [`FormatSize`](./IChartSymbol.cs/Методы/FormatSize.md) | *Описание* |
| [`FormatSizeFull`](./IChartSymbol.cs/Методы/FormatSizeFull.md) | *Описание* |
| [`FormatSizeShort`](./IChartSymbol.cs/Методы/FormatSizeShort.md) | *Описание* |
| [`FormatTime`](./IChartSymbol.cs/Методы/FormatTime.md) | *Описание* |
| [`FormatTrades`](./IChartSymbol.cs/Методы/FormatTrades.md) | *Описание* |
| [`GetPrice`](./IChartSymbol.cs/Методы/GetPrice.md) | *Описание* |
| [`GetSize`](./IChartSymbol.cs/Методы/GetSize.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Code`](./IChartSymbol.cs/Свойства/Code.md) | *Описание* |
| [`Decimals`](./IChartSymbol.cs/Свойства/Decimals.md) | *Описание* |
| [`Exchange`](./IChartSymbol.cs/Свойства/Exchange.md) | *Описание* |
| [`Name`](./IChartSymbol.cs/Свойства/Name.md) | *Описание* |
| [`StepPrice`](./IChartSymbol.cs/Свойства/StepPrice.md) | *Описание* |





# Методы

## *ConvertTimeFromLocal*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

<mark style="color:yellow;">`dt`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  



## *ConvertTimeToLocal*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```


## *CorrectSizeFilter*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long CorrectSizeFilter(double filter)
```

<mark style="color:yellow;">`filter`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *CorrectSizeFilter*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long CorrectSizeFilter(double filter)
long? CorrectSizeFilter(double? filter)
```

<mark style="color:yellow;">`filter`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *FormatPrice*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatPrice(Decimal price, bool shortDecimals = false)
```
<mark style="color:yellow;">`price`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

<mark style="color:yellow;">`shortDecimals`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *FormatRawPrice*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawPrice(long price, bool shortDecimals = false)
```
<mark style="color:yellow;">`price`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  



## *FormatRawSize*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSize(long size, int round = 2)
```
<mark style="color:yellow;">`size`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  

<mark style="color:yellow;">`round`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *FormatRawSize*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSize(long size, int round = 2)
string FormatRawSize(long size, int round, bool minimize)
```
<mark style="color:yellow;">`size`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  

<mark style="color:yellow;">`round`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`minimize`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *FormatRawSizeFull*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSizeFull(long size)
```


## *FormatRawSizeShort*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSizeShort(long size)
```

<mark style="color:yellow;">`size`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  



## *FormatSize*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSize(Decimal size, int round = 2)
```
<mark style="color:yellow;">`size`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

<mark style="color:yellow;">`round`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *FormatSize*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSize(Decimal size, int round = 2)
string FormatSize(Decimal size, int round, bool minimize)
```
<mark style="color:yellow;">`size`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

<mark style="color:yellow;">`round`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`minimize`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *FormatSizeFull*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSizeFull(Decimal size)
```


## *FormatSizeShort*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSizeShort(Decimal size)
```

<mark style="color:yellow;">`size`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  



## *FormatTime*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTime(DateTime dt, string format)
```
<mark style="color:yellow;">`dt`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

<mark style="color:yellow;">`format`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *FormatTrades*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTrades(long trades)
```
<mark style="color:yellow;">`trades`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  



## *FormatTrades*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTrades(long trades)
string FormatTrades(long trades, int round, bool minimize)
```
<mark style="color:yellow;">`trades`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  

<mark style="color:yellow;">`round`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`minimize`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *GetPrice*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Decimal GetPrice(long rawPrice)
```
<mark style="color:yellow;">`rawPrice`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  



## *GetSize*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Decimal GetSize(long rawSize)
```
<mark style="color:yellow;">`rawSize`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  


# Свойства

## *Code*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Code { get; }
```

## *Decimals*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Decimals { get; }
```

## *Exchange*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Exchange { get; }
```

## *Name*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Name { get; }
```

## *StepPrice*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Decimal StepPrice { get; }
```

