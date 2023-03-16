
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

## `AddCluster`<a href="UpdateData-m" id="UpdateData-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddCluster(IChartCluster cluster)
```

`cluster` <mark style="color:red;">*`IChartCluster`*</mark>  
 *Описание*  


***  

## `AddItem`<a href="UpdateData-m" id="UpdateData-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddItem(IChartClusterItem item)
```
`item` <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *Описание*  


***  

## `AddTick`<a href="UpdateData-m" id="UpdateData-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddTick(IChartTick tick)
```
`tick` <mark style="color:red;">*`IChartTick`*</mark>  
 *Описание*  


***  

## `ChartCluster`<a href="UpdateData-m" id="UpdateData-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartCluster(DateTime time, Decimal step)
```
`time` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`step` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `GetItem`<a href="UpdateData-m" id="UpdateData-m"></a>
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

## `Ask`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Ask { get; private set; }
```  
***

## `AskTrades`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AskTrades { get; private set; }
```  
***

## `Bid`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Bid { get; private set; }
```  
***

## `BidTrades`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int BidTrades { get; private set; }
```  
***

## `Close`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Close { get; set; }
```  
***

## `CloseTime`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime CloseTime { get; private set; }
```  
***

## `Delta`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Delta { get; }
```  
***

## `DeltaHigh`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal DeltaHigh { get; private set; }
```  
***

## `DeltaLow`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal DeltaLow { get; private set; }
```  
***

## `High`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal High { get; set; }
```  
***

## `IsUp`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsUp { get; set; }
```  
***

## `Items`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<IChartClusterItem> Items { get; }
```  
***

## `Low`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Low { get; set; }
```  
***

## `MaxValues`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IChartClusterMaxValues MaxValues { get; }
```  
***

## `Open`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Open { get; set; }
```  
***

## `OpenPos`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPos { get; private set; }
```  
***

## `OpenPosAskChg`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosAskChg { get; private set; }
```  
***

## `OpenPosBidChg`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosBidChg { get; private set; }
```  
***

## `OpenPosChg`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosChg { get; }
```  
***

## `OpenPosHigh`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosHigh { get; private set; }
```  
***

## `OpenPosLow`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosLow { get; private set; }
```  
***

## `OpenTime`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime OpenTime { get; private set; }
```  
***

## `Step`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Step { get; }
```  
***

## `Time`<a href="Volume-p" id="Volume-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; }
```  
***

## `Trades`<a href="Volume-p" id="Volume-p"></a>
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

