# UserPositions

`namespace` [TigerTrade.Tc](../).[Collections](./)

\===

#### Синтаксис

```csharp
public sealed class UserPositions
```

## Список методов

| Название                                                    | Описание |
| ----------------------------------------------------------- | -------- |
| [`Add`](userpositions.cs.md#method-add)                     | _===_    |
| [`AddExecution`](userpositions.cs.md#method-addexecution)   | _===_    |
| [`Clear`](userpositions.cs.md#method-clear)                 | _===_    |
| [`Create`](userpositions.cs.md#method-create)               | _===_    |
| [`GetAll`](userpositions.cs.md#method-getall)               | _===_    |
| [`GetBySymbol`](userpositions.cs.md#method-getbysymbol)     | _===_    |
| [`Remove`](userpositions.cs.md#method-remove)               | _===_    |
| [`UserPositions`](userpositions.cs.md#method-userpositions) | _===_    |

***

***

## Методы

### `Add` <a href="#method-add" id="method-add"></a>

\===

```csharp
public void Add(UserPosition position)
```

`position` _<mark style="color:red;">`UserPosition`</mark>_\
_===_

***

### `AddExecution` <a href="#method-addexecution" id="method-addexecution"></a>

\===

```csharp
public UserPosition AddExecution(Execution execution, out UserDeal deal, out bool updated)
```

`execution` _<mark style="color:red;">`Execution`</mark>_\
_===_

`UserDeal` _<mark style="color:red;">`out`</mark>_\
_===_

`bool` _<mark style="color:red;">`out`</mark>_\
_===_

***

### `Clear` <a href="#method-clear" id="method-clear"></a>

\===

```csharp
public void Clear()
```

***

### `Create` <a href="#method-create" id="method-create"></a>

\===

```csharp
public UserPosition Create(Symbol symbol, Account account)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`account` _<mark style="color:red;">`Account`</mark>_\
_===_

***

### `GetAll` <a href="#method-getall" id="method-getall"></a>

\===

```csharp
public List<UserPosition> GetAll()
```

***

### `GetBySymbol` <a href="#method-getbysymbol" id="method-getbysymbol"></a>

\===

```csharp
public List<UserPosition> GetBySymbol(string symbolID)
```

`symbolID` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `Remove` <a href="#method-remove" id="method-remove"></a>

\===

```csharp
public void Remove(UserPosition position)
```

`position` _<mark style="color:red;">`UserPosition`</mark>_\
_===_

***

### `UserPositions` <a href="#method-userpositions" id="method-userpositions"></a>

\===

```csharp
public UserPositions()
```

***
