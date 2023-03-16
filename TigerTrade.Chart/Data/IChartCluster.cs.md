
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


===

### Синтаксис
```csharp
public interface IChartCluster
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetItem`](#method-getitem) | *===* |

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

## `GetItem`<a href="method-getitem" id="method-getitem"></a>
===
```csharp
IChartClusterItem GetItem(Decimal price)
```

`price` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Ask`<a href="property-ask" id="property-ask"></a>
===
```csharp
Decimal Ask { get; }
```  
***

## `AskTrades`<a href="property-asktrades" id="property-asktrades"></a>
===
```csharp
int AskTrades { get; }
```  
***

## `Bid`<a href="property-bid" id="property-bid"></a>
===
```csharp
Decimal Bid { get; }
```  
***

## `BidTrades`<a href="property-bidtrades" id="property-bidtrades"></a>
===
```csharp
int BidTrades { get; }
```  
***

## `Close`<a href="property-close" id="property-close"></a>
===
```csharp
Decimal Close { get; }
```  
***

## `CloseTime`<a href="property-closetime" id="property-closetime"></a>
===
```csharp
DateTime CloseTime { get; }
```  
***

## `Delta`<a href="property-delta" id="property-delta"></a>
===
```csharp
Decimal Delta { get; }
```  
***

## `DeltaHigh`<a href="property-deltahigh" id="property-deltahigh"></a>
===
```csharp
Decimal DeltaHigh { get; }
```  
***

## `DeltaLow`<a href="property-deltalow" id="property-deltalow"></a>
===
```csharp
Decimal DeltaLow { get; }
```  
***

## `High`<a href="property-high" id="property-high"></a>
===
```csharp
Decimal High { get; }
```  
***

## `IsUp`<a href="property-isup" id="property-isup"></a>
===
```csharp
bool IsUp { get; }
```  
***

## `Low`<a href="property-low" id="property-low"></a>
===
```csharp
Decimal Low { get; }
```  
***

## `MaxValues`<a href="property-maxvalues" id="property-maxvalues"></a>
===
```csharp
IChartClusterMaxValues MaxValues { get; }
```  
***

## `Open`<a href="property-open" id="property-open"></a>
===
```csharp
Decimal Open { get; }
```  
***

## `OpenPos`<a href="property-openpos" id="property-openpos"></a>
===
```csharp
long OpenPos { get; }
```  
***

## `OpenPosAskChg`<a href="property-openposaskchg" id="property-openposaskchg"></a>
===
```csharp
long OpenPosAskChg { get; }
```  
***

## `OpenPosBidChg`<a href="property-openposbidchg" id="property-openposbidchg"></a>
===
```csharp
long OpenPosBidChg { get; }
```  
***

## `OpenPosChg`<a href="property-openposchg" id="property-openposchg"></a>
===
```csharp
long OpenPosChg { get; }
```  
***

## `OpenPosHigh`<a href="property-openposhigh" id="property-openposhigh"></a>
===
```csharp
long OpenPosHigh { get; }
```  
***

## `OpenPosLow`<a href="property-openposlow" id="property-openposlow"></a>
===
```csharp
long OpenPosLow { get; }
```  
***

## `OpenTime`<a href="property-opentime" id="property-opentime"></a>
===
```csharp
DateTime OpenTime { get; }
```  
***

## `Time`<a href="property-time" id="property-time"></a>
===
```csharp
DateTime Time { get; }
```  
***

## `Trades`<a href="property-trades" id="property-trades"></a>
===
```csharp
int Trades { get; }
```  
***

## `Volume`<a href="property-volume" id="property-volume"></a>
===
```csharp
Decimal Volume { get; }
```  
***

