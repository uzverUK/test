
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


Описание

### Синтаксис
```csharp
public static class SymbolManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#method-clear) | *Описание* |
| [`FindSwitchPair`](#method-findswitchpair) | *Описание* |
| [`FireSymbolUpdatedEvent`](#method-firesymbolupdatedevent) | *Описание* |
| [`Get`](#method-get) | *Описание* |
| [`GetAll`](#method-getall) | *Описание* |
| [`GetAllOptions`](#method-getalloptions) | *Описание* |
| [`LoadOrUpdate`](#method-loadorupdate) | *Описание* |
| [`RiseFavoritesReady`](#method-risefavoritesready) | *Описание* |
| [`RiseSymbolsReady`](#method-risesymbolsready) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ClientSpecLastUpdate`](#property-clientspeclastupdate) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`Action`](#event-action) | *Описание* |
| [`Action`](#event-action) | *Описание* |
| [`Action`](#event-action) | *Описание* |
| [`SymbolUpdated;`](#event-symbolupdated;) | *Описание* |





***  
***  
# Методы

## `Clear`<a href="method-clear" id="method-clear"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Clear()
```

***  

## `FindSwitchPair`<a href="method-findswitchpair" id="method-findswitchpair"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Symbol FindSwitchPair(Symbol symbol, Func<Symbol, bool> isExcludeSymbol)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  


***  

## `FireSymbolUpdatedEvent`<a href="method-firesymbolupdatedevent" id="method-firesymbolupdatedevent"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void FireSymbolUpdatedEvent(Symbol symbol)
```
`Action` <mark style="color:red;">*`new`*</mark>  
 *Описание*  

`SymbolManager` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `Get`<a href="method-get" id="method-get"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Symbol Get(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Get`<a href="method-get" id="method-get"></a>
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

## `GetAll`<a href="method-getall" id="method-getall"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Symbol> GetAll(bool includeDeleted = false)
```
`includeDeleted` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetAllOptions`<a href="method-getalloptions" id="method-getalloptions"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Symbol> GetAllOptions()
```

***  

## `LoadOrUpdate`<a href="method-loadorupdate" id="method-loadorupdate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void LoadOrUpdate(byte[] data, DateTime utcSpecChangedTime)
```

`utcSpecChangedTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `RiseFavoritesReady`<a href="method-risefavoritesready" id="method-risefavoritesready"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void RiseFavoritesReady()
```

***  

## `RiseSymbolsReady`<a href="method-risesymbolsready" id="method-risesymbolsready"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void RiseSymbolsReady()
```

***  
***  
 ***  
# Свойства

## `ClientSpecLastUpdate`<a href="property-clientspeclastupdate" id="property-clientspeclastupdate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime ClientSpecLastUpdate { get; set; }
```  
***
***  
 ***  
# События

## `Action`<a href="event-action" id="event-action"></a>
Описание

```csharp
public static event Action SymbolsReady
```

## `Action`<a href="event-action" id="event-action"></a>
Описание

```csharp
public static event Action FavoritesReady
```

## `Action`<a href="event-action" id="event-action"></a>
Описание

```csharp
public static event Action BunchOfOptionsUpdated
```

## `SymbolUpdated;`<a href="event-symbolupdated;" id="event-symbolupdated;"></a>
Описание

```csharp
public static event Action<Symbol> SymbolUpdated;
```

