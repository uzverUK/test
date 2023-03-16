# Account

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class Account
```

## Список методов

| Название                                                  | Описание |
| --------------------------------------------------------- | -------- |
| [`Account`](account.cs.md#method-account)                 | _===_    |
| [`GetConnectionID`](account.cs.md#method-getconnectionid) | _===_    |
| [`GetUniqueID`](account.cs.md#method-getuniqueid)         | _===_    |
| [`ToString`](account.cs.md#method-tostring)               | _===_    |

## Список свойств

| Название                                              | Описание |
| ----------------------------------------------------- | -------- |
| [`AccountID`](account.cs.md#property-accountid)       | _===_    |
| [`Connection`](account.cs.md#property-connection)     | _===_    |
| [`ConnectionID`](account.cs.md#property-connectionid) | _===_    |
| [`Currency`](account.cs.md#property-currency)         | _===_    |
| [`IsLive`](account.cs.md#property-islive)             | _===_    |
| [`IsPlayer`](account.cs.md#property-isplayer)         | _===_    |
| [`IsSimulator`](account.cs.md#property-issimulator)   | _===_    |
| [`Name`](account.cs.md#property-name)                 | _===_    |
| [`Simulator`](account.cs.md#property-simulator)       | _===_    |
| [`Trust`](account.cs.md#property-trust)               | _===_    |
| [`Union`](account.cs.md#property-union)               | _===_    |

***

***

## Методы

### `Account` <a href="#method-account" id="method-account"></a>

\===

```csharp
public Account(ConnectionInfo connection, string uniqueID)
```

`connection` _<mark style="color:red;">`ConnectionInfo`</mark>_\
_===_

`uniqueID` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetConnectionID` <a href="#method-getconnectionid" id="method-getconnectionid"></a>

\===

```csharp
public static string GetConnectionID(string id)
```

`id` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetUniqueID` <a href="#method-getuniqueid" id="method-getuniqueid"></a>

\===

```csharp
public static string GetUniqueID(string id)
```

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

***

***

***

## Свойства

### `AccountID` <a href="#property-accountid" id="property-accountid"></a>

\===

```csharp
public string AccountID { get; }
```

***

### `Connection` <a href="#property-connection" id="property-connection"></a>

\===

```csharp
public ConnectionInfo Connection { get; }
```

***

### `ConnectionID` <a href="#property-connectionid" id="property-connectionid"></a>

\===

```csharp
public string ConnectionID { get; }
```

***

### `Currency` <a href="#property-currency" id="property-currency"></a>

\===

```csharp
public string Currency { get; set; }
```

***

### `IsLive` <a href="#property-islive" id="property-islive"></a>

\===

```csharp
public bool IsLive { get; }
```

***

### `IsPlayer` <a href="#property-isplayer" id="property-isplayer"></a>

\===

```csharp
public bool IsPlayer { get; }
```

***

### `IsSimulator` <a href="#property-issimulator" id="property-issimulator"></a>

\===

```csharp
public bool IsSimulator { get; }
```

***

### `Name` <a href="#property-name" id="property-name"></a>

\===

```csharp
public string Name { get; set; }
```

***

### `Simulator` <a href="#property-simulator" id="property-simulator"></a>

\===

```csharp
public bool Simulator { get; internal set; }
```

***

### `Trust` <a href="#property-trust" id="property-trust"></a>

\===

```csharp
public bool Trust { get; internal set; }
```

***

### `Union` <a href="#property-union" id="property-union"></a>

\===

```csharp
public string Union { get; set; }
```

***
