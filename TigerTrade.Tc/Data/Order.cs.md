
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


===

### Синтаксис
```csharp
public sealed class Order
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Order`](#method-order) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Account`](#property-account) | *===* |
| [`AvgFillPrice`](#property-avgfillprice) | *===* |
| [`CancelInitiator`](#property-cancelinitiator) | *===* |
| [`Comment`](#property-comment) | *===* |
| [`Connection`](#property-connection) | *===* |
| [`DisplayQty`](#property-displayqty) | *===* |
| [`Filled`](#property-filled) | *===* |
| [`ID`](#property-id) | *===* |
| [`IsActive`](#property-isactive) | *===* |
| [`IsInactive`](#property-isinactive) | *===* |
| [`IsSplicedFuturesSymbol`](#property-issplicedfuturessymbol) | *===* |
| [`ModifyInitiator`](#property-modifyinitiator) | *===* |
| [`ModifyParams`](#property-modifyparams) | *===* |
| [`Options`](#property-options) | *===* |
| [`OrderID`](#property-orderid) | *===* |
| [`PlaceInitiator`](#property-placeinitiator) | *===* |
| [`PosClose`](#property-posclose) | *===* |
| [`Price`](#property-price) | *===* |
| [`Quantity`](#property-quantity) | *===* |
| [`QuantityReal`](#property-quantityreal) | *===* |
| [`Remaining`](#property-remaining) | *===* |
| [`RoundTrip`](#property-roundtrip) | *===* |
| [`Side`](#property-side) | *===* |
| [`State`](#property-state) | *===* |
| [`StopPrice`](#property-stopprice) | *===* |
| [`Symbol`](#property-symbol) | *===* |
| [`TakePrice`](#property-takeprice) | *===* |
| [`Time`](#property-time) | *===* |
| [`TransID`](#property-transid) | *===* |
| [`Type`](#property-type) | *===* |
| [`Validity`](#property-validity) | *===* |





***  
***  
# Методы

## `Order`<a href="method-order" id="method-order"></a>
===
```csharp
public Order(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *===*  


***  

## `Order`<a href="method-order" id="method-order"></a>
===
```csharp
public Order(Symbol symbol, Account account)
public Order(Symbol symbol, Account account, Hashtable options)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *===*  

`options` <mark style="color:red;">*`Hashtable`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Account`<a href="property-account" id="property-account"></a>
===
```csharp
public Account Account { get; }
```  
***

## `AvgFillPrice`<a href="property-avgfillprice" id="property-avgfillprice"></a>
===
```csharp
public double? AvgFillPrice { get; set; }
```  
***

## `CancelInitiator`<a href="property-cancelinitiator" id="property-cancelinitiator"></a>
===
```csharp
public string CancelInitiator { get; set; }
```  
***

## `Comment`<a href="property-comment" id="property-comment"></a>
===
```csharp
public string Comment { get; set; }
```  
***

## `Connection`<a href="property-connection" id="property-connection"></a>
===
```csharp
public ConnectionInfo Connection { get; }
```  
***

## `DisplayQty`<a href="property-displayqty" id="property-displayqty"></a>
===
```csharp
public long? DisplayQty { get; set; }
```  
***

## `Filled`<a href="property-filled" id="property-filled"></a>
===
```csharp
public long Filled { get; set; }
```  
***

## `ID`<a href="property-id" id="property-id"></a>
===
```csharp
public string ID { get; }
```  
***

## `IsActive`<a href="property-isactive" id="property-isactive"></a>
===
```csharp
public bool IsActive { get; }
```  
***

## `IsInactive`<a href="property-isinactive" id="property-isinactive"></a>
===
```csharp
public bool IsInactive { get; }
```  
***

## `IsSplicedFuturesSymbol`<a href="property-issplicedfuturessymbol" id="property-issplicedfuturessymbol"></a>
===
```csharp
public bool IsSplicedFuturesSymbol { get; private set; }
```  
***

## `ModifyInitiator`<a href="property-modifyinitiator" id="property-modifyinitiator"></a>
===
```csharp
public string ModifyInitiator { get; set; }
```  
***

## `ModifyParams`<a href="property-modifyparams" id="property-modifyparams"></a>
===
```csharp
public OrderModifyParams ModifyParams { get; set; }
```  
***

## `Options`<a href="property-options" id="property-options"></a>
===
```csharp
public Hashtable Options { get; }
```  
***

## `OrderID`<a href="property-orderid" id="property-orderid"></a>
===
```csharp
public string OrderID { get; internal set; }
```  
***

## `PlaceInitiator`<a href="property-placeinitiator" id="property-placeinitiator"></a>
===
```csharp
public string PlaceInitiator { get; set; }
```  
***

## `PosClose`<a href="property-posclose" id="property-posclose"></a>
===
```csharp
public bool PosClose { get; set; }
```  
***

## `Price`<a href="property-price" id="property-price"></a>
===
```csharp
public long Price { get; set; }
```  
***

## `Quantity`<a href="property-quantity" id="property-quantity"></a>
===
```csharp
public long Quantity { get; set; }
```  
***

## `QuantityReal`<a href="property-quantityreal" id="property-quantityreal"></a>
===
```csharp
public double QuantityReal { get; set; }
```  
***

## `Remaining`<a href="property-remaining" id="property-remaining"></a>
===
```csharp
public long Remaining { get; set; }
```  
***

## `RoundTrip`<a href="property-roundtrip" id="property-roundtrip"></a>
===
```csharp
public RoundTrip RoundTrip { get; }
```  
***

## `Side`<a href="property-side" id="property-side"></a>
===
```csharp
public Side Side { get; set; }
```  
***

## `State`<a href="property-state" id="property-state"></a>
===
```csharp
public OrderState State { get; set; }
```  
***

## `StopPrice`<a href="property-stopprice" id="property-stopprice"></a>
===
```csharp
public long StopPrice { get; set; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
===
```csharp
public Symbol Symbol { get; }
```  
***

## `TakePrice`<a href="property-takeprice" id="property-takeprice"></a>
===
```csharp
public long TakePrice { get; set; }
```  
***

## `Time`<a href="property-time" id="property-time"></a>
===
```csharp
public DateTime Time { get; set; }
```  
***

## `TransID`<a href="property-transid" id="property-transid"></a>
===
```csharp
public string TransID { get; internal set; }
```  
***

## `Type`<a href="property-type" id="property-type"></a>
===
```csharp
public OrderType Type { get; set; }
```  
***

## `Validity`<a href="property-validity" id="property-validity"></a>
===
```csharp
public OrderValidity Validity { get; set; }
```  
***

