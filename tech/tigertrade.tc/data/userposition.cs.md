# UserPosition

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class UserPosition
```

## Список методов

| Название                                                   | Описание |
| ---------------------------------------------------------- | -------- |
| [`GetMoneyPnl`](userposition.cs.md#method-getmoneypnl)     | _===_    |
| [`GetPercentPnl`](userposition.cs.md#method-getpercentpnl) | _===_    |
| [`GetPointsPnl`](userposition.cs.md#method-getpointspnl)   | _===_    |
| [`InitStrategy`](userposition.cs.md#method-initstrategy)   | _===_    |
| [`UserPosition`](userposition.cs.md#method-userposition)   | _===_    |

## Список свойств

| Название                                                       | Описание |
| -------------------------------------------------------------- | -------- |
| [`AccountID`](userposition.cs.md#property-accountid)           | _===_    |
| [`AccountName`](userposition.cs.md#property-accountname)       | _===_    |
| [`Ask`](userposition.cs.md#property-ask)                       | _===_    |
| [`Bid`](userposition.cs.md#property-bid)                       | _===_    |
| [`Comission`](userposition.cs.md#property-comission)           | _===_    |
| [`ConnectionID`](userposition.cs.md#property-connectionid)     | _===_    |
| [`ConnectionName`](userposition.cs.md#property-connectionname) | _===_    |
| [`Hidden`](userposition.cs.md#property-hidden)                 | _===_    |
| [`IsMt5TimeValid`](userposition.cs.md#property-ismt5timevalid) | _===_    |
| [`LastPrice`](userposition.cs.md#property-lastprice)           | _===_    |
| [`LastTradeIDs`](userposition.cs.md#property-lasttradeids)     | _===_    |
| [`LastTradeTime`](userposition.cs.md#property-lasttradetime)   | _===_    |
| [`MaxQuantity`](userposition.cs.md#property-maxquantity)       | _===_    |
| [`OpenPrice`](userposition.cs.md#property-openprice)           | _===_    |
| [`OpenTime`](userposition.cs.md#property-opentime)             | _===_    |
| [`PositionID`](userposition.cs.md#property-positionid)         | _===_    |
| [`PositionPnl`](userposition.cs.md#property-positionpnl)       | _===_    |
| [`PositionTime`](userposition.cs.md#property-positiontime)     | _===_    |
| [`Price`](userposition.cs.md#property-price)                   | _===_    |
| [`PriceSum`](userposition.cs.md#property-pricesum)             | _===_    |
| [`PriceSumLong`](userposition.cs.md#property-pricesumlong)     | _===_    |
| [`Size`](userposition.cs.md#property-size)                     | _===_    |
| [`SizeStep`](userposition.cs.md#property-sizestep)             | _===_    |
| [`StartTime`](userposition.cs.md#property-starttime)           | _===_    |
| [`Strategy`](userposition.cs.md#property-strategy)             | _===_    |
| [`Symbol`](userposition.cs.md#property-symbol)                 | _===_    |
| [`SymbolID`](userposition.cs.md#property-symbolid)             | _===_    |
| [`SymbolName`](userposition.cs.md#property-symbolname)         | _===_    |
| [`TotalQuantity`](userposition.cs.md#property-totalquantity)   | _===_    |
| [`TotalValue`](userposition.cs.md#property-totalvalue)         | _===_    |
| [`TotalValueLong`](userposition.cs.md#property-totalvaluelong) | _===_    |

***

***

## Методы

### `GetMoneyPnl` <a href="#method-getmoneypnl" id="method-getmoneypnl"></a>

\===

```csharp
public double GetMoneyPnl()
```

***

### `GetMoneyPnl` <a href="#method-getmoneypnl" id="method-getmoneypnl"></a>

\===

```csharp
public double GetMoneyPnl()
public double GetMoneyPnl(long exitPrice)
```

`exitPrice` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `GetMoneyPnl` <a href="#method-getmoneypnl" id="method-getmoneypnl"></a>

\===

```csharp
public double GetMoneyPnl()
public double GetMoneyPnl(long exitPrice)
public double GetMoneyPnl(long entryPrice, long exitPrice, long size)
```

`exitPrice` _<mark style="color:red;">`long`</mark>_\
_===_

`entryPrice` _<mark style="color:red;">`long`</mark>_\
_===_

`size` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `GetPercentPnl` <a href="#method-getpercentpnl" id="method-getpercentpnl"></a>

\===

```csharp
public double GetPercentPnl()
```

***

### `GetPercentPnl` <a href="#method-getpercentpnl" id="method-getpercentpnl"></a>

\===

```csharp
public double GetPercentPnl()
public double GetPercentPnl(long exitPrice)
```

`exitPrice` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `GetPointsPnl` <a href="#method-getpointspnl" id="method-getpointspnl"></a>

\===

```csharp
public double GetPointsPnl()
```

***

### `GetPointsPnl` <a href="#method-getpointspnl" id="method-getpointspnl"></a>

\===

```csharp
public double GetPointsPnl()
public double GetPointsPnl(long exitPrice)
```

`exitPrice` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `InitStrategy` <a href="#method-initstrategy" id="method-initstrategy"></a>

\===

```csharp
public void InitStrategy(ExitStrategy strategy)
```

`strategy` _<mark style="color:red;">`ExitStrategy`</mark>_\
_===_

***

### `UserPosition` <a href="#method-userposition" id="method-userposition"></a>

\===

```csharp
public UserPosition()
```

***

### `UserPosition` <a href="#method-userposition" id="method-userposition"></a>

\===

```csharp
public UserPosition()
public UserPosition(ConnectionInfo info, Symbol symbol, Account account)
```

`info` _<mark style="color:red;">`ConnectionInfo`</mark>_\
_===_

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`account` _<mark style="color:red;">`Account`</mark>_\
_===_

***

***

***

## Свойства

### `AccountID` <a href="#property-accountid" id="property-accountid"></a>

\===

```csharp
public string AccountID { get; set; }
```

***

### `AccountName` <a href="#property-accountname" id="property-accountname"></a>

\===

```csharp
public string AccountName { get; set; }
```

***

### `Ask` <a href="#property-ask" id="property-ask"></a>

\===

```csharp
public long Ask { get; private set; }
```

***

### `Bid` <a href="#property-bid" id="property-bid"></a>

\===

```csharp
public long Bid { get; private set; }
```

***

### `Comission` <a href="#property-comission" id="property-comission"></a>

\===

```csharp
public double Comission { get; set; }
```

***

### `ConnectionID` <a href="#property-connectionid" id="property-connectionid"></a>

\===

```csharp
public string ConnectionID { get; set; }
```

***

### `ConnectionName` <a href="#property-connectionname" id="property-connectionname"></a>

\===

```csharp
public string ConnectionName { get; set; }
```

***

### `Hidden` <a href="#property-hidden" id="property-hidden"></a>

\===

```csharp
public bool Hidden { get; set; }
```

***

### `IsMt5TimeValid` <a href="#property-ismt5timevalid" id="property-ismt5timevalid"></a>

\===

```csharp
public bool IsMt5TimeValid { get; set; }
```

***

### `LastPrice` <a href="#property-lastprice" id="property-lastprice"></a>

\===

```csharp
public long LastPrice { get; private set; }
```

***

### `LastTradeIDs` <a href="#property-lasttradeids" id="property-lasttradeids"></a>

\===

```csharp
public HashSet<string> LastTradeIDs { get; set; }
```

***

### `LastTradeTime` <a href="#property-lasttradetime" id="property-lasttradetime"></a>

\===

```csharp
public DateTime LastTradeTime { get; set; }
```

***

### `MaxQuantity` <a href="#property-maxquantity" id="property-maxquantity"></a>

\===

```csharp
public long MaxQuantity { get; set; }
```

***

### `OpenPrice` <a href="#property-openprice" id="property-openprice"></a>

\===

```csharp
public long OpenPrice { get; set; }
```

***

### `OpenTime` <a href="#property-opentime" id="property-opentime"></a>

\===

```csharp
public DateTime OpenTime { get; set; }
```

***

### `PositionID` <a href="#property-positionid" id="property-positionid"></a>

\===

```csharp
public string PositionID { get; }
```

***

### `PositionPnl` <a href="#property-positionpnl" id="property-positionpnl"></a>

\===

```csharp
public long PositionPnl { get; private set; }
```

***

### `PositionTime` <a href="#property-positiontime" id="property-positiontime"></a>

\===

```csharp
public TimeSpan PositionTime { get; private set; }
```

***

### `Price` <a href="#property-price" id="property-price"></a>

\===

```csharp
public long Price { get; set; }
```

***

### `PriceSum` <a href="#property-pricesum" id="property-pricesum"></a>

\===

```csharp
public BigInteger PriceSum { get; set; }
```

***

### `PriceSumLong` <a href="#property-pricesumlong" id="property-pricesumlong"></a>

\===

```csharp
public long PriceSumLong { get; set; }
```

***

### `Size` <a href="#property-size" id="property-size"></a>

\===

```csharp
public long Size { get; set; }
```

***

### `SizeStep` <a href="#property-sizestep" id="property-sizestep"></a>

\===

```csharp
public double? SizeStep { get; set; }
```

***

### `StartTime` <a href="#property-starttime" id="property-starttime"></a>

\===

```csharp
public DateTime StartTime { get; set; }
```

***

### `Strategy` <a href="#property-strategy" id="property-strategy"></a>

\===

```csharp
public ExitStrategy Strategy { get; set; }
```

***

### `Symbol` <a href="#property-symbol" id="property-symbol"></a>

\===

```csharp
public Symbol Symbol { get; internal set; }
```

***

### `SymbolID` <a href="#property-symbolid" id="property-symbolid"></a>

\===

```csharp
public string SymbolID { get; set; }
```

***

### `SymbolName` <a href="#property-symbolname" id="property-symbolname"></a>

\===

```csharp
public string SymbolName { get; set; }
```

***

### `TotalQuantity` <a href="#property-totalquantity" id="property-totalquantity"></a>

\===

```csharp
public long TotalQuantity { get; set; }
```

***

### `TotalValue` <a href="#property-totalvalue" id="property-totalvalue"></a>

\===

```csharp
public BigInteger TotalValue { get; set; }
```

***

### `TotalValueLong` <a href="#property-totalvaluelong" id="property-totalvaluelong"></a>

\===

```csharp
public long TotalValueLong { get; set; }
```

***
