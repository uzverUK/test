# Order

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class Order
```

## Список методов

| Название                            | Описание |
| ----------------------------------- | -------- |
| [`Order`](order.cs.md#method-order) | _===_    |

## Список свойств

| Название                                                                | Описание |
| ----------------------------------------------------------------------- | -------- |
| [`Account`](order.cs.md#property-account)                               | _===_    |
| [`AvgFillPrice`](order.cs.md#property-avgfillprice)                     | _===_    |
| [`CancelInitiator`](order.cs.md#property-cancelinitiator)               | _===_    |
| [`Comment`](order.cs.md#property-comment)                               | _===_    |
| [`Connection`](order.cs.md#property-connection)                         | _===_    |
| [`DisplayQty`](order.cs.md#property-displayqty)                         | _===_    |
| [`Filled`](order.cs.md#property-filled)                                 | _===_    |
| [`ID`](order.cs.md#property-id)                                         | _===_    |
| [`IsActive`](order.cs.md#property-isactive)                             | _===_    |
| [`IsInactive`](order.cs.md#property-isinactive)                         | _===_    |
| [`IsSplicedFuturesSymbol`](order.cs.md#property-issplicedfuturessymbol) | _===_    |
| [`ModifyInitiator`](order.cs.md#property-modifyinitiator)               | _===_    |
| [`ModifyParams`](order.cs.md#property-modifyparams)                     | _===_    |
| [`Options`](order.cs.md#property-options)                               | _===_    |
| [`OrderID`](order.cs.md#property-orderid)                               | _===_    |
| [`PlaceInitiator`](order.cs.md#property-placeinitiator)                 | _===_    |
| [`PosClose`](order.cs.md#property-posclose)                             | _===_    |
| [`Price`](order.cs.md#property-price)                                   | _===_    |
| [`Quantity`](order.cs.md#property-quantity)                             | _===_    |
| [`QuantityReal`](order.cs.md#property-quantityreal)                     | _===_    |
| [`Remaining`](order.cs.md#property-remaining)                           | _===_    |
| [`RoundTrip`](order.cs.md#property-roundtrip)                           | _===_    |
| [`Side`](order.cs.md#property-side)                                     | _===_    |
| [`State`](order.cs.md#property-state)                                   | _===_    |
| [`StopPrice`](order.cs.md#property-stopprice)                           | _===_    |
| [`Symbol`](order.cs.md#property-symbol)                                 | _===_    |
| [`TakePrice`](order.cs.md#property-takeprice)                           | _===_    |
| [`Time`](order.cs.md#property-time)                                     | _===_    |
| [`TransID`](order.cs.md#property-transid)                               | _===_    |
| [`Type`](order.cs.md#property-type)                                     | _===_    |
| [`Validity`](order.cs.md#property-validity)                             | _===_    |

***

***

## Методы

### `Order` <a href="#method-order" id="method-order"></a>

\===

```csharp
public Order(Symbol symbol, Account account)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`account` _<mark style="color:red;">`Account`</mark>_\
_===_

***

### `Order` <a href="#method-order" id="method-order"></a>

\===

```csharp
public Order(Symbol symbol, Account account)
public Order(Symbol symbol, Account account, Hashtable options)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`account` _<mark style="color:red;">`Account`</mark>_\
_===_

`options` _<mark style="color:red;">`Hashtable`</mark>_\
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

### `AvgFillPrice` <a href="#property-avgfillprice" id="property-avgfillprice"></a>

\===

```csharp
public double? AvgFillPrice { get; set; }
```

***

### `CancelInitiator` <a href="#property-cancelinitiator" id="property-cancelinitiator"></a>

\===

```csharp
public string CancelInitiator { get; set; }
```

***

### `Comment` <a href="#property-comment" id="property-comment"></a>

\===

```csharp
public string Comment { get; set; }
```

***

### `Connection` <a href="#property-connection" id="property-connection"></a>

\===

```csharp
public ConnectionInfo Connection { get; }
```

***

### `DisplayQty` <a href="#property-displayqty" id="property-displayqty"></a>

\===

```csharp
public long? DisplayQty { get; set; }
```

***

### `Filled` <a href="#property-filled" id="property-filled"></a>

\===

```csharp
public long Filled { get; set; }
```

***

### `ID` <a href="#property-id" id="property-id"></a>

\===

```csharp
public string ID { get; }
```

***

### `IsActive` <a href="#property-isactive" id="property-isactive"></a>

\===

```csharp
public bool IsActive { get; }
```

***

### `IsInactive` <a href="#property-isinactive" id="property-isinactive"></a>

\===

```csharp
public bool IsInactive { get; }
```

***

### `IsSplicedFuturesSymbol` <a href="#property-issplicedfuturessymbol" id="property-issplicedfuturessymbol"></a>

\===

```csharp
public bool IsSplicedFuturesSymbol { get; private set; }
```

***

### `ModifyInitiator` <a href="#property-modifyinitiator" id="property-modifyinitiator"></a>

\===

```csharp
public string ModifyInitiator { get; set; }
```

***

### `ModifyParams` <a href="#property-modifyparams" id="property-modifyparams"></a>

\===

```csharp
public OrderModifyParams ModifyParams { get; set; }
```

***

### `Options` <a href="#property-options" id="property-options"></a>

\===

```csharp
public Hashtable Options { get; }
```

***

### `OrderID` <a href="#property-orderid" id="property-orderid"></a>

\===

```csharp
public string OrderID { get; internal set; }
```

***

### `PlaceInitiator` <a href="#property-placeinitiator" id="property-placeinitiator"></a>

\===

```csharp
public string PlaceInitiator { get; set; }
```

***

### `PosClose` <a href="#property-posclose" id="property-posclose"></a>

\===

```csharp
public bool PosClose { get; set; }
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

### `QuantityReal` <a href="#property-quantityreal" id="property-quantityreal"></a>

\===

```csharp
public double QuantityReal { get; set; }
```

***

### `Remaining` <a href="#property-remaining" id="property-remaining"></a>

\===

```csharp
public long Remaining { get; set; }
```

***

### `RoundTrip` <a href="#property-roundtrip" id="property-roundtrip"></a>

\===

```csharp
public RoundTrip RoundTrip { get; }
```

***

### `Side` <a href="#property-side" id="property-side"></a>

\===

```csharp
public Side Side { get; set; }
```

***

### `State` <a href="#property-state" id="property-state"></a>

\===

```csharp
public OrderState State { get; set; }
```

***

### `StopPrice` <a href="#property-stopprice" id="property-stopprice"></a>

\===

```csharp
public long StopPrice { get; set; }
```

***

### `Symbol` <a href="#property-symbol" id="property-symbol"></a>

\===

```csharp
public Symbol Symbol { get; }
```

***

### `TakePrice` <a href="#property-takeprice" id="property-takeprice"></a>

\===

```csharp
public long TakePrice { get; set; }
```

***

### `Time` <a href="#property-time" id="property-time"></a>

\===

```csharp
public DateTime Time { get; set; }
```

***

### `TransID` <a href="#property-transid" id="property-transid"></a>

\===

```csharp
public string TransID { get; internal set; }
```

***

### `Type` <a href="#property-type" id="property-type"></a>

\===

```csharp
public OrderType Type { get; set; }
```

***

### `Validity` <a href="#property-validity" id="property-validity"></a>

\===

```csharp
public OrderValidity Validity { get; set; }
```

***
