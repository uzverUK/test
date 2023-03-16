
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Collections](../../TigerTrade.Tc/Collections.md)


Описание

### Синтаксис
```csharp
public sealed class UserPositions
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Add`](#Add-m) | *Описание* |
| [`AddExecution`](#AddExecution-m) | *Описание* |
| [`Clear`](#Clear-m) | *Описание* |
| [`Create`](#Create-m) | *Описание* |
| [`GetAll`](#GetAll-m) | *Описание* |
| [`GetBySymbol`](#GetBySymbol-m) | *Описание* |
| [`Remove`](#Remove-m) | *Описание* |
| [`UserPositions`](#UserPositions-m) | *Описание* |





***  
***  
# Методы

## `Add`<a href="Add-m" id="Add-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Add(UserPosition position)
```

`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `AddExecution`<a href="AddExecution-m" id="AddExecution-m"></a>
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

## `Clear`<a href="Clear-m" id="Clear-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear()
```

***  

## `Create`<a href="Create-m" id="Create-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPosition Create(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `GetAll`<a href="GetAll-m" id="GetAll-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<UserPosition> GetAll()
```

***  

## `GetBySymbol`<a href="GetBySymbol-m" id="GetBySymbol-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<UserPosition> GetBySymbol(string symbolID)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Remove`<a href="Remove-m" id="Remove-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Remove(UserPosition position)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `UserPositions`<a href="UserPositions-m" id="UserPositions-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPositions()
```

***  

