# Security

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class Security
```

## Список методов

| Название                                     | Описание |
| -------------------------------------------- | -------- |
| [`Security`](security.cs.md#method-security) | _===_    |

## Список свойств

| Название                                                           | Описание |
| ------------------------------------------------------------------ | -------- |
| [`AskPrice`](security.cs.md#property-askprice)                     | _===_    |
| [`AskSize`](security.cs.md#property-asksize)                       | _===_    |
| [`AskTime`](security.cs.md#property-asktime)                       | _===_    |
| [`BidDepthT`](security.cs.md#property-biddeptht)                   | _===_    |
| [`BidPrice`](security.cs.md#property-bidprice)                     | _===_    |
| [`BidSize`](security.cs.md#property-bidsize)                       | _===_    |
| [`BidTime`](security.cs.md#property-bidtime)                       | _===_    |
| [`Change`](security.cs.md#property-change)                         | _===_    |
| [`ClosePrice`](security.cs.md#property-closeprice)                 | _===_    |
| [`HighPrice`](security.cs.md#property-highprice)                   | _===_    |
| [`LastConditions`](security.cs.md#property-lastconditions)         | _===_    |
| [`LastIsNotQualified`](security.cs.md#property-lastisnotqualified) | _===_    |
| [`LastMarket`](security.cs.md#property-lastmarket)                 | _===_    |
| [`LastMarketCenter`](security.cs.md#property-lastmarketcenter)     | _===_    |
| [`LastPrice`](security.cs.md#property-lastprice)                   | _===_    |
| [`LastSide`](security.cs.md#property-lastside)                     | _===_    |
| [`LastSize`](security.cs.md#property-lastsize)                     | _===_    |
| [`LastTime`](security.cs.md#property-lasttime)                     | _===_    |
| [`LowPrice`](security.cs.md#property-lowprice)                     | _===_    |
| [`MarginBuy`](security.cs.md#property-marginbuy)                   | _===_    |
| [`MarginSell`](security.cs.md#property-marginsell)                 | _===_    |
| [`NetChange`](security.cs.md#property-netchange)                   | _===_    |
| [`NumBids`](security.cs.md#property-numbids)                       | _===_    |
| [`NumOffers`](security.cs.md#property-numoffers)                   | _===_    |
| [`OfferDepthT`](security.cs.md#property-offerdeptht)               | _===_    |
| [`OpenInt`](security.cs.md#property-openint)                       | _===_    |
| [`OpenPrice`](security.cs.md#property-openprice)                   | _===_    |
| [`PriceMax`](security.cs.md#property-pricemax)                     | _===_    |
| [`PriceMin`](security.cs.md#property-pricemin)                     | _===_    |
| [`SecurityID`](security.cs.md#property-securityid)                 | _===_    |
| [`Symbol`](security.cs.md#property-symbol)                         | _===_    |
| [`TheoreticalPrice`](security.cs.md#property-theoreticalprice)     | _===_    |
| [`Trades`](security.cs.md#property-trades)                         | _===_    |
| [`Value`](security.cs.md#property-value)                           | _===_    |
| [`Volatility`](security.cs.md#property-volatility)                 | _===_    |
| [`Volume`](security.cs.md#property-volume)                         | _===_    |

***

***

## Методы

### `Security` <a href="#method-security" id="method-security"></a>

\===

```csharp
public Security(Symbol symbol)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

***

***

***

## Свойства

### `AskPrice` <a href="#property-askprice" id="property-askprice"></a>

\===

```csharp
public long AskPrice { get; set; }
```

***

### `AskSize` <a href="#property-asksize" id="property-asksize"></a>

\===

```csharp
public long AskSize { get; set; }
```

***

### `AskTime` <a href="#property-asktime" id="property-asktime"></a>

\===

```csharp
public DateTime AskTime { get; set; }
```

***

### `BidDepthT` <a href="#property-biddeptht" id="property-biddeptht"></a>

\===

```csharp
public long BidDepthT { get; set; }
```

***

### `BidPrice` <a href="#property-bidprice" id="property-bidprice"></a>

\===

```csharp
public long BidPrice { get; set; }
```

***

### `BidSize` <a href="#property-bidsize" id="property-bidsize"></a>

\===

```csharp
public long BidSize { get; set; }
```

***

### `BidTime` <a href="#property-bidtime" id="property-bidtime"></a>

\===

