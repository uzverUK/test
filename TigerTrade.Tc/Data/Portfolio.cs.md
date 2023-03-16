
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


===

### Синтаксис
```csharp
public sealed class Portfolio
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Portfolio`](#method-portfolio) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Balance`](#property-balance) | *===* |
| [`Comission`](#property-comission) | *===* |
| [`Connection`](#property-connection) | *===* |
| [`ConnectionID`](#property-connectionid) | *===* |
| [`Currency`](#property-currency) | *===* |
| [`FreeMargin`](#property-freemargin) | *===* |
| [`Leverage`](#property-leverage) | *===* |
| [`Name`](#property-name) | *===* |
| [`PortfolioID`](#property-portfolioid) | *===* |
| [`Precision`](#property-precision) | *===* |
| [`RealizedPnl`](#property-realizedpnl) | *===* |
| [`Register`](#property-register) | *===* |
| [`UnrealizedPnl`](#property-unrealizedpnl) | *===* |
| [`UsedMargin`](#property-usedmargin) | *===* |





***  
***  
# Методы

## `Portfolio`<a href="method-portfolio" id="method-portfolio"></a>
===
```csharp
public Portfolio(ConnectionInfo connection, string uniqueID)
```

`connection` <mark style="color:red;">*`ConnectionInfo`*</mark>  
 *===*  

`uniqueID` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
===
```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Balance`<a href="property-balance" id="property-balance"></a>
===
```csharp
public double Balance { get; set; }
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

## `ConnectionID`<a href="property-connectionid" id="property-connectionid"></a>
===
```csharp
public string ConnectionID { get; }
```  
***

## `Currency`<a href="property-currency" id="property-currency"></a>
===
```csharp
public string Currency { get; set; }
```  
***

## `FreeMargin`<a href="property-freemargin" id="property-freemargin"></a>
===
```csharp
public double FreeMargin { get; set; }
```  
***

## `Leverage`<a href="property-leverage" id="property-leverage"></a>
===
```csharp
public int? Leverage { get; set; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
===
```csharp
public string Name { get; set; }
```  
***

## `PortfolioID`<a href="property-portfolioid" id="property-portfolioid"></a>
===
```csharp
public string PortfolioID { get; set; }
```  
***

## `Precision`<a href="property-precision" id="property-precision"></a>
===
```csharp
public int Precision { get; set; }
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

## `UnrealizedPnl`<a href="property-unrealizedpnl" id="property-unrealizedpnl"></a>
===
```csharp
public double? UnrealizedPnl { get; set; }
```  
***

## `UsedMargin`<a href="property-usedmargin" id="property-usedmargin"></a>
===
```csharp
public double UsedMargin { get; set; }
```  
***

