
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class MarketDepth
```


# Список методов
| Название | Описание |
| --- | --- |
| [`MarketDepth`](#MarketDepth-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Asks`](#Asks-p) | *Описание* |
| [`AsksSize`](#AsksSize-p) | *Описание* |
| [`BestAskPrice`](#BestAskPrice-p) | *Описание* |
| [`BestAskSize`](#BestAskSize-p) | *Описание* |
| [`BestBidPrice`](#BestBidPrice-p) | *Описание* |
| [`BestBidSize`](#BestBidSize-p) | *Описание* |
| [`Bids`](#Bids-p) | *Описание* |
| [`BidsSize`](#BidsSize-p) | *Описание* |
| [`Symbol`](#Symbol-p) | *Описание* |





***  
***  
# Методы

## `MarketDepth`<a href="MarketDepth-m" id="MarketDepth-m"></a>
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

## `Asks`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<long, long> Asks { get; internal set; }
```  
***

## `AsksSize`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long AsksSize { get; internal set; }
```  
***

## `BestAskPrice`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestAskPrice { get; internal set; }
```  
***

## `BestAskSize`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestAskSize { get; internal set; }
```  
***

## `BestBidPrice`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestBidPrice { get; internal set; }
```  
***

## `BestBidSize`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestBidSize { get; internal set; }
```  
***

## `Bids`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<long, long> Bids { get; internal set; }
```  
***

## `BidsSize`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BidsSize { get; internal set; }
```  
***

## `Symbol`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; }
```  
***

