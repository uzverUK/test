# Execution

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class Execution
```

## Список методов

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`Execution`](execution.cs.md#method-execution) | _===_    |

## Список свойств

| Название                                              | Описание |
| ----------------------------------------------------- | -------- |
| [`Account`](execution.cs.md#property-account)         | _===_    |
| [`Comission`](execution.cs.md#property-comission)     | _===_    |
| [`Connection`](execution.cs.md#property-connection)   | _===_    |
| [`Currency`](execution.cs.md#property-currency)       | _===_    |
| [`ExecutionID`](execution.cs.md#property-executionid) | _===_    |
| [`ID`](execution.cs.md#property-id)                   | _===_    |
| [`OrderID`](execution.cs.md#property-orderid)         | _===_    |
| [`Price`](execution.cs.md#property-price)             | _===_    |
| [`Quantity`](execution.cs.md#property-quantity)       | _===_    |
| [`RealizedPnl`](execution.cs.md#property-realizedpnl) | _===_    |
| [`Side`](execution.cs.md#property-side)               | _===_    |
| [`Symbol`](execution.cs.md#property-symbol)           | _===_    |
| [`Time`](execution.cs.md#property-time)               | _===_    |

***

***

## Методы

### `Execution` <a href="#method-execution" id="method-execution"></a>

\===

```csharp
public Execution(Symbol symbol, Account account)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`account` _<mark style="color:red;">`Account`</mark>_\
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

### `Currency` <a href="#property-currency" id="property-currency"></a>

\===

```csharp
public string Currency { get; set; }
```

***

### `ExecutionID` <a href="#property-executionid" id="property-executionid"></a>

\===

```csharp
public string ExecutionID { get; set; }
```

***

### `ID` <a href="#property-id" id="property-id"></a>

\===

```csharp
public string ID { get; }
```

***

### `OrderID` <a href="#property-orderid" id="property-orderid"></a>

\===

```csharp
public string OrderID { get; set; }
```

***

### `Price` <a href="#property-price" id="property-price"></a>

\===

```csharp
public long Price { get; set; }
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

### `Side` <a href="#property-side" id="property-side"></a>

\===

```csharp
public Side Side { get; set; }
```

***

### `Symbol` <a href="#property-symbol" id="property-symbol"></a>

\===

```csharp
public Symbol Symbol { get; }
```

***

### `Time` <a href="#property-time" id="property-time"></a>

\===

```csharp
public DateTime Time { get; set; }
```

***
