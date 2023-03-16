
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Position
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Position`](#method-position) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Account`](#property-account) | *Описание* |
| [`AvgPrice`](#property-avgprice) | *Описание* |
| [`Comission`](#property-comission) | *Описание* |
| [`Connection`](#property-connection) | *Описание* |
| [`Liquidation`](#property-liquidation) | *Описание* |
| [`PosNumID`](#property-posnumid) | *Описание* |
| [`PositionID`](#property-positionid) | *Описание* |
| [`Quantity`](#property-quantity) | *Описание* |
| [`RealizedPnl`](#property-realizedpnl) | *Описание* |
| [`Register`](#property-register) | *Описание* |
| [`SlPrice`](#property-slprice) | *Описание* |
| [`Symbol`](#property-symbol) | *Описание* |
| [`TpPrice`](#property-tpprice) | *Описание* |
| [`UnrealizedPnl`](#property-unrealizedpnl) | *Описание* |





***  
***  
# Методы

## `Position`<a href="method-position" id="method-position"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Position(Symbol symbol, Account account, string uniqueID)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  

`uniqueID` <mark style="color:red;">*`string`*</mark>  
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

## `AvgPrice`<a href="property-avgprice" id="property-avgprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double AvgPrice { get; set; }
```  
***

## `Comission`<a href="property-comission" id="property-comission"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? Comission { get; set; }
```  
***

## `Connection`<a href="property-connection" id="property-connection"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ConnectionInfo Connection { get; }
```  
***

## `Liquidation`<a href="property-liquidation" id="property-liquidation"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? Liquidation { get; set; }
```  
***

## `PosNumID`<a href="property-posnumid" id="property-posnumid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long PosNumID { get; set; }
```  
***

## `PositionID`<a href="property-positionid" id="property-positionid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PositionID { get; }
```  
***

## `Quantity`<a href="property-quantity" id="property-quantity"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Quantity { get; set; }
```  
***

## `RealizedPnl`<a href="property-realizedpnl" id="property-realizedpnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? RealizedPnl { get; set; }
```  
***

## `Register`<a href="property-register" id="property-register"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Register { get; set; }
```  
***

## `SlPrice`<a href="property-slprice" id="property-slprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? SlPrice { get; set; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; }
```  
***

## `TpPrice`<a href="property-tpprice" id="property-tpprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? TpPrice { get; set; }
```  
***

## `UnrealizedPnl`<a href="property-unrealizedpnl" id="property-unrealizedpnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? UnrealizedPnl { get; set; }
```  
***

