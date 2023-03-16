
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class MarketDepth
```


# Список методов
| Название | Описание |
| --- | --- |
| [`MarketDepth`](#method-marketdepth) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Asks`](#property-asks) | *Описание* |
| [`AsksSize`](#property-askssize) | *Описание* |
| [`BestAskPrice`](#property-bestaskprice) | *Описание* |
| [`BestAskSize`](#property-bestasksize) | *Описание* |
| [`BestBidPrice`](#property-bestbidprice) | *Описание* |
| [`BestBidSize`](#property-bestbidsize) | *Описание* |
| [`Bids`](#property-bids) | *Описание* |
| [`BidsSize`](#property-bidssize) | *Описание* |
| [`Symbol`](#property-symbol) | *Описание* |





***  
***  
# Методы

## `MarketDepth`<a href="method-marketdepth" id="method-marketdepth"></a>
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

## `Asks`<a href="property-asks" id="property-asks"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<long, long> Asks { get; internal set; }
```  
***

## `AsksSize`<a href="property-askssize" id="property-askssize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long AsksSize { get; internal set; }
```  
***

## `BestAskPrice`<a href="property-bestaskprice" id="property-bestaskprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestAskPrice { get; internal set; }
```  
***

## `BestAskSize`<a href="property-bestasksize" id="property-bestasksize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestAskSize { get; internal set; }
```  
***

## `BestBidPrice`<a href="property-bestbidprice" id="property-bestbidprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestBidPrice { get; internal set; }
```  
***

## `BestBidSize`<a href="property-bestbidsize" id="property-bestbidsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BestBidSize { get; internal set; }
```  
***

## `Bids`<a href="property-bids" id="property-bids"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<long, long> Bids { get; internal set; }
```  
***

## `BidsSize`<a href="property-bidssize" id="property-bidssize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long BidsSize { get; internal set; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; }
```  
***

