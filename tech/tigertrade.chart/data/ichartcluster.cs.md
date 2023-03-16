# IChartCluster

`namespace` [TigerTrade.Chart](../../../).[Data](./)

\===

#### Синтаксис

```csharp
public interface IChartCluster
```

## Список методов

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`GetItem`](ichartcluster.cs.md#method-getitem) | _===_    |

## Список свойств

| Название                                                      | Описание |
| ------------------------------------------------------------- | -------- |
| [`Ask`](ichartcluster.cs.md#property-ask)                     | _===_    |
| [`AskTrades`](ichartcluster.cs.md#property-asktrades)         | _===_    |
| [`Bid`](ichartcluster.cs.md#property-bid)                     | _===_    |
| [`BidTrades`](ichartcluster.cs.md#property-bidtrades)         | _===_    |
| [`Close`](ichartcluster.cs.md#property-close)                 | _===_    |
| [`CloseTime`](ichartcluster.cs.md#property-closetime)         | _===_    |
| [`Delta`](ichartcluster.cs.md#property-delta)                 | _===_    |
| [`DeltaHigh`](ichartcluster.cs.md#property-deltahigh)         | _===_    |
| [`DeltaLow`](ichartcluster.cs.md#property-deltalow)           | _===_    |
| [`High`](ichartcluster.cs.md#property-high)                   | _===_    |
| [`IsUp`](ichartcluster.cs.md#property-isup)                   | _===_    |
| [`Low`](ichartcluster.cs.md#property-low)                     | _===_    |
| [`MaxValues`](ichartcluster.cs.md#property-maxvalues)         | _===_    |
| [`Open`](ichartcluster.cs.md#property-open)                   | _===_    |
| [`OpenPos`](ichartcluster.cs.md#property-openpos)             | _===_    |
| [`OpenPosAskChg`](ichartcluster.cs.md#property-openposaskchg) | _===_    |
| [`OpenPosBidChg`](ichartcluster.cs.md#property-openposbidchg) | _===_    |
| [`OpenPosChg`](ichartcluster.cs.md#property-openposchg)       | _===_    |
| [`OpenPosHigh`](ichartcluster.cs.md#property-openposhigh)     | _===_    |
| [`OpenPosLow`](ichartcluster.cs.md#property-openposlow)       | _===_    |
| [`OpenTime`](ichartcluster.cs.md#property-opentime)           | _===_    |
| [`Time`](ichartcluster.cs.md#property-time)                   | _===_    |
| [`Trades`](ichartcluster.cs.md#property-trades)               | _===_    |
| [`Volume`](ichartcluster.cs.md#property-volume)               | _===_    |

***

***

## Методы

### `GetItem` <a href="#method-getitem" id="method-getitem"></a>

\===

```csharp
IChartClusterItem GetItem(Decimal price)
```

`price` _<mark style="color:red;">`Decimal`</mark>_\
_===_

***

***

***

## Свойства

### `Ask` <a href="#property-ask" id="property-ask"></a>

\===

```csharp
Decimal Ask { get; }
```

***

### `AskTrades` <a href="#property-asktrades" id="property-asktrades"></a>

\===

```csharp
int AskTrades { get; }
```

***

### `Bid` <a href="#property-bid" id="property-bid"></a>

\===

```csharp
Decimal Bid { get; }
```

***

### `BidTrades` <a href="#property-bidtrades" id="property-bidtrades"></a>

\===

```csharp
int BidTrades { get; }
```

***

### `Close` <a href="#property-close" id="property-close"></a>

\===

```csharp
Decimal Close { get; }
```

***

### `CloseTime` <a href="#property-closetime" id="property-closetime"></a>

\===

```csharp
DateTime CloseTime { get; }
```

***

### `Delta` <a href="#property-delta" id="property-delta"></a>

\===

```csharp
Decimal Delta { get; }
```

***

### `DeltaHigh` <a href="#property-deltahigh" id="property-deltahigh"></a>

\===

```csharp
Decimal DeltaHigh { get; }
```

***

### `DeltaLow` <a href="#property-deltalow" id="property-deltalow"></a>

\===

```csharp
Decimal DeltaLow { get; }
```

***

### `High` <a href="#property-high" id="property-high"></a>

\===

```csharp
Decimal High { get; }
```

***

### `IsUp` <a href="#property-isup" id="property-isup"></a>

\===

```csharp
bool IsUp { get; }
```

***

### `Low` <a href="#property-low" id="property-low"></a>

\===

```csharp
Decimal Low { get; }
```

***

### `MaxValues` <a href="#property-maxvalues" id="property-maxvalues"></a>

\===

```csharp
IChartClusterMaxValues MaxValues { get; }
```

***

### `Open` <a href="#property-open" id="property-open"></a>

\===

```csharp
Decimal Open { get; }
```

***

### `OpenPos` <a href="#property-openpos" id="property-openpos"></a>

\===

```csharp
long OpenPos { get; }
```

***

### `OpenPosAskChg` <a href="#property-openposaskchg" id="property-openposaskchg"></a>

\===

```csharp
long OpenPosAskChg { get; }
```

***

### `OpenPosBidChg` <a href="#property-openposbidchg" id="property-openposbidchg"></a>

\===

```csharp
long OpenPosBidChg { get; }
```

***

### `OpenPosChg` <a href="#property-openposchg" id="property-openposchg"></a>

\===

```csharp
long OpenPosChg { get; }
```

***

### `OpenPosHigh` <a href="#property-openposhigh" id="property-openposhigh"></a>

\===

```csharp
long OpenPosHigh { get; }
```

***

### `OpenPosLow` <a href="#property-openposlow" id="property-openposlow"></a>

\===

```csharp
long OpenPosLow { get; }
```

***

### `OpenTime` <a href="#property-opentime" id="property-opentime"></a>

\===

```csharp
DateTime OpenTime { get; }
```

***

### `Time` <a href="#property-time" id="property-time"></a>

\===

```csharp
DateTime Time { get; }
```

***

### `Trades` <a href="#property-trades" id="property-trades"></a>

\===

```csharp
int Trades { get; }
```

***

### `Volume` <a href="#property-volume" id="property-volume"></a>

\===

```csharp
Decimal Volume { get; }
```

***
