
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


Описание

### Синтаксис
```csharp
public static class SymbolManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](./SymbolManager.cs/Методы/Clear.md) | *Описание* |
| [`FindSwitchPair`](./SymbolManager.cs/Методы/FindSwitchPair.md) | *Описание* |
| [`FireSymbolUpdatedEvent`](./SymbolManager.cs/Методы/FireSymbolUpdatedEvent.md) | *Описание* |
| [`Get`](./SymbolManager.cs/Методы/Get.md) | *Описание* |
| [`GetAll`](./SymbolManager.cs/Методы/GetAll.md) | *Описание* |
| [`GetAllOptions`](./SymbolManager.cs/Методы/GetAllOptions.md) | *Описание* |
| [`LoadOrUpdate`](./SymbolManager.cs/Методы/LoadOrUpdate.md) | *Описание* |
| [`RiseFavoritesReady`](./SymbolManager.cs/Методы/RiseFavoritesReady.md) | *Описание* |
| [`RiseSymbolsReady`](./SymbolManager.cs/Методы/RiseSymbolsReady.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ClientSpecLastUpdate`](./SymbolManager.cs/Свойства/ClientSpecLastUpdate.md) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`Action`](./SymbolManager.cs/События/Action.md) | *Описание* |
| [`Action`](./SymbolManager.cs/События/Action.md) | *Описание* |
| [`Action`](./SymbolManager.cs/События/Action.md) | *Описание* |
| [`SymbolUpdated;`](./SymbolManager.cs/События/SymbolUpdated;.md) | *Описание* |





***  
***  
# Методы

## `Clear<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Clear()
```

***  

## `FindSwitchPair<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Symbol FindSwitchPair(Symbol symbol, Func<Symbol, bool> isExcludeSymbol)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  


***  

## `FireSymbolUpdatedEvent<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void FireSymbolUpdatedEvent(Symbol symbol)
```
`Action` <mark style="color:red;">*`new`*</mark>  
 *Описание*  

`SymbolManager` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `Get<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Symbol Get(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Get<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Symbol Get(string id)
public static Symbol[] Get(params string[] ids)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`string` <mark style="color:red;">*`params`*</mark>  
 *Описание*  


***  

## `GetAll<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Symbol> GetAll(bool includeDeleted = false)
```
`includeDeleted` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetAllOptions<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Symbol> GetAllOptions()
```

***  

## `LoadOrUpdate<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void LoadOrUpdate(byte[] data, DateTime utcSpecChangedTime)
```

`utcSpecChangedTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `RiseFavoritesReady<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void RiseFavoritesReady()
```

***  

## `RiseSymbolsReady<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void RiseSymbolsReady()
```

***  
***  
 ***  
# Свойства

## `ClientSpecLastUpdate`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime ClientSpecLastUpdate { get; set; }
```  
***
***  
 ***  
# События

## `Action`
Описание

```csharp
public static event Action SymbolsReady
```

## `Action`
Описание

```csharp
public static event Action FavoritesReady
```

## `Action`
Описание

```csharp
public static event Action BunchOfOptionsUpdated
```

## `SymbolUpdated;`
Описание

```csharp
public static event Action<Symbol> SymbolUpdated;
```

