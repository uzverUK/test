# RawCluster

`namespace` [TigerTrade.Chart](../../../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class RawCluster : IRawCluster
```

## Список методов

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`AddCluster`](rawcluster.cs.md#method-addcluster)     | _===_    |
| [`AddItem`](rawcluster.cs.md#method-additem)           | _===_    |
| [`AddTick`](rawcluster.cs.md#method-addtick)           | _===_    |
| [`GetItem`](rawcluster.cs.md#method-getitem)           | _===_    |
| [`GetValueArea`](rawcluster.cs.md#method-getvaluearea) | _===_    |
| [`RawCluster`](rawcluster.cs.md#method-rawcluster)     | _===_    |
| [`UpdateData`](rawcluster.cs.md#method-updatedata)     | _===_    |

## Список свойств

| Название                                                   | Описание |
| ---------------------------------------------------------- | -------- |
| [`Ask`](rawcluster.cs.md#property-ask)                     | _===_    |
| [`AskTrades`](rawcluster.cs.md#property-asktrades)         | _===_    |
| [`Bid`](rawcluster.cs.md#property-bid)                     | _===_    |
| [`BidTrades`](rawcluster.cs.md#property-bidtrades)         | _===_    |
| [`Close`](rawcluster.cs.md#property-close)                 | _===_    |
| [`CloseTime`](rawcluster.cs.md#property-closetime)         | _===_    |
| [`Delta`](rawcluster.cs.md#property-delta)                 | _===_    |
| [`DeltaHigh`](rawcluster.cs.md#property-deltahigh)         | _===_    |
| [`DeltaLow`](rawcluster.cs.md#property-deltalow)           | _===_    |
| [`High`](rawcluster.cs.md#property-high)                   | _===_    |
| [`IsUp`](rawcluster.cs.md#property-isup)                   | _===_    |
| [`Items`](rawcluster.cs.md#property-items)                 | _===_    |
| [`Low`](rawcluster.cs.md#property-low)                     | _===_    |
| [`MaxValues`](rawcluster.cs.md#property-maxvalues)         | _===_    |
| [`Open`](rawcluster.cs.md#property-open)                   | _===_    |
| [`OpenPos`](rawcluster.cs.md#property-openpos)             | _===_    |
| [`OpenPosAskChg`](rawcluster.cs.md#property-openposaskchg) | _===_    |
| [`OpenPosBidChg`](rawcluster.cs.md#property-openposbidchg) | _===_    |
| [`OpenPosChg`](rawcluster.cs.md#property-openposchg)       | _===_    |
| [`OpenPosHigh`](rawcluster.cs.md#property-openposhigh)     | _===_    |
| [`OpenPosLow`](rawcluster.cs.md#property-openposlow)       | _===_    |
| [`OpenTime`](rawcluster.cs.md#property-opentime)           | _===_    |
| [`Time`](rawcluster.cs.md#property-time)                   | _===_    |
| [`Trades`](rawcluster.cs.md#property-trades)               | _===_    |
| [`Volume`](rawcluster.cs.md#property-volume)               | _===_    |

***

***

## Методы

### `AddCluster` <a href="#method-addcluster" id="method-addcluster"></a>

\===

```csharp
public void AddCluster(IRawCluster cluster)
```

`cluster` _<mark style="color:red;">`IRawCluster`</mark>_\
_===_

***

### `AddItem` <a href="#method-additem" id="method-additem"></a>

\===

```csharp
public void AddItem(IRawClusterItem item)
```

`item` _<mark style="color:red;">`IRawClusterItem`</mark>_\
_===_

***

### `AddTick` <a href="#method-addtick" id="method-addtick"></a>

\===

```csharp
public void AddTick(IRawTick tick, int scale)
```

`tick` _<mark style="color:red;">`IRawTick`</mark>_\
_===_

`scale` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `GetItem` <a href="#method-getitem" id="method-getitem"></a>

\===

```csharp
public IRawClusterItem GetItem(long price)
```

`price` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `GetValueArea` <a href="#method-getvaluearea" id="method-getvaluearea"></a>

\===

```csharp
public IRawClusterValueArea GetValueArea(int valueArea)
```

`valueArea` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `RawCluster` <a href="#method-rawcluster" id="method-rawcluster"></a>

\===

```csharp
public RawCluster(DateTime time)
```

`time` _<mark style="color:red;">`DateTime`</mark>_\
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
public long Ask { get; private set; }
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
public long Bid { get; private set; }
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
public long Close { get; set; }
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
public long Delta { get; }
```

***

### `DeltaHigh` <a href="#property-deltahigh" id="property-deltahigh"></a>

\===

```csharp
public long DeltaHigh { get; private set; }
```

***

### `DeltaLow` <a href="#property-deltalow" id="property-deltalow"></a>

\===

```csharp
public long DeltaLow { get; private set; }
```

***

### `High` <a href="#property-high" id="property-high"></a>

\===

```csharp
public long High { get; set; }
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
public List<IRawClusterItem> Items { get; }
```

***

### `Low` <a href="#property-low" id="property-low"></a>

\===

```csharp
public long Low { get; set; }
```

***

### `MaxValues` <a href="#property-maxvalues" id="property-maxvalues"></a>

\===

```csharp
public IRawClusterMaxValues MaxValues { get; }
```

***

### `Open` <a href="#property-open" id="property-open"></a>

\===

```csharp
public long Open { get; set; }
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
public long Volume { get; }
```

***
