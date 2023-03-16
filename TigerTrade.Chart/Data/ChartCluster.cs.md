
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


===

### Синтаксис
```csharp
public sealed class ChartCluster : IChartCluster
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddCluster`](#method-addcluster) | *===* |
| [`AddItem`](#method-additem) | *===* |
| [`AddTick`](#method-addtick) | *===* |
| [`ChartCluster`](#method-chartcluster) | *===* |
| [`GetItem`](#method-getitem) | *===* |
| [`UpdateData`](#method-updatedata) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Ask`](#property-ask) | *===* |
| [`AskTrades`](#property-asktrades) | *===* |
| [`Bid`](#property-bid) | *===* |
| [`BidTrades`](#property-bidtrades) | *===* |
| [`Close`](#property-close) | *===* |
| [`CloseTime`](#property-closetime) | *===* |
| [`Delta`](#property-delta) | *===* |
| [`DeltaHigh`](#property-deltahigh) | *===* |
| [`DeltaLow`](#property-deltalow) | *===* |
| [`High`](#property-high) | *===* |
| [`IsUp`](#property-isup) | *===* |
| [`Items`](#property-items) | *===* |
| [`Low`](#property-low) | *===* |
| [`MaxValues`](#property-maxvalues) | *===* |
| [`Open`](#property-open) | *===* |
| [`OpenPos`](#property-openpos) | *===* |
| [`OpenPosAskChg`](#property-openposaskchg) | *===* |
| [`OpenPosBidChg`](#property-openposbidchg) | *===* |
| [`OpenPosChg`](#property-openposchg) | *===* |
| [`OpenPosHigh`](#property-openposhigh) | *===* |
| [`OpenPosLow`](#property-openposlow) | *===* |
| [`OpenTime`](#property-opentime) | *===* |
| [`Step`](#property-step) | *===* |
| [`Time`](#property-time) | *===* |
| [`Trades`](#property-trades) | *===* |
| [`Volume`](#property-volume) | *===* |





***  
***  
# Методы

## `AddCluster`<a href="method-addcluster" id="method-addcluster"></a>
===
```csharp
public void AddCluster(IChartCluster cluster)
```

`cluster` <mark style="color:red;">*`IChartCluster`*</mark>  
 *===*  


***  

## `AddItem`<a href="method-additem" id="method-additem"></a>
===
```csharp
public void AddItem(IChartClusterItem item)
```
`item` <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *===*  


***  

## `AddTick`<a href="method-addtick" id="method-addtick"></a>
===
```csharp
public void AddTick(IChartTick tick)
```
`tick` <mark style="color:red;">*`IChartTick`*</mark>  
 *===*  


***  

## `ChartCluster`<a href="method-chartcluster" id="method-chartcluster"></a>
===
```csharp
public ChartCluster(DateTime time, Decimal step)
```
`time` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`step` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  


***  

## `GetItem`<a href="method-getitem" id="method-getitem"></a>
===
```csharp
public IChartClusterItem GetItem(Decimal price)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  


***  

## `UpdateData`<a href="method-updatedata" id="method-updatedata"></a>
===
```csharp
public void UpdateData()
```

***  
***  
 ***  
# Свойства

## `Ask`<a href="property-ask" id="property-ask"></a>
===
```csharp
public Decimal Ask { get; private set; }
```  
***

## `AskTrades`<a href="property-asktrades" id="property-asktrades"></a>
===
```csharp
public int AskTrades { get; private set; }
```  
***

## `Bid`<a href="property-bid" id="property-bid"></a>
===
```csharp
public Decimal Bid { get; private set; }
```  
***

## `BidTrades`<a href="property-bidtrades" id="property-bidtrades"></a>
===
```csharp
public int BidTrades { get; private set; }
```  
***

## `Close`<a href="property-close" id="property-close"></a>
===
```csharp
public Decimal Close { get; set; }
```  
***

## `CloseTime`<a href="property-closetime" id="property-closetime"></a>
===
```csharp
public DateTime CloseTime { get; private set; }
```  
***

## `Delta`<a href="property-delta" id="property-delta"></a>
===
```csharp
public Decimal Delta { get; }
```  
***

## `DeltaHigh`<a href="property-deltahigh" id="property-deltahigh"></a>
===
```csharp
public Decimal DeltaHigh { get; private set; }
```  
***

## `DeltaLow`<a href="property-deltalow" id="property-deltalow"></a>
===
```csharp
public Decimal DeltaLow { get; private set; }
```  
***

## `High`<a href="property-high" id="property-high"></a>
===
```csharp
public Decimal High { get; set; }
```  
***

## `IsUp`<a href="property-isup" id="property-isup"></a>
===
```csharp
public bool IsUp { get; set; }
```  
***

## `Items`<a href="property-items" id="property-items"></a>
===
```csharp
public List<IChartClusterItem> Items { get; }
```  
***

## `Low`<a href="property-low" id="property-low"></a>
===
```csharp
public Decimal Low { get; set; }
```  
***

## `MaxValues`<a href="property-maxvalues" id="property-maxvalues"></a>
===
```csharp
public IChartClusterMaxValues MaxValues { get; }
```  
***

## `Open`<a href="property-open" id="property-open"></a>
===
```csharp
public Decimal Open { get; set; }
```  
***

## `OpenPos`<a href="property-openpos" id="property-openpos"></a>
===
```csharp
public long OpenPos { get; private set; }
```  
***

## `OpenPosAskChg`<a href="property-openposaskchg" id="property-openposaskchg"></a>
===
```csharp
public long OpenPosAskChg { get; private set; }
```  
***

## `OpenPosBidChg`<a href="property-openposbidchg" id="property-openposbidchg"></a>
===
```csharp
public long OpenPosBidChg { get; private set; }
```  
***

## `OpenPosChg`<a href="property-openposchg" id="property-openposchg"></a>
===
```csharp
public long OpenPosChg { get; }
```  
***

## `OpenPosHigh`<a href="property-openposhigh" id="property-openposhigh"></a>
===
```csharp
public long OpenPosHigh { get; private set; }
```  
***

## `OpenPosLow`<a href="property-openposlow" id="property-openposlow"></a>
===
```csharp
public long OpenPosLow { get; private set; }
```  
***

## `OpenTime`<a href="property-opentime" id="property-opentime"></a>
===
```csharp
public DateTime OpenTime { get; private set; }
```  
***

## `Step`<a href="property-step" id="property-step"></a>
===
```csharp
public Decimal Step { get; }
```  
***

## `Time`<a href="property-time" id="property-time"></a>
===
```csharp
public DateTime Time { get; }
```  
***

## `Trades`<a href="property-trades" id="property-trades"></a>
===
```csharp
public int Trades { get; }
```  
***

## `Volume`<a href="property-volume" id="property-volume"></a>
===
```csharp
public Decimal Volume { get; }
```  
***

