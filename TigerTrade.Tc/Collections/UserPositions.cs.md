
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Collections](../../TigerTrade.Tc/Collections.md)


===

### Синтаксис
```csharp
public sealed class UserPositions
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Add`](#method-add) | *===* |
| [`AddExecution`](#method-addexecution) | *===* |
| [`Clear`](#method-clear) | *===* |
| [`Create`](#method-create) | *===* |
| [`GetAll`](#method-getall) | *===* |
| [`GetBySymbol`](#method-getbysymbol) | *===* |
| [`Remove`](#method-remove) | *===* |
| [`UserPositions`](#method-userpositions) | *===* |





***  
***  
# Методы

## `Add`<a href="method-add" id="method-add"></a>
===
```csharp
public void Add(UserPosition position)
```

`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *===*  


***  

## `AddExecution`<a href="method-addexecution" id="method-addexecution"></a>
===
```csharp
public UserPosition AddExecution(Execution execution, out UserDeal deal, out bool updated)
```
`execution` <mark style="color:red;">*`Execution`*</mark>  
 *===*  

`UserDeal` <mark style="color:red;">*`out`*</mark>  
 *===*  

`bool` <mark style="color:red;">*`out`*</mark>  
 *===*  


***  

## `Clear`<a href="method-clear" id="method-clear"></a>
===
```csharp
public void Clear()
```

***  

## `Create`<a href="method-create" id="method-create"></a>
===
```csharp
public UserPosition Create(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *===*  


***  

## `GetAll`<a href="method-getall" id="method-getall"></a>
===
```csharp
public List<UserPosition> GetAll()
```

***  

## `GetBySymbol`<a href="method-getbysymbol" id="method-getbysymbol"></a>
===
```csharp
public List<UserPosition> GetBySymbol(string symbolID)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `Remove`<a href="method-remove" id="method-remove"></a>
===
```csharp
public void Remove(UserPosition position)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *===*  


***  

## `UserPositions`<a href="method-userpositions" id="method-userpositions"></a>
===
```csharp
public UserPositions()
```

***  

