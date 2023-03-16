
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class MarketDepth
```


# Список методов
| Название | Описание |
| --- | --- |
| [`MarketDepth`](./MarketDepth.cs/Методы/MarketDepth.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Asks`](./MarketDepth.cs/Свойства/Asks.md) | *Описание* |
| [`AsksSize`](./MarketDepth.cs/Свойства/AsksSize.md) | *Описание* |
| [`BestAskPrice`](./MarketDepth.cs/Свойства/BestAskPrice.md) | *Описание* |
| [`BestAskSize`](./MarketDepth.cs/Свойства/BestAskSize.md) | *Описание* |
| [`BestBidPrice`](./MarketDepth.cs/Свойства/BestBidPrice.md) | *Описание* |
| [`BestBidSize`](./MarketDepth.cs/Свойства/BestBidSize.md) | *Описание* |
| [`Bids`](./MarketDepth.cs/Свойства/Bids.md) | *Описание* |
| [`BidsSize`](./MarketDepth.cs/Свойства/BidsSize.md) | *Описание* |
| [`Symbol`](./MarketDepth.cs/Свойства/Symbol.md) | *Описание* |





***  
***  
# Методы

## `MarketDepth`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public MarketDepth(Symbol symbol)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Asks`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<long, long> Asks { get; internal set; }
```  
***

## `AsksSize`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long AsksSize { get; internal set; }
```  
***

## `BestAskPrice`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestAskPrice { get; internal set; }
```  
***

## `BestAskSize`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestAskSize { get; internal set; }
```  
***

## `BestBidPrice`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestBidPrice { get; internal set; }
```  
***

## `BestBidSize`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestBidSize { get; internal set; }
```  
***

## `Bids`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<long, long> Bids { get; internal set; }
```  
***

## `BidsSize`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BidsSize { get; internal set; }
```  
***

## `Symbol`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; }
```  
***

