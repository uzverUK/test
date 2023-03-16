
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Collections](../../TigerTrade.Tc/Collections.md)


Описание

### Синтаксис
```csharp
public sealed class UserPositions
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Add`](#method-add) | *Описание* |
| [`AddExecution`](#method-addexecution) | *Описание* |
| [`Clear`](#method-clear) | *Описание* |
| [`Create`](#method-create) | *Описание* |
| [`GetAll`](#method-getall) | *Описание* |
| [`GetBySymbol`](#method-getbysymbol) | *Описание* |
| [`Remove`](#method-remove) | *Описание* |
| [`UserPositions`](#method-userpositions) | *Описание* |





***  
***  
# Методы

## `Add`<a href="method-add" id="method-add"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Add(UserPosition position)
```

`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `AddExecution`<a href="method-addexecution" id="method-addexecution"></a>
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

## `Clear`<a href="method-clear" id="method-clear"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear()
```

***  

## `Create`<a href="method-create" id="method-create"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPosition Create(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `GetAll`<a href="method-getall" id="method-getall"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<UserPosition> GetAll()
```

***  

## `GetBySymbol`<a href="method-getbysymbol" id="method-getbysymbol"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<UserPosition> GetBySymbol(string symbolID)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Remove`<a href="method-remove" id="method-remove"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Remove(UserPosition position)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `UserPositions`<a href="method-userpositions" id="method-userpositions"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPositions()
```

***  

