
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class ChartClusterMaxValues : IChartClusterMaxValues
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ChartClusterMaxValues`](./ChartClusterMaxValues.cs/Методы/ChartClusterMaxValues.md) | *Описание* |
| [`Update`](./ChartClusterMaxValues.cs/Методы/Update.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`MaxAsk`](./ChartClusterMaxValues.cs/Свойства/MaxAsk.md) | *Описание* |
| [`MaxBid`](./ChartClusterMaxValues.cs/Свойства/MaxBid.md) | *Описание* |
| [`MaxDelta`](./ChartClusterMaxValues.cs/Свойства/MaxDelta.md) | *Описание* |
| [`MaxOpenPos`](./ChartClusterMaxValues.cs/Свойства/MaxOpenPos.md) | *Описание* |
| [`MaxTrades`](./ChartClusterMaxValues.cs/Свойства/MaxTrades.md) | *Описание* |
| [`MaxVolume`](./ChartClusterMaxValues.cs/Свойства/MaxVolume.md) | *Описание* |
| [`MinDelta`](./ChartClusterMaxValues.cs/Свойства/MinDelta.md) | *Описание* |
| [`MinOpenPos`](./ChartClusterMaxValues.cs/Свойства/MinOpenPos.md) | *Описание* |
| [`Poc`](./ChartClusterMaxValues.cs/Свойства/Poc.md) | *Описание* |





# Методы

## *ChartClusterMaxValues*
Описание

```csharp
public ChartClusterMaxValues()
```


## *Update*
Описание

```csharp
public void Update(Dictionary<Decimal, ChartClusterItem> items)
```

# Свойства

## *MaxAsk*
Описание

```csharp
public Decimal MaxAsk { get; private set; }
```

## *MaxBid*
Описание

```csharp
public Decimal MaxBid { get; private set; }
```

## *MaxDelta*
Описание

```csharp
public Decimal MaxDelta { get; private set; }
```

## *MaxOpenPos*
Описание

```csharp
public long MaxOpenPos { get; private set; }
```

## *MaxTrades*
Описание

```csharp
public int MaxTrades { get; private set; }
```

## *MaxVolume*
Описание

```csharp
public Decimal MaxVolume { get; private set; }
```

## *MinDelta*
Описание

```csharp
public Decimal MinDelta { get; private set; }
```

## *MinOpenPos*
Описание

```csharp
public long MinOpenPos { get; private set; }
```

## *Poc*
Описание

```csharp
public Decimal Poc { get; private set; }
```

