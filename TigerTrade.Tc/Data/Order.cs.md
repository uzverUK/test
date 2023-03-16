
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Order
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Order`](#Order-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Account`](#Account-p) | *Описание* |
| [`AvgFillPrice`](#AvgFillPrice-p) | *Описание* |
| [`CancelInitiator`](#CancelInitiator-p) | *Описание* |
| [`Comment`](#Comment-p) | *Описание* |
| [`Connection`](#Connection-p) | *Описание* |
| [`DisplayQty`](#DisplayQty-p) | *Описание* |
| [`Filled`](#Filled-p) | *Описание* |
| [`ID`](#ID-p) | *Описание* |
| [`IsActive`](#IsActive-p) | *Описание* |
| [`IsInactive`](#IsInactive-p) | *Описание* |
| [`IsSplicedFuturesSymbol`](#IsSplicedFuturesSymbol-p) | *Описание* |
| [`ModifyInitiator`](#ModifyInitiator-p) | *Описание* |
| [`ModifyParams`](#ModifyParams-p) | *Описание* |
| [`Options`](#Options-p) | *Описание* |
| [`OrderID`](#OrderID-p) | *Описание* |
| [`PlaceInitiator`](#PlaceInitiator-p) | *Описание* |
| [`PosClose`](#PosClose-p) | *Описание* |
| [`Price`](#Price-p) | *Описание* |
| [`Quantity`](#Quantity-p) | *Описание* |
| [`QuantityReal`](#QuantityReal-p) | *Описание* |
| [`Remaining`](#Remaining-p) | *Описание* |
| [`RoundTrip`](#RoundTrip-p) | *Описание* |
| [`Side`](#Side-p) | *Описание* |
| [`State`](#State-p) | *Описание* |
| [`StopPrice`](#StopPrice-p) | *Описание* |
| [`Symbol`](#Symbol-p) | *Описание* |
| [`TakePrice`](#TakePrice-p) | *Описание* |
| [`Time`](#Time-p) | *Описание* |
| [`TransID`](#TransID-p) | *Описание* |
| [`Type`](#Type-p) | *Описание* |
| [`Validity`](#Validity-p) | *Описание* |





***  
***  
# Методы

## `Order`<a href="Order-m" id="Order-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Order(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `Order`<a href="Order-m" id="Order-m"></a>
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

## `Account`<a href="Account-p" id="Account-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Account Account { get; }
```  
***

## `AvgFillPrice`<a href="AvgFillPrice-p" id="AvgFillPrice-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? AvgFillPrice { get; set; }
```  
***

## `CancelInitiator`<a href="CancelInitiator-p" id="CancelInitiator-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string CancelInitiator { get; set; }
```  
***

## `Comment`<a href="Comment-p" id="Comment-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Comment { get; set; }
```  
***

## `Connection`<a href="Connection-p" id="Connection-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ConnectionInfo Connection { get; }
```  
***

## `DisplayQty`<a href="DisplayQty-p" id="DisplayQty-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long? DisplayQty { get; set; }
```  
***

## `Filled`<a href="Filled-p" id="Filled-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Filled { get; set; }
```  
***

## `ID`<a href="ID-p" id="ID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `IsActive`<a href="IsActive-p" id="IsActive-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsActive { get; }
```  
***

## `IsInactive`<a href="IsInactive-p" id="IsInactive-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsInactive { get; }
```  
***

## `IsSplicedFuturesSymbol`<a href="IsSplicedFuturesSymbol-p" id="IsSplicedFuturesSymbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSplicedFuturesSymbol { get; private set; }
```  
***

## `ModifyInitiator`<a href="ModifyInitiator-p" id="ModifyInitiator-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ModifyInitiator { get; set; }
```  
***

## `ModifyParams`<a href="ModifyParams-p" id="ModifyParams-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderModifyParams ModifyParams { get; set; }
```  
***

## `Options`<a href="Options-p" id="Options-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Hashtable Options { get; }
```  
***

## `OrderID`<a href="OrderID-p" id="OrderID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string OrderID { get; internal set; }
```  
***

## `PlaceInitiator`<a href="PlaceInitiator-p" id="PlaceInitiator-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PlaceInitiator { get; set; }
```  
***

## `PosClose`<a href="PosClose-p" id="PosClose-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool PosClose { get; set; }
```  
***

## `Price`<a href="Price-p" id="Price-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Price { get; set; }
```  
***

## `Quantity`<a href="Quantity-p" id="Quantity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Quantity { get; set; }
```  
***

## `QuantityReal`<a href="QuantityReal-p" id="QuantityReal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double QuantityReal { get; set; }
```  
***

## `Remaining`<a href="Remaining-p" id="Remaining-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Remaining { get; set; }
```  
***

## `RoundTrip`<a href="RoundTrip-p" id="RoundTrip-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RoundTrip RoundTrip { get; }
```  
***

## `Side`<a href="Side-p" id="Side-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Side Side { get; set; }
```  
***

## `State`<a href="State-p" id="State-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderState State { get; set; }
```  
***

## `StopPrice`<a href="StopPrice-p" id="StopPrice-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long StopPrice { get; set; }
```  
***

## `Symbol`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; }
```  
***

## `TakePrice`<a href="TakePrice-p" id="TakePrice-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long TakePrice { get; set; }
```  
***

## `Time`<a href="Time-p" id="Time-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; set; }
```  
***

## `TransID`<a href="TransID-p" id="TransID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TransID { get; internal set; }
```  
***

## `Type`<a href="Type-p" id="Type-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderType Type { get; set; }
```  
***

## `Validity`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderValidity Validity { get; set; }
```  
***

