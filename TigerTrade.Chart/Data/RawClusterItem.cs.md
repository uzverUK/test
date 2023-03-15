
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class RawClusterItem : IRawClusterItem
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`Add`](./RawClusterItem.cs/Методы/Add.md) | *Описание* |
| [`RawClusterItem`](./RawClusterItem.cs/Методы/RawClusterItem.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Ask`](./RawClusterItem.cs/Свойства/Ask.md) | *Описание* |
| [`AskTrades`](./RawClusterItem.cs/Свойства/AskTrades.md) | *Описание* |
| [`Bid`](./RawClusterItem.cs/Свойства/Bid.md) | *Описание* |
| [`BidTrades`](./RawClusterItem.cs/Свойства/BidTrades.md) | *Описание* |
| [`Delta`](./RawClusterItem.cs/Свойства/Delta.md) | *Описание* |
| [`OpenPos`](./RawClusterItem.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosAsk`](./RawClusterItem.cs/Свойства/OpenPosAsk.md) | *Описание* |
| [`OpenPosBid`](./RawClusterItem.cs/Свойства/OpenPosBid.md) | *Описание* |
| [`Price`](./RawClusterItem.cs/Свойства/Price.md) | *Описание* |
| [`Trades`](./RawClusterItem.cs/Свойства/Trades.md) | *Описание* |
| [`Volume`](./RawClusterItem.cs/Свойства/Volume.md) | *Описание* |




            ***
  ***
  # Методы

## Add
Описание

```csharp
public void Add(IRawClusterItem item)
```

<mark style="color:yellow;">`item`</mark> <mark style="color:red;">*`IRawClusterItem`*</mark>  
 *Описание*  


***                

## RawClusterItem
Описание

```csharp
public RawClusterItem(long price)
```
<mark style="color:yellow;">`price`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***                

## RawClusterItem
Описание

```csharp
public RawClusterItem(long price)
public RawClusterItem(IRawClusterItem item)
```
<mark style="color:yellow;">`price`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  

<mark style="color:yellow;">`item`</mark> <mark style="color:red;">*`IRawClusterItem`*</mark>  
 *Описание*  


***                
                ***
  ***
  # Свойства

## Ask
Описание

```csharp
public long Ask { get; set; }
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
public long Bid { get; set; }
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
public long Delta { get; }
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
public long Price { get; set; }
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

