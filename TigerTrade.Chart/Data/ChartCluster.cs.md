
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class ChartCluster : IChartCluster
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddCluster`](#AddCluster-m) | *Описание* |
| [`AddItem`](#AddItem-m) | *Описание* |
| [`AddTick`](#AddTick-m) | *Описание* |
| [`ChartCluster`](#ChartCluster-m) | *Описание* |
| [`GetItem`](#GetItem-m) | *Описание* |
| [`UpdateData`](#UpdateData-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Ask`](#Ask-p) | *Описание* |
| [`AskTrades`](#AskTrades-p) | *Описание* |
| [`Bid`](#Bid-p) | *Описание* |
| [`BidTrades`](#BidTrades-p) | *Описание* |
| [`Close`](#Close-p) | *Описание* |
| [`CloseTime`](#CloseTime-p) | *Описание* |
| [`Delta`](#Delta-p) | *Описание* |
| [`DeltaHigh`](#DeltaHigh-p) | *Описание* |
| [`DeltaLow`](#DeltaLow-p) | *Описание* |
| [`High`](#High-p) | *Описание* |
| [`IsUp`](#IsUp-p) | *Описание* |
| [`Items`](#Items-p) | *Описание* |
| [`Low`](#Low-p) | *Описание* |
| [`MaxValues`](#MaxValues-p) | *Описание* |
| [`Open`](#Open-p) | *Описание* |
| [`OpenPos`](#OpenPos-p) | *Описание* |
| [`OpenPosAskChg`](#OpenPosAskChg-p) | *Описание* |
| [`OpenPosBidChg`](#OpenPosBidChg-p) | *Описание* |
| [`OpenPosChg`](#OpenPosChg-p) | *Описание* |
| [`OpenPosHigh`](#OpenPosHigh-p) | *Описание* |
| [`OpenPosLow`](#OpenPosLow-p) | *Описание* |
| [`OpenTime`](#OpenTime-p) | *Описание* |
| [`Step`](#Step-p) | *Описание* |
| [`Time`](#Time-p) | *Описание* |
| [`Trades`](#Trades-p) | *Описание* |
| [`Volume`](#Volume-p) | *Описание* |





***  
***  
# Методы

## `AddCluster`<a href="AddCluster-m" id="AddCluster-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddCluster(IChartCluster cluster)
```

`cluster` <mark style="color:red;">*`IChartCluster`*</mark>  
 *Описание*  


***  

## `AddItem`<a href="AddItem-m" id="AddItem-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddItem(IChartClusterItem item)
```
`item` <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *Описание*  


***  

## `AddTick`<a href="AddTick-m" id="AddTick-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddTick(IChartTick tick)
```
`tick` <mark style="color:red;">*`IChartTick`*</mark>  
 *Описание*  


***  

## `ChartCluster`<a href="ChartCluster-m" id="ChartCluster-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartCluster(DateTime time, Decimal step)
```
`time` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`step` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `GetItem`<a href="GetItem-m" id="GetItem-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IChartClusterItem GetItem(Decimal price)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `UpdateData`<a href="UpdateData-m" id="UpdateData-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void UpdateData()
```

***  
***  
 ***  
# Свойства

## `Ask`<a href="Ask-p" id="Ask-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Ask { get; private set; }
```  
***

## `AskTrades`<a href="AskTrades-p" id="AskTrades-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AskTrades { get; private set; }
```  
***

## `Bid`<a href="Bid-p" id="Bid-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Bid { get; private set; }
```  
***

## `BidTrades`<a href="BidTrades-p" id="BidTrades-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int BidTrades { get; private set; }
```  
***

## `Close`<a href="Close-p" id="Close-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Close { get; set; }
```  
***

## `CloseTime`<a href="CloseTime-p" id="CloseTime-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime CloseTime { get; private set; }
```  
***

## `Delta`<a href="Delta-p" id="Delta-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Delta { get; }
```  
***

## `DeltaHigh`<a href="DeltaHigh-p" id="DeltaHigh-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal DeltaHigh { get; private set; }
```  
***

## `DeltaLow`<a href="DeltaLow-p" id="DeltaLow-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal DeltaLow { get; private set; }
```  
***

## `High`<a href="High-p" id="High-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal High { get; set; }
```  
***

## `IsUp`<a href="IsUp-p" id="IsUp-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsUp { get; set; }
```  
***

## `Items`<a href="Items-p" id="Items-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<IChartClusterItem> Items { get; }
```  
***

## `Low`<a href="Low-p" id="Low-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Low { get; set; }
```  
***

## `MaxValues`<a href="MaxValues-p" id="MaxValues-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IChartClusterMaxValues MaxValues { get; }
```  
***

## `Open`<a href="Open-p" id="Open-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Open { get; set; }
```  
***

## `OpenPos`<a href="OpenPos-p" id="OpenPos-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPos { get; private set; }
```  
***

## `OpenPosAskChg`<a href="OpenPosAskChg-p" id="OpenPosAskChg-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosAskChg { get; private set; }
```  
***

## `OpenPosBidChg`<a href="OpenPosBidChg-p" id="OpenPosBidChg-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosBidChg { get; private set; }
```  
***

## `OpenPosChg`<a href="OpenPosChg-p" id="OpenPosChg-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosChg { get; }
```  
***

## `OpenPosHigh`<a href="OpenPosHigh-p" id="OpenPosHigh-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosHigh { get; private set; }
```  
***

## `OpenPosLow`<a href="OpenPosLow-p" id="OpenPosLow-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosLow { get; private set; }
```  
***

## `OpenTime`<a href="OpenTime-p" id="OpenTime-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime OpenTime { get; private set; }
```  
***

## `Step`<a href="Step-p" id="Step-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Step { get; }
```  
***

## `Time`<a href="Time-p" id="Time-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; }
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

