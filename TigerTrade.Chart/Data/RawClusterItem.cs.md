
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


===

### Синтаксис
```csharp
public sealed class RawClusterItem : IRawClusterItem
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Add`](#method-add) | *===* |
| [`RawClusterItem`](#method-rawclusteritem) | *===* |

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
public void Add(IRawClusterItem item)
```

`item` <mark style="color:red;">*`IRawClusterItem`*</mark>  
 *===*  


***  

## `RawClusterItem`<a href="method-rawclusteritem" id="method-rawclusteritem"></a>
===
```csharp
public RawClusterItem(long price)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `RawClusterItem`<a href="method-rawclusteritem" id="method-rawclusteritem"></a>
===
```csharp
public RawClusterItem(long price)
public RawClusterItem(IRawClusterItem item)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *===*  

`item` <mark style="color:red;">*`IRawClusterItem`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Ask`<a href="property-ask" id="property-ask"></a>
===
```csharp
public long Ask { get; set; }
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
public long Bid { get; set; }
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
public long Delta { get; }
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
public long Price { get; set; }
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

