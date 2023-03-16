
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


===

### Синтаксис
```csharp
public sealed class RawCluster : IRawCluster
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddCluster`](#method-addcluster) | *===* |
| [`AddItem`](#method-additem) | *===* |
| [`AddTick`](#method-addtick) | *===* |
| [`GetItem`](#method-getitem) | *===* |
| [`GetValueArea`](#method-getvaluearea) | *===* |
| [`RawCluster`](#method-rawcluster) | *===* |
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
| [`Time`](#property-time) | *===* |
| [`Trades`](#property-trades) | *===* |
| [`Volume`](#property-volume) | *===* |





***  
***  
# Методы

## `AddCluster`<a href="method-addcluster" id="method-addcluster"></a>
===
```csharp
public void AddCluster(IRawCluster cluster)
```

`cluster` <mark style="color:red;">*`IRawCluster`*</mark>  
 *===*  


***  

## `AddItem`<a href="method-additem" id="method-additem"></a>
===
```csharp
public void AddItem(IRawClusterItem item)
```
`item` <mark style="color:red;">*`IRawClusterItem`*</mark>  
 *===*  


***  

## `AddTick`<a href="method-addtick" id="method-addtick"></a>
===
```csharp
public void AddTick(IRawTick tick, int scale)
```
`tick` <mark style="color:red;">*`IRawTick`*</mark>  
 *===*  

`scale` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `GetItem`<a href="method-getitem" id="method-getitem"></a>
===
```csharp
public IRawClusterItem GetItem(long price)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `GetValueArea`<a href="method-getvaluearea" id="method-getvaluearea"></a>
===
```csharp
public IRawClusterValueArea GetValueArea(int valueArea)
```
`valueArea` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `RawCluster`<a href="method-rawcluster" id="method-rawcluster"></a>
===
```csharp
public RawCluster(DateTime time)
```
`time` <mark style="color:red;">*`DateTime`*</mark>  
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
public long Ask { get; private set; }
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
public long Bid { get; private set; }
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
public long Close { get; set; }
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
public long Delta { get; }
```  
***

## `DeltaHigh`<a href="property-deltahigh" id="property-deltahigh"></a>
===
```csharp
public long DeltaHigh { get; private set; }
```  
***

## `DeltaLow`<a href="property-deltalow" id="property-deltalow"></a>
===
```csharp
public long DeltaLow { get; private set; }
```  
***

## `High`<a href="property-high" id="property-high"></a>
===
```csharp
public long High { get; set; }
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
public List<IRawClusterItem> Items { get; }
```  
***

## `Low`<a href="property-low" id="property-low"></a>
===
```csharp
public long Low { get; set; }
```  
***

## `MaxValues`<a href="property-maxvalues" id="property-maxvalues"></a>
===
```csharp
public IRawClusterMaxValues MaxValues { get; }
```  
***

## `Open`<a href="property-open" id="property-open"></a>
===
```csharp
public long Open { get; set; }
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
public long Volume { get; }
```  
***

