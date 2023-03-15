
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class ChartCluster : IChartCluster
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`AddCluster`](./ChartCluster.cs/Методы/AddCluster.md) | *Описание* |
| [`AddItem`](./ChartCluster.cs/Методы/AddItem.md) | *Описание* |
| [`AddTick`](./ChartCluster.cs/Методы/AddTick.md) | *Описание* |
| [`ChartCluster`](./ChartCluster.cs/Методы/ChartCluster.md) | *Описание* |
| [`GetItem`](./ChartCluster.cs/Методы/GetItem.md) | *Описание* |
| [`UpdateData`](./ChartCluster.cs/Методы/UpdateData.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Ask`](./ChartCluster.cs/Свойства/Ask.md) | *Описание* |
| [`AskTrades`](./ChartCluster.cs/Свойства/AskTrades.md) | *Описание* |
| [`Bid`](./ChartCluster.cs/Свойства/Bid.md) | *Описание* |
| [`BidTrades`](./ChartCluster.cs/Свойства/BidTrades.md) | *Описание* |
| [`Close`](./ChartCluster.cs/Свойства/Close.md) | *Описание* |
| [`CloseTime`](./ChartCluster.cs/Свойства/CloseTime.md) | *Описание* |
| [`Delta`](./ChartCluster.cs/Свойства/Delta.md) | *Описание* |
| [`DeltaHigh`](./ChartCluster.cs/Свойства/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./ChartCluster.cs/Свойства/DeltaLow.md) | *Описание* |
| [`High`](./ChartCluster.cs/Свойства/High.md) | *Описание* |
| [`IsUp`](./ChartCluster.cs/Свойства/IsUp.md) | *Описание* |
| [`Items`](./ChartCluster.cs/Свойства/Items.md) | *Описание* |
| [`Low`](./ChartCluster.cs/Свойства/Low.md) | *Описание* |
| [`MaxValues`](./ChartCluster.cs/Свойства/MaxValues.md) | *Описание* |
| [`Open`](./ChartCluster.cs/Свойства/Open.md) | *Описание* |
| [`OpenPos`](./ChartCluster.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosAskChg`](./ChartCluster.cs/Свойства/OpenPosAskChg.md) | *Описание* |
| [`OpenPosBidChg`](./ChartCluster.cs/Свойства/OpenPosBidChg.md) | *Описание* |
| [`OpenPosChg`](./ChartCluster.cs/Свойства/OpenPosChg.md) | *Описание* |
| [`OpenPosHigh`](./ChartCluster.cs/Свойства/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./ChartCluster.cs/Свойства/OpenPosLow.md) | *Описание* |
| [`OpenTime`](./ChartCluster.cs/Свойства/OpenTime.md) | *Описание* |
| [`Step`](./ChartCluster.cs/Свойства/Step.md) | *Описание* |
| [`Time`](./ChartCluster.cs/Свойства/Time.md) | *Описание* |
| [`Trades`](./ChartCluster.cs/Свойства/Trades.md) | *Описание* |
| [`Volume`](./ChartCluster.cs/Свойства/Volume.md) | *Описание* |





# Методы

## *AddCluster*
Описание

```csharp
public void AddCluster(IChartCluster cluster)
```

<mark style="color:yellow;">`cluster`</mark> <mark style="color:red;">*`IChartCluster`*</mark>  
 *Описание*  



## *AddItem*
Описание

```csharp
public void AddItem(IChartClusterItem item)
```
<mark style="color:yellow;">`item`</mark> <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *Описание*  



## *AddTick*
Описание

```csharp
public void AddTick(IChartTick tick)
```
<mark style="color:yellow;">`tick`</mark> <mark style="color:red;">*`IChartTick`*</mark>  
 *Описание*  



## *ChartCluster*
Описание

```csharp
public ChartCluster(DateTime time, Decimal step)
```
<mark style="color:yellow;">`time`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

<mark style="color:yellow;">`step`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  



## *GetItem*
Описание

```csharp
public IChartClusterItem GetItem(Decimal price)
```
<mark style="color:yellow;">`price`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  



## *UpdateData*
Описание

```csharp
public void UpdateData()
```

# Свойства

## *Ask*
Описание

```csharp
public Decimal Ask { get; private set; }
```

## *AskTrades*
Описание

```csharp
public int AskTrades { get; private set; }
```

## *Bid*
Описание

```csharp
public Decimal Bid { get; private set; }
```

## *BidTrades*
Описание

```csharp
public int BidTrades { get; private set; }
```

## *Close*
Описание

```csharp
public Decimal Close { get; set; }
```

## *CloseTime*
Описание

```csharp
public DateTime CloseTime { get; private set; }
```

## *Delta*
Описание

```csharp
public Decimal Delta { get; }
```

## *DeltaHigh*
Описание

```csharp
public Decimal DeltaHigh { get; private set; }
```

## *DeltaLow*
Описание

```csharp
public Decimal DeltaLow { get; private set; }
```

## *High*
Описание

```csharp
public Decimal High { get; set; }
```

## *IsUp*
Описание

```csharp
public bool IsUp { get; set; }
```

## *Items*
Описание

```csharp
public List<IChartClusterItem> Items { get; }
```

## *Low*
Описание

```csharp
public Decimal Low { get; set; }
```

## *MaxValues*
Описание

```csharp
public IChartClusterMaxValues MaxValues { get; }
```

## *Open*
Описание

```csharp
public Decimal Open { get; set; }
```

## *OpenPos*
Описание

```csharp
public long OpenPos { get; private set; }
```

## *OpenPosAskChg*
Описание

```csharp
public long OpenPosAskChg { get; private set; }
```

## *OpenPosBidChg*
Описание

```csharp
public long OpenPosBidChg { get; private set; }
```

## *OpenPosChg*
Описание

```csharp
public long OpenPosChg { get; }
```

## *OpenPosHigh*
Описание

```csharp
public long OpenPosHigh { get; private set; }
```

## *OpenPosLow*
Описание

```csharp
public long OpenPosLow { get; private set; }
```

## *OpenTime*
Описание

```csharp
public DateTime OpenTime { get; private set; }
```

## *Step*
Описание

```csharp
public Decimal Step { get; }
```

## *Time*
Описание

```csharp
public DateTime Time { get; }
```

## *Trades*
Описание

```csharp
public int Trades { get; }
```

## *Volume*
Описание

```csharp
public Decimal Volume { get; }
```

