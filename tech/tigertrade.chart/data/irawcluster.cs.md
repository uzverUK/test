# IRawCluster

`namespace` [TigerTrade.Chart](../../../).[Data](./)

\===

#### Синтаксис

```csharp
public interface IRawCluster
```

## Список методов

| Название                                                | Описание |
| ------------------------------------------------------- | -------- |
| [`GetItem`](irawcluster.cs.md#method-getitem)           | _===_    |
| [`GetValueArea`](irawcluster.cs.md#method-getvaluearea) | _===_    |

## Список свойств

| Название                                                    | Описание |
| ----------------------------------------------------------- | -------- |
| [`Ask`](irawcluster.cs.md#property-ask)                     | _===_    |
| [`AskTrades`](irawcluster.cs.md#property-asktrades)         | _===_    |
| [`Bid`](irawcluster.cs.md#property-bid)                     | _===_    |
| [`BidTrades`](irawcluster.cs.md#property-bidtrades)         | _===_    |
| [`Close`](irawcluster.cs.md#property-close)                 | _===_    |
| [`CloseTime`](irawcluster.cs.md#property-closetime)         | _===_    |
| [`Delta`](irawcluster.cs.md#property-delta)                 | _===_    |
| [`DeltaHigh`](irawcluster.cs.md#property-deltahigh)         | _===_    |
| [`DeltaLow`](irawcluster.cs.md#property-deltalow)           | _===_    |
| [`High`](irawcluster.cs.md#property-high)                   | _===_    |
| [`IsUp`](irawcluster.cs.md#property-isup)                   | _===_    |
| [`Low`](irawcluster.cs.md#property-low)                     | _===_    |
| [`MaxValues`](irawcluster.cs.md#property-maxvalues)         | _===_    |
| [`Open`](irawcluster.cs.md#property-open)                   | _===_    |
| [`OpenPos`](irawcluster.cs.md#property-openpos)             | _===_    |
| [`OpenPosAskChg`](irawcluster.cs.md#property-openposaskchg) | _===_    |
| [`OpenPosBidChg`](irawcluster.cs.md#property-openposbidchg) | _===_    |
| [`OpenPosChg`](irawcluster.cs.md#property-openposchg)       | _===_    |
| [`OpenPosHigh`](irawcluster.cs.md#property-openposhigh)     | _===_    |
| [`OpenPosLow`](irawcluster.cs.md#property-openposlow)       | _===_    |
| [`OpenTime`](irawcluster.cs.md#property-opentime)           | _===_    |
| [`Time`](irawcluster.cs.md#property-time)                   | _===_    |
| [`Trades`](irawcluster.cs.md#property-trades)               | _===_    |
| [`Volume`](irawcluster.cs.md#property-volume)               | _===_    |

***

***

## Методы

### `GetItem` <a href="#method-getitem" id="method-getitem"></a>

\===

```csharp
IRawClusterItem GetItem(long price)
```

`price` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `GetValueArea` <a href="#method-getvaluearea" id="method-getvaluearea"></a>

\===

```csharp
IRawClusterValueArea GetValueArea(int valueArea)
```

`valueArea` _<mark style="color:red;">`int`</mark>_\
_===_

***

***

***

## Свойства

### `Ask` <a href="#property-ask" id="property-ask"></a>

\===

```csharp
long Ask { get; }
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
long Bid { get; }
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
long Close { get; }
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
long Delta { get; }
```

***

### `DeltaHigh` <a href="#property-deltahigh" id="property-deltahigh"></a>

\===

```csharp
long DeltaHigh { get; }
```

***

### `DeltaLow` <a href="#property-deltalow" id="property-deltalow"></a>

\===

```csharp
long DeltaLow { get; }
```

***

### `High` <a href="#property-high" id="property-high"></a>

\===

```csharp
long High { get; }
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
long Low { get; }
```

***

### `MaxValues` <a href="#property-maxvalues" id="property-maxvalues"></a>

\===

```csharp
IRawClusterMaxValues MaxValues { get; }
```

***

### `Open` <a href="#property-open" id="property-open"></a>

\===

```csharp
long Open { get; }
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
long Volume { get; }
```

***
