
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public interface IRawCluster
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`GetItem`](./IRawCluster.cs/Методы/GetItem.md) | *Описание* |
| [`GetValueArea`](./IRawCluster.cs/Методы/GetValueArea.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Ask`](./IRawCluster.cs/Свойства/Ask.md) | *Описание* |
| [`AskTrades`](./IRawCluster.cs/Свойства/AskTrades.md) | *Описание* |
| [`Bid`](./IRawCluster.cs/Свойства/Bid.md) | *Описание* |
| [`BidTrades`](./IRawCluster.cs/Свойства/BidTrades.md) | *Описание* |
| [`Close`](./IRawCluster.cs/Свойства/Close.md) | *Описание* |
| [`CloseTime`](./IRawCluster.cs/Свойства/CloseTime.md) | *Описание* |
| [`Delta`](./IRawCluster.cs/Свойства/Delta.md) | *Описание* |
| [`DeltaHigh`](./IRawCluster.cs/Свойства/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./IRawCluster.cs/Свойства/DeltaLow.md) | *Описание* |
| [`High`](./IRawCluster.cs/Свойства/High.md) | *Описание* |
| [`IsUp`](./IRawCluster.cs/Свойства/IsUp.md) | *Описание* |
| [`Low`](./IRawCluster.cs/Свойства/Low.md) | *Описание* |
| [`MaxValues`](./IRawCluster.cs/Свойства/MaxValues.md) | *Описание* |
| [`Open`](./IRawCluster.cs/Свойства/Open.md) | *Описание* |
| [`OpenPos`](./IRawCluster.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosAskChg`](./IRawCluster.cs/Свойства/OpenPosAskChg.md) | *Описание* |
| [`OpenPosBidChg`](./IRawCluster.cs/Свойства/OpenPosBidChg.md) | *Описание* |
| [`OpenPosChg`](./IRawCluster.cs/Свойства/OpenPosChg.md) | *Описание* |
| [`OpenPosHigh`](./IRawCluster.cs/Свойства/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./IRawCluster.cs/Свойства/OpenPosLow.md) | *Описание* |
| [`OpenTime`](./IRawCluster.cs/Свойства/OpenTime.md) | *Описание* |
| [`Time`](./IRawCluster.cs/Свойства/Time.md) | *Описание* |
| [`Trades`](./IRawCluster.cs/Свойства/Trades.md) | *Описание* |
| [`Volume`](./IRawCluster.cs/Свойства/Volume.md) | *Описание* |





# Методы

## *GetItem*
Описание

```csharp
IRawClusterItem GetItem(long price)
```

<mark style="color:yellow;">`price`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  



## *GetValueArea*
Описание

```csharp
IRawClusterValueArea GetValueArea(int valueArea)
```
<mark style="color:yellow;">`valueArea`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


# Свойства

## *Ask*
Описание

```csharp
long Ask { get; }
```

## *AskTrades*
Описание

```csharp
int AskTrades { get; }
```

## *Bid*
Описание

```csharp
long Bid { get; }
```

## *BidTrades*
Описание

```csharp
int BidTrades { get; }
```

## *Close*
Описание

```csharp
long Close { get; }
```

## *CloseTime*
Описание

```csharp
DateTime CloseTime { get; }
```

## *Delta*
Описание

```csharp
long Delta { get; }
```

## *DeltaHigh*
Описание

```csharp
long DeltaHigh { get; }
```

## *DeltaLow*
Описание

```csharp
long DeltaLow { get; }
```

## *High*
Описание

```csharp
long High { get; }
```

## *IsUp*
Описание

```csharp
bool IsUp { get; }
```

## *Low*
Описание

```csharp
long Low { get; }
```

## *MaxValues*
Описание

```csharp
IRawClusterMaxValues MaxValues { get; }
```

## *Open*
Описание

```csharp
long Open { get; }
```

## *OpenPos*
Описание

```csharp
long OpenPos { get; }
```

## *OpenPosAskChg*
Описание

```csharp
long OpenPosAskChg { get; }
```

## *OpenPosBidChg*
Описание

```csharp
long OpenPosBidChg { get; }
```

## *OpenPosChg*
Описание

```csharp
long OpenPosChg { get; }
```

## *OpenPosHigh*
Описание

```csharp
long OpenPosHigh { get; }
```

## *OpenPosLow*
Описание

```csharp
long OpenPosLow { get; }
```

## *OpenTime*
Описание

```csharp
DateTime OpenTime { get; }
```

## *Time*
Описание

```csharp
DateTime Time { get; }
```

## *Trades*
Описание

```csharp
int Trades { get; }
```

## *Volume*
Описание

```csharp
long Volume { get; }
```

