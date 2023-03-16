
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class ChartClusterItem : IChartClusterItem
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Add`](#test) | *Описание* |
| [`ChartClusterItem`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Ask`](./ChartClusterItem.cs/Свойства/Ask.md) | *Описание* |
| [`AskTrades`](./ChartClusterItem.cs/Свойства/AskTrades.md) | *Описание* |
| [`Bid`](./ChartClusterItem.cs/Свойства/Bid.md) | *Описание* |
| [`BidTrades`](./ChartClusterItem.cs/Свойства/BidTrades.md) | *Описание* |
| [`Delta`](./ChartClusterItem.cs/Свойства/Delta.md) | *Описание* |
| [`OpenPos`](./ChartClusterItem.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosAsk`](./ChartClusterItem.cs/Свойства/OpenPosAsk.md) | *Описание* |
| [`OpenPosBid`](./ChartClusterItem.cs/Свойства/OpenPosBid.md) | *Описание* |
| [`Price`](./ChartClusterItem.cs/Свойства/Price.md) | *Описание* |
| [`Trades`](./ChartClusterItem.cs/Свойства/Trades.md) | *Описание* |
| [`Volume`](./ChartClusterItem.cs/Свойства/Volume.md) | *Описание* |





***  
***  
# Методы

## `Add`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Add(IChartClusterItem item)
```

`item` <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *Описание*  


***  

## `ChartClusterItem`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartClusterItem(Decimal price)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `ChartClusterItem`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartClusterItem(Decimal price)
public ChartClusterItem(IChartClusterItem item)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

`item` <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Ask`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Ask { get; set; }
```  
***

## `AskTrades`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AskTrades { get; set; }
```  
***

## `Bid`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Bid { get; set; }
```  
***

## `BidTrades`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int BidTrades { get; set; }
```  
***

## `Delta`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Delta { get; }
```  
***

## `OpenPos`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPos { get; }
```  
***

## `OpenPosAsk`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosAsk { get; set; }
```  
***

## `OpenPosBid`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosBid { get; set; }
```  
***

## `Price`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Price { get; set; }
```  
***

## `Trades`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Trades { get; }
```  
***

## `Volume`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Volume { get; }
```  
***

