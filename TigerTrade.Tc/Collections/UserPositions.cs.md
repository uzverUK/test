
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Collections](../../TigerTrade.Tc/Collections.md)


Описание

### Синтаксис
```csharp
public sealed class UserPositions
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Add`](#test) | *Описание* |
| [`AddExecution`](#test) | *Описание* |
| [`Clear`](#test) | *Описание* |
| [`Create`](#test) | *Описание* |
| [`GetAll`](#test) | *Описание* |
| [`GetBySymbol`](#test) | *Описание* |
| [`Remove`](#test) | *Описание* |
| [`UserPositions`](#test) | *Описание* |





***  
***  
# Методы

## `Add`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Add(UserPosition position)
```

`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `AddExecution`<a href="test" id="test"></a>
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

## `Clear`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear()
```

***  

## `Create`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPosition Create(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `GetAll`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<UserPosition> GetAll()
```

***  

## `GetBySymbol`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<UserPosition> GetBySymbol(string symbolID)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Remove`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Remove(UserPosition position)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `UserPositions`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPositions()
```

***  

