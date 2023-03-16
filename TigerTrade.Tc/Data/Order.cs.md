
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Order
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Order`](#method-order) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Account`](#property-account) | *Описание* |
| [`AvgFillPrice`](#property-avgfillprice) | *Описание* |
| [`CancelInitiator`](#property-cancelinitiator) | *Описание* |
| [`Comment`](#property-comment) | *Описание* |
| [`Connection`](#property-connection) | *Описание* |
| [`DisplayQty`](#property-displayqty) | *Описание* |
| [`Filled`](#property-filled) | *Описание* |
| [`ID`](#property-id) | *Описание* |
| [`IsActive`](#property-isactive) | *Описание* |
| [`IsInactive`](#property-isinactive) | *Описание* |
| [`IsSplicedFuturesSymbol`](#property-issplicedfuturessymbol) | *Описание* |
| [`ModifyInitiator`](#property-modifyinitiator) | *Описание* |
| [`ModifyParams`](#property-modifyparams) | *Описание* |
| [`Options`](#property-options) | *Описание* |
| [`OrderID`](#property-orderid) | *Описание* |
| [`PlaceInitiator`](#property-placeinitiator) | *Описание* |
| [`PosClose`](#property-posclose) | *Описание* |
| [`Price`](#property-price) | *Описание* |
| [`Quantity`](#property-quantity) | *Описание* |
| [`QuantityReal`](#property-quantityreal) | *Описание* |
| [`Remaining`](#property-remaining) | *Описание* |
| [`RoundTrip`](#property-roundtrip) | *Описание* |
| [`Side`](#property-side) | *Описание* |
| [`State`](#property-state) | *Описание* |
| [`StopPrice`](#property-stopprice) | *Описание* |
| [`Symbol`](#property-symbol) | *Описание* |
| [`TakePrice`](#property-takeprice) | *Описание* |
| [`Time`](#property-time) | *Описание* |
| [`TransID`](#property-transid) | *Описание* |
| [`Type`](#property-type) | *Описание* |
| [`Validity`](#property-validity) | *Описание* |





***  
***  
# Методы

## `Order`<a href="method-order" id="method-order"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Order(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `Order`<a href="method-order" id="method-order"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Order(Symbol symbol, Account account)
public Order(Symbol symbol, Account account, Hashtable options)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  

`options` <mark style="color:red;">*`Hashtable`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Account`<a href="property-account" id="property-account"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Account Account { get; }
```  
***

## `AvgFillPrice`<a href="property-avgfillprice" id="property-avgfillprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? AvgFillPrice { get; set; }
```  
***

## `CancelInitiator`<a href="property-cancelinitiator" id="property-cancelinitiator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string CancelInitiator { get; set; }
```  
***

## `Comment`<a href="property-comment" id="property-comment"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Comment { get; set; }
```  
***

## `Connection`<a href="property-connection" id="property-connection"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ConnectionInfo Connection { get; }
```  
***

## `DisplayQty`<a href="property-displayqty" id="property-displayqty"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long? DisplayQty { get; set; }
```  
***

## `Filled`<a href="property-filled" id="property-filled"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Filled { get; set; }
```  
***

## `ID`<a href="property-id" id="property-id"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `IsActive`<a href="property-isactive" id="property-isactive"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsActive { get; }
```  
***

## `IsInactive`<a href="property-isinactive" id="property-isinactive"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsInactive { get; }
```  
***

## `IsSplicedFuturesSymbol`<a href="property-issplicedfuturessymbol" id="property-issplicedfuturessymbol"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSplicedFuturesSymbol { get; private set; }
```  
***

## `ModifyInitiator`<a href="property-modifyinitiator" id="property-modifyinitiator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ModifyInitiator { get; set; }
```  
***

## `ModifyParams`<a href="property-modifyparams" id="property-modifyparams"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderModifyParams ModifyParams { get; set; }
```  
***

## `Options`<a href="property-options" id="property-options"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Hashtable Options { get; }
```  
***

## `OrderID`<a href="property-orderid" id="property-orderid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string OrderID { get; internal set; }
```  
***

## `PlaceInitiator`<a href="property-placeinitiator" id="property-placeinitiator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PlaceInitiator { get; set; }
```  
***

## `PosClose`<a href="property-posclose" id="property-posclose"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool PosClose { get; set; }
```  
***

## `Price`<a href="property-price" id="property-price"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Price { get; set; }
```  
***

## `Quantity`<a href="property-quantity" id="property-quantity"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Quantity { get; set; }
```  
***

## `QuantityReal`<a href="property-quantityreal" id="property-quantityreal"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double QuantityReal { get; set; }
```  
***

## `Remaining`<a href="property-remaining" id="property-remaining"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Remaining { get; set; }
```  
***

## `RoundTrip`<a href="property-roundtrip" id="property-roundtrip"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RoundTrip RoundTrip { get; }
```  
***

## `Side`<a href="property-side" id="property-side"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Side Side { get; set; }
```  
***

## `State`<a href="property-state" id="property-state"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderState State { get; set; }
```  
***

## `StopPrice`<a href="property-stopprice" id="property-stopprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long StopPrice { get; set; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; }
```  
***

## `TakePrice`<a href="property-takeprice" id="property-takeprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long TakePrice { get; set; }
```  
***

## `Time`<a href="property-time" id="property-time"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; set; }
```  
***

## `TransID`<a href="property-transid" id="property-transid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TransID { get; internal set; }
```  
***

## `Type`<a href="property-type" id="property-type"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderType Type { get; set; }
```  
***

## `Validity`<a href="property-validity" id="property-validity"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderValidity Validity { get; set; }
```  
***

