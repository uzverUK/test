# RawClusterItem

`namespace` [TigerTrade.Chart](../../../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class RawClusterItem : IRawClusterItem
```

## Список методов

| Название                                                       | Описание |
| -------------------------------------------------------------- | -------- |
| [`Add`](rawclusteritem.cs.md#method-add)                       | _===_    |
| [`RawClusterItem`](rawclusteritem.cs.md#method-rawclusteritem) | _===_    |

## Список свойств

| Название                                                 | Описание |
| -------------------------------------------------------- | -------- |
| [`Ask`](rawclusteritem.cs.md#property-ask)               | _===_    |
| [`AskTrades`](rawclusteritem.cs.md#property-asktrades)   | _===_    |
| [`Bid`](rawclusteritem.cs.md#property-bid)               | _===_    |
| [`BidTrades`](rawclusteritem.cs.md#property-bidtrades)   | _===_    |
| [`Delta`](rawclusteritem.cs.md#property-delta)           | _===_    |
| [`OpenPos`](rawclusteritem.cs.md#property-openpos)       | _===_    |
| [`OpenPosAsk`](rawclusteritem.cs.md#property-openposask) | _===_    |
| [`OpenPosBid`](rawclusteritem.cs.md#property-openposbid) | _===_    |
| [`Price`](rawclusteritem.cs.md#property-price)           | _===_    |
| [`Trades`](rawclusteritem.cs.md#property-trades)         | _===_    |
| [`Volume`](rawclusteritem.cs.md#property-volume)         | _===_    |

***

***

## Методы

### `Add` <a href="#method-add" id="method-add"></a>

\===

```csharp
public void Add(IRawClusterItem item)
```

`item` _<mark style="color:red;">`IRawClusterItem`</mark>_\
_===_

***

### `RawClusterItem` <a href="#method-rawclusteritem" id="method-rawclusteritem"></a>

\===

```csharp
public RawClusterItem(long price)
```

`price` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `RawClusterItem` <a href="#method-rawclusteritem" id="method-rawclusteritem"></a>

\===

```csharp
public RawClusterItem(long price)
public RawClusterItem(IRawClusterItem item)
```

`price` _<mark style="color:red;">`long`</mark>_\
_===_

`item` _<mark style="color:red;">`IRawClusterItem`</mark>_\
_===_

***

***

***

## Свойства

### `Ask` <a href="#property-ask" id="property-ask"></a>

\===

```csharp
public long Ask { get; set; }
```

***

### `AskTrades` <a href="#property-asktrades" id="property-asktrades"></a>

\===

```csharp
public int AskTrades { get; set; }
```

***

### `Bid` <a href="#property-bid" id="property-bid"></a>

\===

```csharp
public long Bid { get; set; }
```

***

### `BidTrades` <a href="#property-bidtrades" id="property-bidtrades"></a>

\===

```csharp
public int BidTrades { get; set; }
```

***

### `Delta` <a href="#property-delta" id="property-delta"></a>

\===

```csharp
public long Delta { get; }
```

***

### `OpenPos` <a href="#property-openpos" id="property-openpos"></a>

\===

```csharp
public long OpenPos { get; }
```

***

### `OpenPosAsk` <a href="#property-openposask" id="property-openposask"></a>

\===

```csharp
public long OpenPosAsk { get; set; }
```

***

### `OpenPosBid` <a href="#property-openposbid" id="property-openposbid"></a>

\===

```csharp
public long OpenPosBid { get; set; }
```

***

### `Price` <a href="#property-price" id="property-price"></a>

\===

```csharp
public long Price { get; set; }
```

***

### `Trades` <a href="#property-trades" id="property-trades"></a>

\===

```csharp
public int Trades { get; }
```

***

### `Volume` <a href="#property-volume" id="property-volume"></a>

\===

```csharp
public long Volume { get; }
```

***
