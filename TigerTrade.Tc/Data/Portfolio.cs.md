
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Portfolio
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Portfolio`](#method-portfolio) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Balance`](#property-balance) | *Описание* |
| [`Comission`](#property-comission) | *Описание* |
| [`Connection`](#property-connection) | *Описание* |
| [`ConnectionID`](#property-connectionid) | *Описание* |
| [`Currency`](#property-currency) | *Описание* |
| [`FreeMargin`](#property-freemargin) | *Описание* |
| [`Leverage`](#property-leverage) | *Описание* |
| [`Name`](#property-name) | *Описание* |
| [`PortfolioID`](#property-portfolioid) | *Описание* |
| [`Precision`](#property-precision) | *Описание* |
| [`RealizedPnl`](#property-realizedpnl) | *Описание* |
| [`Register`](#property-register) | *Описание* |
| [`UnrealizedPnl`](#property-unrealizedpnl) | *Описание* |
| [`UsedMargin`](#property-usedmargin) | *Описание* |





***  
***  
# Методы

## `Portfolio`<a href="method-portfolio" id="method-portfolio"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Portfolio(ConnectionInfo connection, string uniqueID)
```

`connection` <mark style="color:red;">*`ConnectionInfo`*</mark>  
 *Описание*  

`uniqueID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Balance`<a href="property-balance" id="property-balance"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Balance { get; set; }
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

## `ConnectionID`<a href="property-connectionid" id="property-connectionid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionID { get; }
```  
***

## `Currency`<a href="property-currency" id="property-currency"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Currency { get; set; }
```  
***

## `FreeMargin`<a href="property-freemargin" id="property-freemargin"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double FreeMargin { get; set; }
```  
***

## `Leverage`<a href="property-leverage" id="property-leverage"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int? Leverage { get; set; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; set; }
```  
***

## `PortfolioID`<a href="property-portfolioid" id="property-portfolioid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PortfolioID { get; set; }
```  
***

## `Precision`<a href="property-precision" id="property-precision"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Precision { get; set; }
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

## `UnrealizedPnl`<a href="property-unrealizedpnl" id="property-unrealizedpnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? UnrealizedPnl { get; set; }
```  
***

## `UsedMargin`<a href="property-usedmargin" id="property-usedmargin"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double UsedMargin { get; set; }
```  
***

