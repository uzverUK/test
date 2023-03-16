
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


Описание

### Синтаксис
```csharp
public static class SymbolManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#Clear-m) | *Описание* |
| [`FindSwitchPair`](#FindSwitchPair-m) | *Описание* |
| [`FireSymbolUpdatedEvent`](#FireSymbolUpdatedEvent-m) | *Описание* |
| [`Get`](#Get-m) | *Описание* |
| [`GetAll`](#GetAll-m) | *Описание* |
| [`GetAllOptions`](#GetAllOptions-m) | *Описание* |
| [`LoadOrUpdate`](#LoadOrUpdate-m) | *Описание* |
| [`RiseFavoritesReady`](#RiseFavoritesReady-m) | *Описание* |
| [`RiseSymbolsReady`](#RiseSymbolsReady-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ClientSpecLastUpdate`](#ClientSpecLastUpdate-p) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`Action`](#Action-p) | *Описание* |
| [`Action`](#Action-p) | *Описание* |
| [`Action`](#Action-p) | *Описание* |
| [`SymbolUpdated;`](#SymbolUpdated;-p) | *Описание* |





***  
***  
# Методы

## `Clear`<a href="RiseSymbolsReady-m" id="RiseSymbolsReady-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Clear()
```

***  

## `FindSwitchPair`<a href="RiseSymbolsReady-m" id="RiseSymbolsReady-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Symbol FindSwitchPair(Symbol symbol, Func<Symbol, bool> isExcludeSymbol)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  


***  

## `FireSymbolUpdatedEvent`<a href="RiseSymbolsReady-m" id="RiseSymbolsReady-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void FireSymbolUpdatedEvent(Symbol symbol)
```
`Action` <mark style="color:red;">*`new`*</mark>  
 *Описание*  

`SymbolManager` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `Get`<a href="RiseSymbolsReady-m" id="RiseSymbolsReady-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Symbol Get(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Get`<a href="RiseSymbolsReady-m" id="RiseSymbolsReady-m"></a>
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

## `GetAll`<a href="RiseSymbolsReady-m" id="RiseSymbolsReady-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Symbol> GetAll(bool includeDeleted = false)
```
`includeDeleted` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetAllOptions`<a href="RiseSymbolsReady-m" id="RiseSymbolsReady-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Symbol> GetAllOptions()
```

***  

## `LoadOrUpdate`<a href="RiseSymbolsReady-m" id="RiseSymbolsReady-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void LoadOrUpdate(byte[] data, DateTime utcSpecChangedTime)
```

`utcSpecChangedTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `RiseFavoritesReady`<a href="RiseSymbolsReady-m" id="RiseSymbolsReady-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void RiseFavoritesReady()
```

***  

## `RiseSymbolsReady`<a href="RiseSymbolsReady-m" id="RiseSymbolsReady-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void RiseSymbolsReady()
```

***  
***  
 ***  
# Свойства

## `ClientSpecLastUpdate`<a href="ClientSpecLastUpdate-p" id="ClientSpecLastUpdate-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime ClientSpecLastUpdate { get; set; }
```  
***
***  
 ***  
# События

## `Action`<a href="SymbolUpdated;-p" id="SymbolUpdated;-p"></a>
Описание

```csharp
public static event Action SymbolsReady
```

## `Action`<a href="SymbolUpdated;-p" id="SymbolUpdated;-p"></a>
Описание

```csharp
public static event Action FavoritesReady
```

## `Action`<a href="SymbolUpdated;-p" id="SymbolUpdated;-p"></a>
Описание

```csharp
public static event Action BunchOfOptionsUpdated
```

## `SymbolUpdated;`<a href="SymbolUpdated;-p" id="SymbolUpdated;-p"></a>
Описание

```csharp
public static event Action<Symbol> SymbolUpdated;
```

