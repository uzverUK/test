
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class RawCluster : IRawCluster
```


## Таблица методов
| Название | Описание |
| --- | --- |
| [`AddCluster`](./RawCluster.cs/Методы/AddCluster.md) | *Описание* |
| [`AddItem`](./RawCluster.cs/Методы/AddItem.md) | *Описание* |
| [`AddTick`](./RawCluster.cs/Методы/AddTick.md) | *Описание* |
| [`GetItem`](./RawCluster.cs/Методы/GetItem.md) | *Описание* |
| [`GetValueArea`](./RawCluster.cs/Методы/GetValueArea.md) | *Описание* |
| [`RawCluster`](./RawCluster.cs/Методы/RawCluster.md) | *Описание* |
| [`UpdateData`](./RawCluster.cs/Методы/UpdateData.md) | *Описание* |

## Таблица свойств
| Название | Описание |
| --- | --- |
| [`Ask`](./RawCluster.cs/Свойства/Ask.md) | *Описание* |
| [`AskTrades`](./RawCluster.cs/Свойства/AskTrades.md) | *Описание* |
| [`Bid`](./RawCluster.cs/Свойства/Bid.md) | *Описание* |
| [`BidTrades`](./RawCluster.cs/Свойства/BidTrades.md) | *Описание* |
| [`Close`](./RawCluster.cs/Свойства/Close.md) | *Описание* |
| [`CloseTime`](./RawCluster.cs/Свойства/CloseTime.md) | *Описание* |
| [`Delta`](./RawCluster.cs/Свойства/Delta.md) | *Описание* |
| [`DeltaHigh`](./RawCluster.cs/Свойства/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./RawCluster.cs/Свойства/DeltaLow.md) | *Описание* |
| [`High`](./RawCluster.cs/Свойства/High.md) | *Описание* |
| [`IsUp`](./RawCluster.cs/Свойства/IsUp.md) | *Описание* |
| [`Items`](./RawCluster.cs/Свойства/Items.md) | *Описание* |
| [`Low`](./RawCluster.cs/Свойства/Low.md) | *Описание* |
| [`MaxValues`](./RawCluster.cs/Свойства/MaxValues.md) | *Описание* |
| [`Open`](./RawCluster.cs/Свойства/Open.md) | *Описание* |
| [`OpenPos`](./RawCluster.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosAskChg`](./RawCluster.cs/Свойства/OpenPosAskChg.md) | *Описание* |
| [`OpenPosBidChg`](./RawCluster.cs/Свойства/OpenPosBidChg.md) | *Описание* |
| [`OpenPosChg`](./RawCluster.cs/Свойства/OpenPosChg.md) | *Описание* |
| [`OpenPosHigh`](./RawCluster.cs/Свойства/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./RawCluster.cs/Свойства/OpenPosLow.md) | *Описание* |
| [`OpenTime`](./RawCluster.cs/Свойства/OpenTime.md) | *Описание* |
| [`Time`](./RawCluster.cs/Свойства/Time.md) | *Описание* |
| [`Trades`](./RawCluster.cs/Свойства/Trades.md) | *Описание* |
| [`Volume`](./RawCluster.cs/Свойства/Volume.md) | *Описание* |




            ***
  ***
  # Методы

## AddCluster
Описание

```csharp
public void AddCluster(IRawCluster cluster)
```

<mark style="color:yellow;">`cluster`</mark> <mark style="color:red;">*`IRawCluster`*</mark>  
 *Описание*  


***                

## AddItem
Описание

```csharp
public void AddItem(IRawClusterItem item)
```
<mark style="color:yellow;">`item`</mark> <mark style="color:red;">*`IRawClusterItem`*</mark>  
 *Описание*  


***                

## AddTick
Описание

```csharp
public void AddTick(IRawTick tick, int scale)
```
<mark style="color:yellow;">`tick`</mark> <mark style="color:red;">*`IRawTick`*</mark>  
 *Описание*  

<mark style="color:yellow;">`scale`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## GetItem
Описание

```csharp
public IRawClusterItem GetItem(long price)
```
<mark style="color:yellow;">`price`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***                

## GetValueArea
Описание

```csharp
public IRawClusterValueArea GetValueArea(int valueArea)
```
<mark style="color:yellow;">`valueArea`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## RawCluster
Описание

```csharp
public RawCluster(DateTime time)
```
<mark style="color:yellow;">`time`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***                

## UpdateData
Описание

```csharp
public void UpdateData()
```

***                
                ***
  ***
  # Свойства

## Ask
Описание

```csharp
public long Ask { get; private set; }
```
***

## AskTrades
Описание

```csharp
public int AskTrades { get; private set; }
```
***

## Bid
Описание

```csharp
public long Bid { get; private set; }
```
***

## BidTrades
Описание

```csharp
public int BidTrades { get; private set; }
```
***

## Close
Описание

```csharp
public long Close { get; set; }
```
***

## CloseTime
Описание

```csharp
public DateTime CloseTime { get; private set; }
```
***

## Delta
Описание

```csharp
public long Delta { get; }
```
***

## DeltaHigh
Описание

```csharp
public long DeltaHigh { get; private set; }
```
***

## DeltaLow
Описание

```csharp
public long DeltaLow { get; private set; }
```
***

## High
Описание

```csharp
public long High { get; set; }
```
***

## IsUp
Описание

```csharp
public bool IsUp { get; set; }
```
***

## Items
Описание

```csharp
public List<IRawClusterItem> Items { get; }
```
***

## Low
Описание

```csharp
public long Low { get; set; }
```
***

## MaxValues
Описание

```csharp
public IRawClusterMaxValues MaxValues { get; }
```
***

## Open
Описание

```csharp
public long Open { get; set; }
```
***

## OpenPos
Описание

```csharp
public long OpenPos { get; private set; }
```
***

## OpenPosAskChg
Описание

```csharp
public long OpenPosAskChg { get; private set; }
```
***

## OpenPosBidChg
Описание

```csharp
public long OpenPosBidChg { get; private set; }
```
***

## OpenPosChg
Описание

```csharp
public long OpenPosChg { get; }
```
***

## OpenPosHigh
Описание

```csharp
public long OpenPosHigh { get; private set; }
```
***

## OpenPosLow
Описание

```csharp
public long OpenPosLow { get; private set; }
```
***

## OpenTime
Описание

```csharp
public DateTime OpenTime { get; private set; }
```
***

## Time
Описание

```csharp
public DateTime Time { get; }
```
***

## Trades
Описание

```csharp
public int Trades { get; }
```
***

## Volume
Описание

```csharp
public long Volume { get; }
```
***

