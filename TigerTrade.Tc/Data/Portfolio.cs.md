
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Portfolio
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Portfolio`](#Portfolio-m) | *Описание* |
| [`ToString`](#ToString-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Balance`](#Balance-p) | *Описание* |
| [`Comission`](#Comission-p) | *Описание* |
| [`Connection`](#Connection-p) | *Описание* |
| [`ConnectionID`](#ConnectionID-p) | *Описание* |
| [`Currency`](#Currency-p) | *Описание* |
| [`FreeMargin`](#FreeMargin-p) | *Описание* |
| [`Leverage`](#Leverage-p) | *Описание* |
| [`Name`](#Name-p) | *Описание* |
| [`PortfolioID`](#PortfolioID-p) | *Описание* |
| [`Precision`](#Precision-p) | *Описание* |
| [`RealizedPnl`](#RealizedPnl-p) | *Описание* |
| [`Register`](#Register-p) | *Описание* |
| [`UnrealizedPnl`](#UnrealizedPnl-p) | *Описание* |
| [`UsedMargin`](#UsedMargin-p) | *Описание* |





***  
***  
# Методы

## `Portfolio`<a href="Portfolio-m" id="Portfolio-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Portfolio(ConnectionInfo connection, string uniqueID)
```

`connection` <mark style="color:red;">*`ConnectionInfo`*</mark>  
 *Описание*  

`uniqueID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ToString`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Balance`<a href="Balance-p" id="Balance-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Balance { get; set; }
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

## `ConnectionID`<a href="ConnectionID-p" id="ConnectionID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionID { get; }
```  
***

## `Currency`<a href="Currency-p" id="Currency-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Currency { get; set; }
```  
***

## `FreeMargin`<a href="FreeMargin-p" id="FreeMargin-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double FreeMargin { get; set; }
```  
***

## `Leverage`<a href="Leverage-p" id="Leverage-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int? Leverage { get; set; }
```  
***

## `Name`<a href="Name-p" id="Name-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; set; }
```  
***

## `PortfolioID`<a href="PortfolioID-p" id="PortfolioID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PortfolioID { get; set; }
```  
***

## `Precision`<a href="Precision-p" id="Precision-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Precision { get; set; }
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

## `UnrealizedPnl`<a href="UnrealizedPnl-p" id="UnrealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? UnrealizedPnl { get; set; }
```  
***

## `UsedMargin`<a href="UsedMargin-p" id="UsedMargin-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double UsedMargin { get; set; }
```  
***

