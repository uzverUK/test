# MarketDepth

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class MarketDepth
```

## Список методов

| Название                                              | Описание |
| ----------------------------------------------------- | -------- |
| [`MarketDepth`](marketdepth.cs.md#method-marketdepth) | _===_    |

## Список свойств

| Название                                                  | Описание |
| --------------------------------------------------------- | -------- |
| [`Asks`](marketdepth.cs.md#property-asks)                 | _===_    |
| [`AsksSize`](marketdepth.cs.md#property-askssize)         | _===_    |
| [`BestAskPrice`](marketdepth.cs.md#property-bestaskprice) | _===_    |
| [`BestAskSize`](marketdepth.cs.md#property-bestasksize)   | _===_    |
| [`BestBidPrice`](marketdepth.cs.md#property-bestbidprice) | _===_    |
| [`BestBidSize`](marketdepth.cs.md#property-bestbidsize)   | _===_    |
| [`Bids`](marketdepth.cs.md#property-bids)                 | _===_    |
| [`BidsSize`](marketdepth.cs.md#property-bidssize)         | _===_    |
| [`Symbol`](marketdepth.cs.md#property-symbol)             | _===_    |

***

***

## Методы

### `MarketDepth` <a href="#method-marketdepth" id="method-marketdepth"></a>

\===

```csharp
public MarketDepth(Symbol symbol)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

***

***

***

## Свойства

### `Asks` <a href="#property-asks" id="property-asks"></a>

\===

```csharp
public Dictionary<long, long> Asks { get; internal set; }
```

***

### `AsksSize` <a href="#property-askssize" id="property-askssize"></a>

\===

```csharp
public long AsksSize { get; internal set; }
```

***

### `BestAskPrice` <a href="#property-bestaskprice" id="property-bestaskprice"></a>

\===

```csharp
public long BestAskPrice { get; internal set; }
```

***

### `BestAskSize` <a href="#property-bestasksize" id="property-bestasksize"></a>

\===

```csharp
public long BestAskSize { get; internal set; }
```

***

### `BestBidPrice` <a href="#property-bestbidprice" id="property-bestbidprice"></a>

\===

```csharp
public long BestBidPrice { get; internal set; }
```

***

### `BestBidSize` <a href="#property-bestbidsize" id="property-bestbidsize"></a>

\===

```csharp
public long BestBidSize { get; internal set; }
```

***

### `Bids` <a href="#property-bids" id="property-bids"></a>

\===

```csharp
public Dictionary<long, long> Bids { get; internal set; }
```

***

### `BidsSize` <a href="#property-bidssize" id="property-bidssize"></a>

\===

```csharp
public long BidsSize { get; internal set; }
```

***

### `Symbol` <a href="#property-symbol" id="property-symbol"></a>

\===

```csharp
public Symbol Symbol { get; }
```

***
