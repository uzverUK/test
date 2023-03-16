
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Collections](../../TigerTrade.Tc/Collections.md)


Описание

### Синтаксис
```csharp
public sealed class UserPositions
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Add`](./UserPositions.cs/Методы/Add.md) | *Описание* |
| [`AddExecution`](./UserPositions.cs/Методы/AddExecution.md) | *Описание* |
| [`Clear`](./UserPositions.cs/Методы/Clear.md) | *Описание* |
| [`Create`](./UserPositions.cs/Методы/Create.md) | *Описание* |
| [`GetAll`](./UserPositions.cs/Методы/GetAll.md) | *Описание* |
| [`GetBySymbol`](./UserPositions.cs/Методы/GetBySymbol.md) | *Описание* |
| [`Remove`](./UserPositions.cs/Методы/Remove.md) | *Описание* |
| [`UserPositions`](./UserPositions.cs/Методы/UserPositions.md) | *Описание* |





***  
***  
# Методы

## `Add`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Add(UserPosition position)
```

`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `AddExecution`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPosition AddExecution(Execution execution, out UserDeal deal, out bool updated)
```
`execution` <mark style="color:red;">*`Execution`*</mark>  
 *Описание*  

`UserDeal` <mark style="color:red;">*`out`*</mark>  
 *Описание*  

`bool` <mark style="color:red;">*`out`*</mark>  
 *Описание*  


***  

## `Clear`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear()
```

***  

## `Create`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPosition Create(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `GetAll`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<UserPosition> GetAll()
```

***  

## `GetBySymbol`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<UserPosition> GetBySymbol(string symbolID)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Remove`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Remove(UserPosition position)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `UserPositions`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPositions()
```

***  

