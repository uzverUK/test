
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


===

### Синтаксис
```csharp
public sealed class Account
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Account`](#method-account) | *===* |
| [`GetConnectionID`](#method-getconnectionid) | *===* |
| [`GetUniqueID`](#method-getuniqueid) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AccountID`](#property-accountid) | *===* |
| [`Connection`](#property-connection) | *===* |
| [`ConnectionID`](#property-connectionid) | *===* |
| [`Currency`](#property-currency) | *===* |
| [`IsLive`](#property-islive) | *===* |
| [`IsPlayer`](#property-isplayer) | *===* |
| [`IsSimulator`](#property-issimulator) | *===* |
| [`Name`](#property-name) | *===* |
| [`Simulator`](#property-simulator) | *===* |
| [`Trust`](#property-trust) | *===* |
| [`Union`](#property-union) | *===* |





***  
***  
# Методы

## `Account`<a href="method-account" id="method-account"></a>
===
```csharp
public Account(ConnectionInfo connection, string uniqueID)
```

`connection` <mark style="color:red;">*`ConnectionInfo`*</mark>  
 *===*  

`uniqueID` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetConnectionID`<a href="method-getconnectionid" id="method-getconnectionid"></a>
===
```csharp
public static string GetConnectionID(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetUniqueID`<a href="method-getuniqueid" id="method-getuniqueid"></a>
===
```csharp
public static string GetUniqueID(string id)
```

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

## `AccountID`<a href="property-accountid" id="property-accountid"></a>
===
```csharp
public string AccountID { get; }
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

## `IsLive`<a href="property-islive" id="property-islive"></a>
===
```csharp
public bool IsLive { get; }
```  
***

## `IsPlayer`<a href="property-isplayer" id="property-isplayer"></a>
===
```csharp
public bool IsPlayer { get; }
```  
***

## `IsSimulator`<a href="property-issimulator" id="property-issimulator"></a>
===
```csharp
public bool IsSimulator { get; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
===
```csharp
public string Name { get; set; }
```  
***

## `Simulator`<a href="property-simulator" id="property-simulator"></a>
===
```csharp
public bool Simulator { get; internal set; }
```  
***

## `Trust`<a href="property-trust" id="property-trust"></a>
===
```csharp
public bool Trust { get; internal set; }
```  
***

## `Union`<a href="property-union" id="property-union"></a>
===
```csharp
public string Union { get; set; }
```  
***

