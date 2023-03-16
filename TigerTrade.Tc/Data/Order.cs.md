
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

## `Account`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Account Account { get; }
```  
***

## `AvgFillPrice`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? AvgFillPrice { get; set; }
```  
***

## `CancelInitiator`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string CancelInitiator { get; set; }
```  
***

## `Comment`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Comment { get; set; }
```  
***

## `Connection`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ConnectionInfo Connection { get; }
```  
***

## `DisplayQty`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long? DisplayQty { get; set; }
```  
***

## `Filled`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Filled { get; set; }
```  
***

## `ID`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `IsActive`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsActive { get; }
```  
***

## `IsInactive`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsInactive { get; }
```  
***

## `IsSplicedFuturesSymbol`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSplicedFuturesSymbol { get; private set; }
```  
***

## `ModifyInitiator`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ModifyInitiator { get; set; }
```  
***

## `ModifyParams`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderModifyParams ModifyParams { get; set; }
```  
***

## `Options`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Hashtable Options { get; }
```  
***

## `OrderID`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string OrderID { get; internal set; }
```  
***

## `PlaceInitiator`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PlaceInitiator { get; set; }
```  
***

## `PosClose`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool PosClose { get; set; }
```  
***

## `Price`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Price { get; set; }
```  
***

## `Quantity`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Quantity { get; set; }
```  
***

## `QuantityReal`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double QuantityReal { get; set; }
```  
***

## `Remaining`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Remaining { get; set; }
```  
***

## `RoundTrip`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RoundTrip RoundTrip { get; }
```  
***

## `Side`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Side Side { get; set; }
```  
***

## `State`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderState State { get; set; }
```  
***

## `StopPrice`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long StopPrice { get; set; }
```  
***

## `Symbol`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; }
```  
***

## `TakePrice`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long TakePrice { get; set; }
```  
***

## `Time`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; set; }
```  
***

## `TransID`<a href="Validity-p" id="Validity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TransID { get; internal set; }
```  
***

## `Type`<a href="Validity-p" id="Validity-p"></a>
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

