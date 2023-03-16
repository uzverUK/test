
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartSymbol
```


# Список методов
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

# Список свойств
| Название | Описание |
| --- | --- |
| [`Code`](./IChartSymbol.cs/Свойства/Code.md) | *Описание* |
| [`Decimals`](./IChartSymbol.cs/Свойства/Decimals.md) | *Описание* |
| [`Exchange`](./IChartSymbol.cs/Свойства/Exchange.md) | *Описание* |
| [`Name`](./IChartSymbol.cs/Свойства/Name.md) | *Описание* |
| [`StepPrice`](./IChartSymbol.cs/Свойства/StepPrice.md) | *Описание* |





***  
***  
# Методы

## `ConvertTimeFromLocal<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ConvertTimeToLocal<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `CorrectSizeFilter<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long CorrectSizeFilter(double filter)
```

`filter` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `CorrectSizeFilter<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long CorrectSizeFilter(double filter)
long? CorrectSizeFilter(double? filter)
```

`filter` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `FormatPrice<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatPrice(Decimal price, bool shortDecimals = false)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

`shortDecimals` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatRawPrice<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawPrice(long price, bool shortDecimals = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatRawSize<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSize(long size, int round = 2)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`round` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `FormatRawSize<a href="test" id="test"></a>`
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

## `FormatRawSizeFull<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSizeFull(long size)
```

***  

## `FormatRawSizeShort<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatRawSizeShort(long size)
```

`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatSize<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSize(Decimal size, int round = 2)
```
`size` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

`round` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `FormatSize<a href="test" id="test"></a>`
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

## `FormatSizeFull<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSizeFull(Decimal size)
```

***  

## `FormatSizeShort<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatSizeShort(Decimal size)
```

`size` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `FormatTime<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTime(DateTime dt, string format)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatTrades<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTrades(long trades)
```
`trades` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatTrades<a href="test" id="test"></a>`
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

## `GetPrice<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Decimal GetPrice(long rawPrice)
```
`rawPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetSize<a href="test" id="test"></a>`
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

## `Code`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Code { get; }
```  
***

## `Decimals`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Decimals { get; }
```  
***

## `Exchange`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Exchange { get; }
```  
***

## `Name`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string Name { get; }
```  
***

## `StepPrice`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Decimal StepPrice { get; }
```  
***

