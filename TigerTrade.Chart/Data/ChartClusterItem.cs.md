
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


===

### Синтаксис
```csharp
public sealed class ChartClusterItem : IChartClusterItem
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Add`](#method-add) | *===* |
| [`ChartClusterItem`](#method-chartclusteritem) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Ask`](#property-ask) | *===* |
| [`AskTrades`](#property-asktrades) | *===* |
| [`Bid`](#property-bid) | *===* |
| [`BidTrades`](#property-bidtrades) | *===* |
| [`Delta`](#property-delta) | *===* |
| [`OpenPos`](#property-openpos) | *===* |
| [`OpenPosAsk`](#property-openposask) | *===* |
| [`OpenPosBid`](#property-openposbid) | *===* |
| [`Price`](#property-price) | *===* |
| [`Trades`](#property-trades) | *===* |
| [`Volume`](#property-volume) | *===* |





***  
***  
# Методы

## `Add`<a href="method-add" id="method-add"></a>
===
```csharp
public void Add(IChartClusterItem item)
```

`item` <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *===*  


***  

## `ChartClusterItem`<a href="method-chartclusteritem" id="method-chartclusteritem"></a>
===
```csharp
public ChartClusterItem(Decimal price)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  


***  

## `ChartClusterItem`<a href="method-chartclusteritem" id="method-chartclusteritem"></a>
===
```csharp
public ChartClusterItem(Decimal price)
public ChartClusterItem(IChartClusterItem item)
```
`price` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  

`item` <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Ask`<a href="property-ask" id="property-ask"></a>
===
```csharp
public Decimal Ask { get; set; }
```  
***

## `AskTrades`<a href="property-asktrades" id="property-asktrades"></a>
===
```csharp
public int AskTrades { get; set; }
```  
***

## `Bid`<a href="property-bid" id="property-bid"></a>
===
```csharp
public Decimal Bid { get; set; }
```  
***

## `BidTrades`<a href="property-bidtrades" id="property-bidtrades"></a>
===
```csharp
public int BidTrades { get; set; }
```  
***

## `Delta`<a href="property-delta" id="property-delta"></a>
===
```csharp
public Decimal Delta { get; }
```  
***

## `OpenPos`<a href="property-openpos" id="property-openpos"></a>
===
```csharp
public long OpenPos { get; }
```  
***

## `OpenPosAsk`<a href="property-openposask" id="property-openposask"></a>
===
```csharp
public long OpenPosAsk { get; set; }
```  
***

## `OpenPosBid`<a href="property-openposbid" id="property-openposbid"></a>
===
```csharp
public long OpenPosBid { get; set; }
```  
***

## `Price`<a href="property-price" id="property-price"></a>
===
```csharp
public Decimal Price { get; set; }
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

