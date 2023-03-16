# Portfolio

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class Portfolio
```

## Список методов

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`Portfolio`](portfolio.cs.md#method-portfolio) | _===_    |
| [`ToString`](portfolio.cs.md#method-tostring)   | _===_    |

## Список свойств

| Название                                                  | Описание |
| --------------------------------------------------------- | -------- |
| [`Balance`](portfolio.cs.md#property-balance)             | _===_    |
| [`Comission`](portfolio.cs.md#property-comission)         | _===_    |
| [`Connection`](portfolio.cs.md#property-connection)       | _===_    |
| [`ConnectionID`](portfolio.cs.md#property-connectionid)   | _===_    |
| [`Currency`](portfolio.cs.md#property-currency)           | _===_    |
| [`FreeMargin`](portfolio.cs.md#property-freemargin)       | _===_    |
| [`Leverage`](portfolio.cs.md#property-leverage)           | _===_    |
| [`Name`](portfolio.cs.md#property-name)                   | _===_    |
| [`PortfolioID`](portfolio.cs.md#property-portfolioid)     | _===_    |
| [`Precision`](portfolio.cs.md#property-precision)         | _===_    |
| [`RealizedPnl`](portfolio.cs.md#property-realizedpnl)     | _===_    |
| [`Register`](portfolio.cs.md#property-register)           | _===_    |
| [`UnrealizedPnl`](portfolio.cs.md#property-unrealizedpnl) | _===_    |
| [`UsedMargin`](portfolio.cs.md#property-usedmargin)       | _===_    |

***

***

## Методы

### `Portfolio` <a href="#method-portfolio" id="method-portfolio"></a>

\===

```csharp
public Portfolio(ConnectionInfo connection, string uniqueID)
```

`connection` _<mark style="color:red;">`ConnectionInfo`</mark>_\
_===_

`uniqueID` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

***

***

***

## Свойства

### `Balance` <a href="#property-balance" id="property-balance"></a>

\===

```csharp
public double Balance { get; set; }
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

### `ConnectionID` <a href="#property-connectionid" id="property-connectionid"></a>

\===

```csharp
public string ConnectionID { get; }
```

***

### `Currency` <a href="#property-currency" id="property-currency"></a>

\===

```csharp
public string Currency { get; set; }
```

***

### `FreeMargin` <a href="#property-freemargin" id="property-freemargin"></a>

\===

```csharp
public double FreeMargin { get; set; }
```

***

### `Leverage` <a href="#property-leverage" id="property-leverage"></a>

\===

```csharp
public int? Leverage { get; set; }
```

***

### `Name` <a href="#property-name" id="property-name"></a>

\===

```csharp
public string Name { get; set; }
```

***

### `PortfolioID` <a href="#property-portfolioid" id="property-portfolioid"></a>

\===

```csharp
public string PortfolioID { get; set; }
```

***

### `Precision` <a href="#property-precision" id="property-precision"></a>

\===

```csharp
public int Precision { get; set; }
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

### `UnrealizedPnl` <a href="#property-unrealizedpnl" id="property-unrealizedpnl"></a>

\===

```csharp
public double? UnrealizedPnl { get; set; }
```

***

### `UsedMargin` <a href="#property-usedmargin" id="property-usedmargin"></a>

\===

```csharp
public double UsedMargin { get; set; }
```

***
