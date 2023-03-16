
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

## `Account`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Account Account { get; }
```  
***

## `AvgPrice`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double AvgPrice { get; set; }
```  
***

## `Comission`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? Comission { get; set; }
```  
***

## `Connection`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ConnectionInfo Connection { get; }
```  
***

## `Liquidation`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? Liquidation { get; set; }
```  
***

## `PosNumID`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long PosNumID { get; set; }
```  
***

## `PositionID`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PositionID { get; }
```  
***

## `Quantity`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Quantity { get; set; }
```  
***

## `RealizedPnl`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? RealizedPnl { get; set; }
```  
***

## `Register`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Register { get; set; }
```  
***

## `SlPrice`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? SlPrice { get; set; }
```  
***

## `Symbol`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; }
```  
***

## `TpPrice`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
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

