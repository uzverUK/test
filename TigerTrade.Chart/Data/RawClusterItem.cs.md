
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class RawClusterItem : IRawClusterItem
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`Add`](./RawClusterItem.cs/Методы/Add.md) | *Описание* |
| [`RawClusterItem`](./RawClusterItem.cs/Методы/RawClusterItem.md) | *Описание* |

# Таблица свойств
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





# Методы

## `Add`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Add(IRawClusterItem item)
```

<mark style="color:purple;">`item`</mark> <mark style="color:red;">*`IRawClusterItem`*</mark>  
 *Описание*  



## `RawClusterItem`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RawClusterItem(long price)
```
<mark style="color:purple;">`price`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  



## `RawClusterItem`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RawClusterItem(long price)
public RawClusterItem(IRawClusterItem item)
```
<mark style="color:purple;">`price`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  

<mark style="color:purple;">`item`</mark> <mark style="color:red;">*`IRawClusterItem`*</mark>  
 *Описание*  


# Свойства

## `Ask`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Ask { get; set; }
```

## `AskTrades`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AskTrades { get; set; }
```

## `Bid`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Bid { get; set; }
```

## `BidTrades`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int BidTrades { get; set; }
```

## `Delta`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Delta { get; }
```

## `OpenPos`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPos { get; }
```

## `OpenPosAsk`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosAsk { get; set; }
```

## `OpenPosBid`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosBid { get; set; }
```

## `Price`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Price { get; set; }
```

## `Trades`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Trades { get; }
```

## `Volume`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Volume { get; }
```