```csharp
public DateTime BidTime { get; set; }
```

***

### `Change` <a href="#property-change" id="property-change"></a>

\===

```csharp
public double? Change { get; set; }
```

***

### `ClosePrice` <a href="#property-closeprice" id="property-closeprice"></a>

\===

```csharp
public double ClosePrice { get; set; }
```

***

### `HighPrice` <a href="#property-highprice" id="property-highprice"></a>

\===

```csharp
public double HighPrice { get; set; }
```

***

### `LastConditions` <a href="#property-lastconditions" id="property-lastconditions"></a>

\===

```csharp
public string LastConditions { get; set; }
```

***

### `LastIsNotQualified` <a href="#property-lastisnotqualified" id="property-lastisnotqualified"></a>

\===

```csharp
public bool LastIsNotQualified { get; set; }
```

***

### `LastMarket` <a href="#property-lastmarket" id="property-lastmarket"></a>

\===

```csharp
public string LastMarket { get; set; }
```

***

### `LastMarketCenter` <a href="#property-lastmarketcenter" id="property-lastmarketcenter"></a>

\===

```csharp
public long LastMarketCenter { get; set; }
```

***

### `LastPrice` <a href="#property-lastprice" id="property-lastprice"></a>

\===

```csharp
public long LastPrice { get; set; }
```

***

### `LastSide` <a href="#property-lastside" id="property-lastside"></a>

\===

```csharp
public Side LastSide { get; set; }
```

***

### `LastSize` <a href="#property-lastsize" id="property-lastsize"></a>

\===

```csharp
public long LastSize { get; set; }
```

***

### `LastTime` <a href="#property-lasttime" id="property-lasttime"></a>

\===

```csharp
public DateTime LastTime { get; set; }
```

***

### `LowPrice` <a href="#property-lowprice" id="property-lowprice"></a>

\===

```csharp
public double LowPrice { get; set; }
```

***

### `MarginBuy` <a href="#property-marginbuy" id="property-marginbuy"></a>

\===

```csharp
public double MarginBuy { get; set; }
```

***

### `MarginSell` <a href="#property-marginsell" id="property-marginsell"></a>

\===

```csharp
public double MarginSell { get; set; }
```

***

### `NetChange` <a href="#property-netchange" id="property-netchange"></a>

\===

```csharp
public double? NetChange { get; set; }
```

***

### `NumBids` <a href="#property-numbids" id="property-numbids"></a>

\===

```csharp
public long NumBids { get; set; }
```

***

### `NumOffers` <a href="#property-numoffers" id="property-numoffers"></a>

\===

```csharp
public long NumOffers { get; set; }
```

***

### `OfferDepthT` <a href="#property-offerdeptht" id="property-offerdeptht"></a>

\===

```csharp
public long OfferDepthT { get; set; }
```

***

### `OpenInt` <a href="#property-openint" id="property-openint"></a>

\===

```csharp
public long OpenInt { get; set; }
```

***

### `OpenPrice` <a href="#property-openprice" id="property-openprice"></a>

\===

```csharp
public double OpenPrice { get; set; }
```

***

### `PriceMax` <a href="#property-pricemax" id="property-pricemax"></a>

\===

```csharp
public double PriceMax { get; set; }
```

***

### `PriceMin` <a href="#property-pricemin" id="property-pricemin"></a>

\===

```csharp
public double PriceMin { get; set; }
```

***

### `SecurityID` <a href="#property-securityid" id="property-securityid"></a>

\===

```csharp
public string SecurityID { get; }
```

***

### `Symbol` <a href="#property-symbol" id="property-symbol"></a>

\===

```csharp
public Symbol Symbol { get; }
```

***

### `TheoreticalPrice` <a href="#property-theoreticalprice" id="property-theoreticalprice"></a>

\===

```csharp
public double TheoreticalPrice { get; set; }
```

***

### `Trades` <a href="#property-trades" id="property-trades"></a>

\===

```csharp
public long Trades { get; set; }
```

***

### `Value` <a href="#property-value" id="property-value"></a>

\===

```csharp
public long Value { get; set; }
```

***

### `Volatility` <a href="#property-volatility" id="property-volatility"></a>

\===

```csharp
public double Volatility { get; set; }
```

***

### `Volume` <a href="#property-volume" id="property-volume"></a>

\===

```csharp
public long Volume { get; set; }
```

***
