
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


===

### Синтаксис
```csharp
public sealed class Position
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Position`](#method-position) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Account`](#property-account) | *===* |
| [`AvgPrice`](#property-avgprice) | *===* |
| [`Comission`](#property-comission) | *===* |
| [`Connection`](#property-connection) | *===* |
| [`Liquidation`](#property-liquidation) | *===* |
| [`PosNumID`](#property-posnumid) | *===* |
| [`PositionID`](#property-positionid) | *===* |
| [`Quantity`](#property-quantity) | *===* |
| [`RealizedPnl`](#property-realizedpnl) | *===* |
| [`Register`](#property-register) | *===* |
| [`SlPrice`](#property-slprice) | *===* |
| [`Symbol`](#property-symbol) | *===* |
| [`TpPrice`](#property-tpprice) | *===* |
| [`UnrealizedPnl`](#property-unrealizedpnl) | *===* |





***  
***  
# Методы

## `Position`<a href="method-position" id="method-position"></a>
===
```csharp
public Position(Symbol symbol, Account account, string uniqueID)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *===*  

`uniqueID` <mark style="color:red;">*`string`*</mark>  
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

## `AvgPrice`<a href="property-avgprice" id="property-avgprice"></a>
===
```csharp
public double AvgPrice { get; set; }
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

## `Liquidation`<a href="property-liquidation" id="property-liquidation"></a>
===
```csharp
public double? Liquidation { get; set; }
```  
***

## `PosNumID`<a href="property-posnumid" id="property-posnumid"></a>
===
```csharp
public long PosNumID { get; set; }
```  
***

## `PositionID`<a href="property-positionid" id="property-positionid"></a>
===
```csharp
public string PositionID { get; }
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

## `Register`<a href="property-register" id="property-register"></a>
===
```csharp
public string Register { get; set; }
```  
***

## `SlPrice`<a href="property-slprice" id="property-slprice"></a>
===
```csharp
public double? SlPrice { get; set; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
===
```csharp
public Symbol Symbol { get; }
```  
***

## `TpPrice`<a href="property-tpprice" id="property-tpprice"></a>
===
```csharp
public double? TpPrice { get; set; }
```  
***

## `UnrealizedPnl`<a href="property-unrealizedpnl" id="property-unrealizedpnl"></a>
===
```csharp
public double? UnrealizedPnl { get; set; }
```  
***

