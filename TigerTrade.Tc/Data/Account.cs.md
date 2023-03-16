
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Account
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Account`](#method-account) | *Описание* |
| [`GetConnectionID`](#method-getconnectionid) | *Описание* |
| [`GetUniqueID`](#method-getuniqueid) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AccountID`](#property-accountid) | *Описание* |
| [`Connection`](#property-connection) | *Описание* |
| [`ConnectionID`](#property-connectionid) | *Описание* |
| [`Currency`](#property-currency) | *Описание* |
| [`IsLive`](#property-islive) | *Описание* |
| [`IsPlayer`](#property-isplayer) | *Описание* |
| [`IsSimulator`](#property-issimulator) | *Описание* |
| [`Name`](#property-name) | *Описание* |
| [`Simulator`](#property-simulator) | *Описание* |
| [`Trust`](#property-trust) | *Описание* |
| [`Union`](#property-union) | *Описание* |





***  
***  
# Методы

## `Account`<a href="method-account" id="method-account"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Account(ConnectionInfo connection, string uniqueID)
```

`connection` <mark style="color:red;">*`ConnectionInfo`*</mark>  
 *Описание*  

`uniqueID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetConnectionID`<a href="method-getconnectionid" id="method-getconnectionid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string GetConnectionID(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetUniqueID`<a href="method-getuniqueid" id="method-getuniqueid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string GetUniqueID(string id)
```

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

## `AccountID`<a href="property-accountid" id="property-accountid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string AccountID { get; }
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

## `IsLive`<a href="property-islive" id="property-islive"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsLive { get; }
```  
***

## `IsPlayer`<a href="property-isplayer" id="property-isplayer"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsPlayer { get; }
```  
***

## `IsSimulator`<a href="property-issimulator" id="property-issimulator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSimulator { get; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; set; }
```  
***

## `Simulator`<a href="property-simulator" id="property-simulator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Simulator { get; internal set; }
```  
***

## `Trust`<a href="property-trust" id="property-trust"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Trust { get; internal set; }
```  
***

## `Union`<a href="property-union" id="property-union"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Union { get; set; }
```  
***

