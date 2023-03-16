# ChartCluster

`namespace` [TigerTrade.Chart](../../../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class ChartCluster : IChartCluster
```

## Список методов

| Название                                                 | Описание |
| -------------------------------------------------------- | -------- |
| [`AddCluster`](chartcluster.cs.md#method-addcluster)     | _===_    |
| [`AddItem`](chartcluster.cs.md#method-additem)           | _===_    |
| [`AddTick`](chartcluster.cs.md#method-addtick)           | _===_    |
| [`ChartCluster`](chartcluster.cs.md#method-chartcluster) | _===_    |
| [`GetItem`](chartcluster.cs.md#method-getitem)           | _===_    |
| [`UpdateData`](chartcluster.cs.md#method-updatedata)     | _===_    |

## Список свойств

| Название                                                     | Описание |
| ------------------------------------------------------------ | -------- |
| [`Ask`](chartcluster.cs.md#property-ask)                     | _===_    |
| [`AskTrades`](chartcluster.cs.md#property-asktrades)         | _===_    |
| [`Bid`](chartcluster.cs.md#property-bid)                     | _===_    |
| [`BidTrades`](chartcluster.cs.md#property-bidtrades)         | _===_    |
| [`Close`](chartcluster.cs.md#property-close)                 | _===_    |
| [`CloseTime`](chartcluster.cs.md#property-closetime)         | _===_    |
| [`Delta`](chartcluster.cs.md#property-delta)                 | _===_    |
| [`DeltaHigh`](chartcluster.cs.md#property-deltahigh)         | _===_    |
| [`DeltaLow`](chartcluster.cs.md#property-deltalow)           | _===_    |
| [`High`](chartcluster.cs.md#property-high)                   | _===_    |
| [`IsUp`](chartcluster.cs.md#property-isup)                   | _===_    |
| [`Items`](chartcluster.cs.md#property-items)                 | _===_    |
| [`Low`](chartcluster.cs.md#property-low)                     | _===_    |
| [`MaxValues`](chartcluster.cs.md#property-maxvalues)         | _===_    |
| [`Open`](chartcluster.cs.md#property-open)                   | _===_    |
| [`OpenPos`](chartcluster.cs.md#property-openpos)             | _===_    |
| [`OpenPosAskChg`](chartcluster.cs.md#property-openposaskchg) | _===_    |
| [`OpenPosBidChg`](chartcluster.cs.md#property-openposbidchg) | _===_    |
| [`OpenPosChg`](chartcluster.cs.md#property-openposchg)       | _===_    |
| [`OpenPosHigh`](chartcluster.cs.md#property-openposhigh)     | _===_    |
| [`OpenPosLow`](chartcluster.cs.md#property-openposlow)       | _===_    |
| [`OpenTime`](chartcluster.cs.md#property-opentime)           | _===_    |
| [`Step`](chartcluster.cs.md#property-step)                   | _===_    |
| [`Time`](chartcluster.cs.md#property-time)                   | _===_    |
| [`Trades`](chartcluster.cs.md#property-trades)               | _===_    |
| [`Volume`](chartcluster.cs.md#property-volume)               | _===_    |

***

***

## Методы

### `AddCluster` <a href="#method-addcluster" id="method-addcluster"></a>

\===

```csharp
public void AddCluster(IChartCluster cluster)
```

`cluster` _<mark style="color:red;">`IChartCluster`</mark>_\
_===_

***

### `AddItem` <a href="#method-additem" id="method-additem"></a>

\===

```csharp
public void AddItem(IChartClusterItem item)
```

`item` _<mark style="color:red;">`IChartClusterItem`</mark>_\
_===_

***

### `AddTick` <a href="#method-addtick" id="method-addtick"></a>

\===

```csharp
public void AddTick(IChartTick tick)
```

`tick` _<mark style="color:red;">`IChartTick`</mark>_\
_===_

***

### `ChartCluster` <a href="#method-chartcluster" id="method-chartcluster"></a>

\===

```csharp
public ChartCluster(DateTime time, Decimal step)
```

`time` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`step` _<mark style="color:red;">`Decimal`</mark>_\
_===_

***

### `GetItem` <a href="#method-getitem" id="method-getitem"></a>

\===

```csharp
public IChartClusterItem GetItem(Decimal price)
```

`price` _<mark style="color:red;">`Decimal`</mark>_\
_===_

***

### `UpdateData` <a href="#method-updatedata" id="method-updatedata"></a>

\===

```csharp
public void UpdateData()
```

***

***

***

## Свойства

### `Ask` <a href="#property-ask" id="property-ask"></a>

\===

```csharp
public Decimal Ask { get; private set; }
```

***

### `AskTrades` <a href="#property-asktrades" id="property-asktrades"></a>

\===

```csharp
public int AskTrades { get; private set; }
```

***

### `Bid` <a href="#property-bid" id="property-bid"></a>

\===

```csharp
public Decimal Bid { get; private set; }
```

***

### `BidTrades` <a href="#property-bidtrades" id="property-bidtrades"></a>

\===

```csharp
public int BidTrades { get; private set; }
```

***

### `Close` <a href="#property-close" id="property-close"></a>

\===

```csharp
public Decimal Close { get; set; }
```

***

### `CloseTime` <a href="#property-closetime" id="property-closetime"></a>

\===

```csharp
public DateTime CloseTime { get; private set; }
```

***

### `Delta` <a href="#property-delta" id="property-delta"></a>

\===

```csharp
public Decimal Delta { get; }
```

***

### `DeltaHigh` <a href="#property-deltahigh" id="property-deltahigh"></a>

\===

```csharp
public Decimal DeltaHigh { get; private set; }
```

***

### `DeltaLow` <a href="#property-deltalow" id="property-deltalow"></a>

\===

```csharp
public Decimal DeltaLow { get; private set; }
```

***

### `High` <a href="#property-high" id="property-high"></a>

\===

```csharp
public Decimal High { get; set; }
```

***

### `IsUp` <a href="#property-isup" id="property-isup"></a>

\===

```csharp
public bool IsUp { get; set; }
```

***

### `Items` <a href="#property-items" id="property-items"></a>

\===

```csharp
public List<IChartClusterItem> Items { get; }
```

***

### `Low` <a href="#property-low" id="property-low"></a>

\===

```csharp
public Decimal Low { get; set; }
```

***

### `MaxValues` <a href="#property-maxvalues" id="property-maxvalues"></a>

\===

```csharp
public IChartClusterMaxValues MaxValues { get; }
```

***

### `Open` <a href="#property-open" id="property-open"></a>

\===

```csharp
public Decimal Open { get; set; }
```

***

### `OpenPos` <a href="#property-openpos" id="property-openpos"></a>

\===

```csharp
public long OpenPos { get; private set; }
```

***

### `OpenPosAskChg` <a href="#property-openposaskchg" id="property-openposaskchg"></a>

\===

```csharp
public long OpenPosAskChg { get; private set; }
```

***

### `OpenPosBidChg` <a href="#property-openposbidchg" id="property-openposbidchg"></a>

\===

```csharp
public long OpenPosBidChg { get; private set; }
```

***

### `OpenPosChg` <a href="#property-openposchg" id="property-openposchg"></a>

\===

```csharp
public long OpenPosChg { get; }
```

***

### `OpenPosHigh` <a href="#property-openposhigh" id="property-openposhigh"></a>

\===

```csharp
public long OpenPosHigh { get; private set; }
```

***

### `OpenPosLow` <a href="#property-openposlow" id="property-openposlow"></a>

\===

```csharp
public long OpenPosLow { get; private set; }
```

***

### `OpenTime` <a href="#property-opentime" id="property-opentime"></a>

\===

```csharp
public DateTime OpenTime { get; private set; }
```

***

### `Step` <a href="#property-step" id="property-step"></a>

\===

```csharp
public Decimal Step { get; }
```

***

### `Time` <a href="#property-time" id="property-time"></a>

\===

```csharp
public DateTime Time { get; }
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
