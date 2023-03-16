# ChartClusterMaxValues

`namespace` [TigerTrade.Chart](../../../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class ChartClusterMaxValues : IChartClusterMaxValues
```

## Список методов

| Название                                                                            | Описание |
| ----------------------------------------------------------------------------------- | -------- |
| [`ChartClusterMaxValues`](chartclustermaxvalues.cs.md#method-chartclustermaxvalues) | _===_    |
| [`Update`](chartclustermaxvalues.cs.md#method-update)                               | _===_    |

## Список свойств

| Название                                                        | Описание |
| --------------------------------------------------------------- | -------- |
| [`MaxAsk`](chartclustermaxvalues.cs.md#property-maxask)         | _===_    |
| [`MaxBid`](chartclustermaxvalues.cs.md#property-maxbid)         | _===_    |
| [`MaxDelta`](chartclustermaxvalues.cs.md#property-maxdelta)     | _===_    |
| [`MaxOpenPos`](chartclustermaxvalues.cs.md#property-maxopenpos) | _===_    |
| [`MaxTrades`](chartclustermaxvalues.cs.md#property-maxtrades)   | _===_    |
| [`MaxVolume`](chartclustermaxvalues.cs.md#property-maxvolume)   | _===_    |
| [`MinDelta`](chartclustermaxvalues.cs.md#property-mindelta)     | _===_    |
| [`MinOpenPos`](chartclustermaxvalues.cs.md#property-minopenpos) | _===_    |
| [`Poc`](chartclustermaxvalues.cs.md#property-poc)               | _===_    |

***

***

## Методы

### `ChartClusterMaxValues` <a href="#method-chartclustermaxvalues" id="method-chartclustermaxvalues"></a>

\===

```csharp
public ChartClusterMaxValues()
```

***

### `Update` <a href="#method-update" id="method-update"></a>

\===

```csharp
public void Update(Dictionary<Decimal, ChartClusterItem> items)
```

***

***

***

## Свойства

### `MaxAsk` <a href="#property-maxask" id="property-maxask"></a>

\===

```csharp
public Decimal MaxAsk { get; private set; }
```

***

### `MaxBid` <a href="#property-maxbid" id="property-maxbid"></a>

\===

```csharp
public Decimal MaxBid { get; private set; }
```

***

### `MaxDelta` <a href="#property-maxdelta" id="property-maxdelta"></a>

\===

```csharp
public Decimal MaxDelta { get; private set; }
```

***

### `MaxOpenPos` <a href="#property-maxopenpos" id="property-maxopenpos"></a>

\===

```csharp
public long MaxOpenPos { get; private set; }
```

***

### `MaxTrades` <a href="#property-maxtrades" id="property-maxtrades"></a>

\===

```csharp
public int MaxTrades { get; private set; }
```

***

### `MaxVolume` <a href="#property-maxvolume" id="property-maxvolume"></a>

\===

```csharp
public Decimal MaxVolume { get; private set; }
```

***

### `MinDelta` <a href="#property-mindelta" id="property-mindelta"></a>

\===

```csharp
public Decimal MinDelta { get; private set; }
```

***

### `MinOpenPos` <a href="#property-minopenpos" id="property-minopenpos"></a>

\===

```csharp
public long MinOpenPos { get; private set; }
```

***

### `Poc` <a href="#property-poc" id="property-poc"></a>

\===

```csharp
public Decimal Poc { get; private set; }
```

***
