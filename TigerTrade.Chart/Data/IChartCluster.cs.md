
# IChartCluster
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)



Описаниеt

### Синтаксис
```csharp
public interface IChartCluster
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`GetItem`](./IChartCluster.cs/Методы/GetItem.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Ask`](./IChartCluster.cs/Свойства/Ask.md) | *Описание* |
| [`AskTrades`](./IChartCluster.cs/Свойства/AskTrades.md) | *Описание* |
| [`Bid`](./IChartCluster.cs/Свойства/Bid.md) | *Описание* |
| [`BidTrades`](./IChartCluster.cs/Свойства/BidTrades.md) | *Описание* |
| [`Close`](./IChartCluster.cs/Свойства/Close.md) | *Описание* |
| [`CloseTime`](./IChartCluster.cs/Свойства/CloseTime.md) | *Описание* |
| [`Delta`](./IChartCluster.cs/Свойства/Delta.md) | *Описание* |
| [`DeltaHigh`](./IChartCluster.cs/Свойства/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./IChartCluster.cs/Свойства/DeltaLow.md) | *Описание* |
| [`High`](./IChartCluster.cs/Свойства/High.md) | *Описание* |
| [`IsUp`](./IChartCluster.cs/Свойства/IsUp.md) | *Описание* |
| [`Low`](./IChartCluster.cs/Свойства/Low.md) | *Описание* |
| [`MaxValues`](./IChartCluster.cs/Свойства/MaxValues.md) | *Описание* |
| [`Open`](./IChartCluster.cs/Свойства/Open.md) | *Описание* |
| [`OpenPos`](./IChartCluster.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosAskChg`](./IChartCluster.cs/Свойства/OpenPosAskChg.md) | *Описание* |
| [`OpenPosBidChg`](./IChartCluster.cs/Свойства/OpenPosBidChg.md) | *Описание* |
| [`OpenPosChg`](./IChartCluster.cs/Свойства/OpenPosChg.md) | *Описание* |
| [`OpenPosHigh`](./IChartCluster.cs/Свойства/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./IChartCluster.cs/Свойства/OpenPosLow.md) | *Описание* |
| [`OpenTime`](./IChartCluster.cs/Свойства/OpenTime.md) | *Описание* |
| [`Time`](./IChartCluster.cs/Свойства/Time.md) | *Описание* |
| [`Trades`](./IChartCluster.cs/Свойства/Trades.md) | *Описание* |
| [`Volume`](./IChartCluster.cs/Свойства/Volume.md) | *Описание* |




            ***
  ***
  # Методы

## GetItem
Описание

```csharp
IChartClusterItem GetItem(Decimal price)
```

<mark style="color:yellow;">`price`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***                
                ***
  ***
  # Свойства

## Ask
Описание

```csharp
Decimal Ask { get; }
```
***

## AskTrades
Описание

```csharp
int AskTrades { get; }
```
***

## Bid
Описание

```csharp
Decimal Bid { get; }
```
***

## BidTrades
Описание

```csharp
int BidTrades { get; }
```
***

## Close
Описание

```csharp
Decimal Close { get; }
```
***

## CloseTime
Описание

```csharp
DateTime CloseTime { get; }
```
***

## Delta
Описание

```csharp
Decimal Delta { get; }
```
***

## DeltaHigh
Описание

```csharp
Decimal DeltaHigh { get; }
```
***

## DeltaLow
Описание

```csharp
Decimal DeltaLow { get; }
```
***

## High
Описание

```csharp
Decimal High { get; }
```
***

## IsUp
Описание

```csharp
bool IsUp { get; }
```
***

## Low
Описание

```csharp
Decimal Low { get; }
```
***

## MaxValues
Описание

```csharp
IChartClusterMaxValues MaxValues { get; }
```
***

## Open
Описание

```csharp
Decimal Open { get; }
```
***

## OpenPos
Описание

```csharp
long OpenPos { get; }
```
***

## OpenPosAskChg
Описание

```csharp
long OpenPosAskChg { get; }
```
***

## OpenPosBidChg
Описание

```csharp
long OpenPosBidChg { get; }
```
***

## OpenPosChg
Описание

```csharp
long OpenPosChg { get; }
```
***

## OpenPosHigh
Описание

```csharp
long OpenPosHigh { get; }
```
***

## OpenPosLow
Описание

```csharp
long OpenPosLow { get; }
```
***

## OpenTime
Описание

```csharp
DateTime OpenTime { get; }
```
***

## Time
Описание

```csharp
DateTime Time { get; }
```
***

## Trades
Описание

```csharp
int Trades { get; }
```
***

## Volume
Описание

```csharp
Decimal Volume { get; }
```
***

