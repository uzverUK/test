
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


===

### Синтаксис
```csharp
public sealed class Execution
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Execution`](#method-execution) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Account`](#property-account) | *===* |
| [`Comission`](#property-comission) | *===* |
| [`Connection`](#property-connection) | *===* |
| [`Currency`](#property-currency) | *===* |
| [`ExecutionID`](#property-executionid) | *===* |
| [`ID`](#property-id) | *===* |
| [`OrderID`](#property-orderid) | *===* |
| [`Price`](#property-price) | *===* |
| [`Quantity`](#property-quantity) | *===* |
| [`RealizedPnl`](#property-realizedpnl) | *===* |
| [`Side`](#property-side) | *===* |
| [`Symbol`](#property-symbol) | *===* |
| [`Time`](#property-time) | *===* |





***  
***  
# Методы

## `Execution`<a href="method-execution" id="method-execution"></a>
===
```csharp
public Execution(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  

`account` <mark style="color:red;">*`Account`*</mark>  
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

## `Comission`<a href="property-comission" id="property-comission"></a>
===
```csharp
public double? Comission { get; set; }
```  
***

## `Connection`<a href="property-connection" id="property-connection"></a>
===
```csharp
public ConnectionInfo Connection { get; }
```  
***

## `Currency`<a href="property-currency" id="property-currency"></a>
===
```csharp
public string Currency { get; set; }
```  
***

## `ExecutionID`<a href="property-executionid" id="property-executionid"></a>
===
```csharp
public string ExecutionID { get; set; }
```  
***

## `ID`<a href="property-id" id="property-id"></a>
===
```csharp
public string ID { get; }
```  
***

## `OrderID`<a href="property-orderid" id="property-orderid"></a>
===
```csharp
public string OrderID { get; set; }
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

## `RealizedPnl`<a href="property-realizedpnl" id="property-realizedpnl"></a>
===
```csharp
public double? RealizedPnl { get; set; }
```  
***

## `Side`<a href="property-side" id="property-side"></a>
===
```csharp
public Side Side { get; set; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
===
```csharp
public Symbol Symbol { get; }
```  
***

## `Time`<a href="property-time" id="property-time"></a>
===
```csharp
public DateTime Time { get; set; }
```  
***

