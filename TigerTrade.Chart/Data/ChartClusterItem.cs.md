
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class ChartClusterItem : IChartClusterItem
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`Add`](./ChartClusterItem.cs/Методы/Add.md) | *Описание* |
| [`ChartClusterItem`](./ChartClusterItem.cs/Методы/ChartClusterItem.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Ask`](./ChartClusterItem.cs/Свойства/Ask.md) | *Описание* |
| [`AskTrades`](./ChartClusterItem.cs/Свойства/AskTrades.md) | *Описание* |
| [`Bid`](./ChartClusterItem.cs/Свойства/Bid.md) | *Описание* |
| [`BidTrades`](./ChartClusterItem.cs/Свойства/BidTrades.md) | *Описание* |
| [`Delta`](./ChartClusterItem.cs/Свойства/Delta.md) | *Описание* |
| [`OpenPos`](./ChartClusterItem.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosAsk`](./ChartClusterItem.cs/Свойства/OpenPosAsk.md) | *Описание* |
| [`OpenPosBid`](./ChartClusterItem.cs/Свойства/OpenPosBid.md) | *Описание* |
| [`Price`](./ChartClusterItem.cs/Свойства/Price.md) | *Описание* |
| [`Trades`](./ChartClusterItem.cs/Свойства/Trades.md) | *Описание* |
| [`Volume`](./ChartClusterItem.cs/Свойства/Volume.md) | *Описание* |




            ***
  ***
  # Методы

## Add
Описание

```csharp
public void Add(IChartClusterItem item)
```

<mark style="color:yellow;">`item`</mark> <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *Описание*  


***                

## ChartClusterItem
Описание

```csharp
public ChartClusterItem(Decimal price)
```
<mark style="color:yellow;">`price`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***                

## ChartClusterItem
Описание

```csharp
public ChartClusterItem(Decimal price)
public ChartClusterItem(IChartClusterItem item)
```
<mark style="color:yellow;">`price`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

<mark style="color:yellow;">`item`</mark> <mark style="color:red;">*`IChartClusterItem`*</mark>  
 *Описание*  


***                
                ***
  ***
  # Свойства

## Ask
Описание

```csharp
public Decimal Ask { get; set; }
```
***

## AskTrades
Описание

```csharp
public int AskTrades { get; set; }
```
***

## Bid
Описание

```csharp
public Decimal Bid { get; set; }
```
***

## BidTrades
Описание

```csharp
public int BidTrades { get; set; }
```
***

## Delta
Описание

```csharp
public Decimal Delta { get; }
```
***

## OpenPos
Описание

```csharp
public long OpenPos { get; }
```
***

## OpenPosAsk
Описание

```csharp
public long OpenPosAsk { get; set; }
```
***

## OpenPosBid
Описание

```csharp
public long OpenPosBid { get; set; }
```
***

## Price
Описание

```csharp
public Decimal Price { get; set; }
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
public Decimal Volume { get; }
```
***

