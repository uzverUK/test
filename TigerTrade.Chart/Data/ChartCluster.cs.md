
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class ChartCluster : IChartCluster
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddCluster`](#method-addcluster) | *Описание* |
| [`AddItem`](#method-additem) | *Описание* |
| [`AddTick`](#method-addtick) | *Описание* |
| [`ChartCluster`](#method-chartcluster) | *Описание* |
| [`GetItem`](#method-getitem) | *Описание* |
| [`UpdateData`](#method-updatedata) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Ask`](#property-ask) | *Описание* |
| [`AskTrades`](#property-asktrades) | *Описание* |
| [`Bid`](#property-bid) | *Описание* |
| [`BidTrades`](#property-bidtrades) | *Описание* |
| [`Close`](#property-close) | *Описание* |
| [`CloseTime`](#property-closetime) | *Описание* |
| [`Delta`](#property-delta) | *Описание* |
| [`DeltaHigh`](#property-deltahigh) | *Описание* |
| [`DeltaLow`](#property-deltalow) | *Описание* |
| [`High`](#property-high) | *Описание* |
| [`IsUp`](#property-isup) | *Описание* |
| [`Items`](#property-items) | *Описание* |
| [`Low`](#property-low) | *Описание* |
| [`MaxValues`](#property-maxvalues) | *Описание* |
| [`Open`](#property-open) | *Описание* |
| [`OpenPos`](#property-openpos) | *Описание* |
| [`OpenPosAskChg`](#property-openposaskchg) | *Описание* |
| [`OpenPosBidChg`](#property-openposbidchg) | *Описание* |
| [`OpenPosChg`](#property-openposchg) | *Описание* |
| [`OpenPosHigh`](#property-openposhigh) | *Описание* |
| [`OpenPosLow`](#property-openposlow) | *Описание* |
| [`OpenTime`](#property-opentime) | *Описание* |
| [`Step`](#property-step) | *Описание* |
| [`Time`](#property-time) | *Описание* |
| [`Trades`](#property-trades) | *Описание* |
| [`Volume`](#property-volume) | *Описание* |





***  
***  
# Методы

## `AddCluster`<a href="method-addcluster" id="method-addcluster"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddCluster(IChartCluster cluster)
```

`cluster` <mark style="color:red;">*`IChartCluster`*</mark>  
 *Описание*  


***  

## `AddItem`<a href="method-additem" id="method-additem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddItem(IChartClusterItem item)
```
`item` <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *Описание*  


***  

## `AddTick`<a href="method-addtick" id="method-addtick"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddTick(IChartTick tick)
```
`tick` <mark style="color:red;">*`IChartTick`*</mark>  
 *Описание*  


***  

## `ChartCluster`<a href="method-chartcluster" id="method-chartcluster"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartCluster(DateTime time, Decimal step)
```
`time` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`step` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `GetItem`<a href="method-getitem" id="method-getitem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IChartClusterItem GetItem(Decimal price)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `UpdateData`<a href="method-updatedata" id="method-updatedata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void UpdateData()
```

***  
***  
 ***  
# Свойства

## `Ask`<a href="property-ask" id="property-ask"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Ask { get; private set; }
```  
***

## `AskTrades`<a href="property-asktrades" id="property-asktrades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AskTrades { get; private set; }
```  
***

## `Bid`<a href="property-bid" id="property-bid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Bid { get; private set; }
```  
***

## `BidTrades`<a href="property-bidtrades" id="property-bidtrades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int BidTrades { get; private set; }
```  
***

## `Close`<a href="property-close" id="property-close"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Close { get; set; }
```  
***

## `CloseTime`<a href="property-closetime" id="property-closetime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime CloseTime { get; private set; }
```  
***

## `Delta`<a href="property-delta" id="property-delta"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Delta { get; }
```  
***

## `DeltaHigh`<a href="property-deltahigh" id="property-deltahigh"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal DeltaHigh { get; private set; }
```  
***

## `DeltaLow`<a href="property-deltalow" id="property-deltalow"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal DeltaLow { get; private set; }
```  
***

## `High`<a href="property-high" id="property-high"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal High { get; set; }
```  
***

## `IsUp`<a href="property-isup" id="property-isup"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsUp { get; set; }
```  
***

## `Items`<a href="property-items" id="property-items"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<IChartClusterItem> Items { get; }
```  
***

## `Low`<a href="property-low" id="property-low"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Low { get; set; }
```  
***

## `MaxValues`<a href="property-maxvalues" id="property-maxvalues"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IChartClusterMaxValues MaxValues { get; }
```  
***

## `Open`<a href="property-open" id="property-open"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Open { get; set; }
```  
***

## `OpenPos`<a href="property-openpos" id="property-openpos"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPos { get; private set; }
```  
***

## `OpenPosAskChg`<a href="property-openposaskchg" id="property-openposaskchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosAskChg { get; private set; }
```  
***

## `OpenPosBidChg`<a href="property-openposbidchg" id="property-openposbidchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosBidChg { get; private set; }
```  
***

## `OpenPosChg`<a href="property-openposchg" id="property-openposchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosChg { get; }
```  
***

## `OpenPosHigh`<a href="property-openposhigh" id="property-openposhigh"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosHigh { get; private set; }
```  
***

## `OpenPosLow`<a href="property-openposlow" id="property-openposlow"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosLow { get; private set; }
```  
***

## `OpenTime`<a href="property-opentime" id="property-opentime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime OpenTime { get; private set; }
```  
***

## `Step`<a href="property-step" id="property-step"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Step { get; }
```  
***

## `Time`<a href="property-time" id="property-time"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; }
```  
***

## `Trades`<a href="property-trades" id="property-trades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Trades { get; }
```  
***

## `Volume`<a href="property-volume" id="property-volume"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Volume { get; }
```  
***

