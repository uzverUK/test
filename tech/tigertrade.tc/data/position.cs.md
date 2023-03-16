# Position

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class Position
```

## Список методов

| Название                                     | Описание |
| -------------------------------------------- | -------- |
| [`Position`](position.cs.md#method-position) | _===_    |

## Список свойств

| Название                                                 | Описание |
| -------------------------------------------------------- | -------- |
| [`Account`](position.cs.md#property-account)             | _===_    |
| [`AvgPrice`](position.cs.md#property-avgprice)           | _===_    |
| [`Comission`](position.cs.md#property-comission)         | _===_    |
| [`Connection`](position.cs.md#property-connection)       | _===_    |
| [`Liquidation`](position.cs.md#property-liquidation)     | _===_    |
| [`PosNumID`](position.cs.md#property-posnumid)           | _===_    |
| [`PositionID`](position.cs.md#property-positionid)       | _===_    |
| [`Quantity`](position.cs.md#property-quantity)           | _===_    |
| [`RealizedPnl`](position.cs.md#property-realizedpnl)     | _===_    |
| [`Register`](position.cs.md#property-register)           | _===_    |
| [`SlPrice`](position.cs.md#property-slprice)             | _===_    |
| [`Symbol`](position.cs.md#property-symbol)               | _===_    |
| [`TpPrice`](position.cs.md#property-tpprice)             | _===_    |
| [`UnrealizedPnl`](position.cs.md#property-unrealizedpnl) | _===_    |

***

***

## Методы

### `Position` <a href="#method-position" id="method-position"></a>

\===

```csharp
public Position(Symbol symbol, Account account, string uniqueID)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`account` _<mark style="color:red;">`Account`</mark>_\
_===_

`uniqueID` _<mark style="color:red;">`string`</mark>_\
_===_

***

***

***

## Свойства

### `Account` <a href="#property-account" id="property-account"></a>

\===

```csharp
public Account Account { get; }
```

***

### `AvgPrice` <a href="#property-avgprice" id="property-avgprice"></a>

\===

```csharp
public double AvgPrice { get; set; }
```

***

### `Comission` <a href="#property-comission" id="property-comission"></a>

\===

```csharp
public double? Comission { get; set; }
```

***

### `Connection` <a href="#property-connection" id="property-connection"></a>

\===

```csharp
public ConnectionInfo Connection { get; }
```

***

### `Liquidation` <a href="#property-liquidation" id="property-liquidation"></a>

\===

```csharp
public double? Liquidation { get; set; }
```

***

### `PosNumID` <a href="#property-posnumid" id="property-posnumid"></a>

\===

```csharp
public long PosNumID { get; set; }
```

***

### `PositionID` <a href="#property-positionid" id="property-positionid"></a>

\===

```csharp
public string PositionID { get; }
```

***

### `Quantity` <a href="#property-quantity" id="property-quantity"></a>

\===

```csharp
public long Quantity { get; set; }
```

***

### `RealizedPnl` <a href="#property-realizedpnl" id="property-realizedpnl"></a>

\===

```csharp
public double? RealizedPnl { get; set; }
```

***

### `Register` <a href="#property-register" id="property-register"></a>

\===

```csharp
public string Register { get; set; }
```

***

### `SlPrice` <a href="#property-slprice" id="property-slprice"></a>

\===

```csharp
public double? SlPrice { get; set; }
```

***

### `Symbol` <a href="#property-symbol" id="property-symbol"></a>

\===

```csharp
public Symbol Symbol { get; }
```

***

### `TpPrice` <a href="#property-tpprice" id="property-tpprice"></a>

\===

```csharp
public double? TpPrice { get; set; }
```

***

### `UnrealizedPnl` <a href="#property-unrealizedpnl" id="property-unrealizedpnl"></a>

\===

```csharp
public double? UnrealizedPnl { get; set; }
```

***
