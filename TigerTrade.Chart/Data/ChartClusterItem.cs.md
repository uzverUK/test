
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class ChartClusterItem : IChartClusterItem
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Add`](#Add-m) | *Описание* |
| [`ChartClusterItem`](#ChartClusterItem-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Ask`](#Ask-p) | *Описание* |
| [`AskTrades`](#AskTrades-p) | *Описание* |
| [`Bid`](#Bid-p) | *Описание* |
| [`BidTrades`](#BidTrades-p) | *Описание* |
| [`Delta`](#Delta-p) | *Описание* |
| [`OpenPos`](#OpenPos-p) | *Описание* |
| [`OpenPosAsk`](#OpenPosAsk-p) | *Описание* |
| [`OpenPosBid`](#OpenPosBid-p) | *Описание* |
| [`Price`](#Price-p) | *Описание* |
| [`Trades`](#Trades-p) | *Описание* |
| [`Volume`](#Volume-p) | *Описание* |





***  
***  
# Методы

## `Add`<a href="Add-m" id="Add-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Add(IChartClusterItem item)
```

`item` <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *Описание*  


***  

## `ChartClusterItem`<a href="ChartClusterItem-m" id="ChartClusterItem-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartClusterItem(Decimal price)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `ChartClusterItem`<a href="ChartClusterItem-m" id="ChartClusterItem-m"></a>
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

## `Ask`<a href="Ask-p" id="Ask-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Ask { get; set; }
```  
***

## `AskTrades`<a href="AskTrades-p" id="AskTrades-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AskTrades { get; set; }
```  
***

## `Bid`<a href="Bid-p" id="Bid-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Bid { get; set; }
```  
***

## `BidTrades`<a href="BidTrades-p" id="BidTrades-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int BidTrades { get; set; }
```  
***

## `Delta`<a href="Delta-p" id="Delta-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Delta { get; }
```  
***

## `OpenPos`<a href="OpenPos-p" id="OpenPos-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPos { get; }
```  
***

## `OpenPosAsk`<a href="OpenPosAsk-p" id="OpenPosAsk-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosAsk { get; set; }
```  
***

## `OpenPosBid`<a href="OpenPosBid-p" id="OpenPosBid-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosBid { get; set; }
```  
***

## `Price`<a href="Price-p" id="Price-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Price { get; set; }
```  
***

## `Trades`<a href="Trades-p" id="Trades-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Trades { get; }
```  
***

## `Volume`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Volume { get; }
```  
***

