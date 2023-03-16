
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Position
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Position`](#Position-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Account`](#Account-p) | *Описание* |
| [`AvgPrice`](#AvgPrice-p) | *Описание* |
| [`Comission`](#Comission-p) | *Описание* |
| [`Connection`](#Connection-p) | *Описание* |
| [`Liquidation`](#Liquidation-p) | *Описание* |
| [`PosNumID`](#PosNumID-p) | *Описание* |
| [`PositionID`](#PositionID-p) | *Описание* |
| [`Quantity`](#Quantity-p) | *Описание* |
| [`RealizedPnl`](#RealizedPnl-p) | *Описание* |
| [`Register`](#Register-p) | *Описание* |
| [`SlPrice`](#SlPrice-p) | *Описание* |
| [`Symbol`](#Symbol-p) | *Описание* |
| [`TpPrice`](#TpPrice-p) | *Описание* |
| [`UnrealizedPnl`](#UnrealizedPnl-p) | *Описание* |





***  
***  
# Методы

## `Position`<a href="Position-m" id="Position-m"></a>
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

## `Account`<a href="Account-p" id="Account-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Account Account { get; }
```  
***

## `AvgPrice`<a href="AvgPrice-p" id="AvgPrice-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double AvgPrice { get; set; }
```  
***

## `Comission`<a href="Comission-p" id="Comission-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? Comission { get; set; }
```  
***

## `Connection`<a href="Connection-p" id="Connection-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ConnectionInfo Connection { get; }
```  
***

## `Liquidation`<a href="Liquidation-p" id="Liquidation-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? Liquidation { get; set; }
```  
***

## `PosNumID`<a href="PosNumID-p" id="PosNumID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long PosNumID { get; set; }
```  
***

## `PositionID`<a href="PositionID-p" id="PositionID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PositionID { get; }
```  
***

## `Quantity`<a href="Quantity-p" id="Quantity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Quantity { get; set; }
```  
***

## `RealizedPnl`<a href="RealizedPnl-p" id="RealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? RealizedPnl { get; set; }
```  
***

## `Register`<a href="Register-p" id="Register-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Register { get; set; }
```  
***

## `SlPrice`<a href="SlPrice-p" id="SlPrice-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? SlPrice { get; set; }
```  
***

## `Symbol`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; }
```  
***

## `TpPrice`<a href="TpPrice-p" id="TpPrice-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? TpPrice { get; set; }
```  
***

## `UnrealizedPnl`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? UnrealizedPnl { get; set; }
```  
***

