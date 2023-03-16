# ChartClusterItem

`namespace` [TigerTrade.Chart](../../../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class ChartClusterItem : IChartClusterItem
```

## Список методов

| Название                                                             | Описание |
| -------------------------------------------------------------------- | -------- |
| [`Add`](chartclusteritem.cs.md#method-add)                           | _===_    |
| [`ChartClusterItem`](chartclusteritem.cs.md#method-chartclusteritem) | _===_    |

## Список свойств

| Название                                                   | Описание |
| ---------------------------------------------------------- | -------- |
| [`Ask`](chartclusteritem.cs.md#property-ask)               | _===_    |
| [`AskTrades`](chartclusteritem.cs.md#property-asktrades)   | _===_    |
| [`Bid`](chartclusteritem.cs.md#property-bid)               | _===_    |
| [`BidTrades`](chartclusteritem.cs.md#property-bidtrades)   | _===_    |
| [`Delta`](chartclusteritem.cs.md#property-delta)           | _===_    |
| [`OpenPos`](chartclusteritem.cs.md#property-openpos)       | _===_    |
| [`OpenPosAsk`](chartclusteritem.cs.md#property-openposask) | _===_    |
| [`OpenPosBid`](chartclusteritem.cs.md#property-openposbid) | _===_    |
| [`Price`](chartclusteritem.cs.md#property-price)           | _===_    |
| [`Trades`](chartclusteritem.cs.md#property-trades)         | _===_    |
| [`Volume`](chartclusteritem.cs.md#property-volume)         | _===_    |

***

***

## Методы

### `Add` <a href="#method-add" id="method-add"></a>

\===

```csharp
public void Add(IChartClusterItem item)
```

`item` _<mark style="color:red;">`IChartClusterItem`</mark>_\
_===_

***

### `ChartClusterItem` <a href="#method-chartclusteritem" id="method-chartclusteritem"></a>

\===

```csharp
public ChartClusterItem(Decimal price)
```

`price` _<mark style="color:red;">`Decimal`</mark>_\
_===_

***

### `ChartClusterItem` <a href="#method-chartclusteritem" id="method-chartclusteritem"></a>

\===

```csharp
public ChartClusterItem(Decimal price)
public ChartClusterItem(IChartClusterItem item)
```

`price` _<mark style="color:red;">`Decimal`</mark>_\
_===_

`item` _<mark style="color:red;">`IChartClusterItem`</mark>_\
_===_

***

***

***

## Свойства

### `Ask` <a href="#property-ask" id="property-ask"></a>

\===

```csharp
public Decimal Ask { get; set; }
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
public Decimal Bid { get; set; }
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
public Decimal Delta { get; }
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
public Decimal Price { get; set; }
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
public Decimal Volume { get; }
```

***
