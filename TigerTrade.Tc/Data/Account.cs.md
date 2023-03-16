
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Account
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Account`](#Account-m) | *Описание* |
| [`GetConnectionID`](#GetConnectionID-m) | *Описание* |
| [`GetUniqueID`](#GetUniqueID-m) | *Описание* |
| [`ToString`](#ToString-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AccountID`](#AccountID-p) | *Описание* |
| [`Connection`](#Connection-p) | *Описание* |
| [`ConnectionID`](#ConnectionID-p) | *Описание* |
| [`Currency`](#Currency-p) | *Описание* |
| [`IsLive`](#IsLive-p) | *Описание* |
| [`IsPlayer`](#IsPlayer-p) | *Описание* |
| [`IsSimulator`](#IsSimulator-p) | *Описание* |
| [`Name`](#Name-p) | *Описание* |
| [`Simulator`](#Simulator-p) | *Описание* |
| [`Trust`](#Trust-p) | *Описание* |
| [`Union`](#Union-p) | *Описание* |





***  
***  
# Методы

## `Account`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Account(ConnectionInfo connection, string uniqueID)
```

`connection` <mark style="color:red;">*`ConnectionInfo`*</mark>  
 *Описание*  

`uniqueID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetConnectionID`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string GetConnectionID(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetUniqueID`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string GetUniqueID(string id)
```

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

## `AccountID`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string AccountID { get; }
```  
***

## `Connection`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ConnectionInfo Connection { get; }
```  
***

## `ConnectionID`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionID { get; }
```  
***

## `Currency`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Currency { get; set; }
```  
***

## `IsLive`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsLive { get; }
```  
***

## `IsPlayer`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsPlayer { get; }
```  
***

## `IsSimulator`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSimulator { get; }
```  
***

## `Name`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; set; }
```  
***

## `Simulator`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Simulator { get; internal set; }
```  
***

## `Trust`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Trust { get; internal set; }
```  
***

## `Union`<a href="Union-p" id="Union-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Union { get; set; }
```  
***

