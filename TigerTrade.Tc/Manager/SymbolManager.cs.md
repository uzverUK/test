
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


===

### Синтаксис
```csharp
public static class SymbolManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#method-clear) | *===* |
| [`FindSwitchPair`](#method-findswitchpair) | *===* |
| [`FireSymbolUpdatedEvent`](#method-firesymbolupdatedevent) | *===* |
| [`Get`](#method-get) | *===* |
| [`GetAll`](#method-getall) | *===* |
| [`GetAllOptions`](#method-getalloptions) | *===* |
| [`LoadOrUpdate`](#method-loadorupdate) | *===* |
| [`RiseFavoritesReady`](#method-risefavoritesready) | *===* |
| [`RiseSymbolsReady`](#method-risesymbolsready) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ClientSpecLastUpdate`](#property-clientspeclastupdate) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`Action`](#event-action) | *===* |
| [`Action`](#event-action) | *===* |
| [`Action`](#event-action) | *===* |
| [`SymbolUpdated;`](#event-symbolupdated;) | *===* |





***  
***  
# Методы

## `Clear`<a href="method-clear" id="method-clear"></a>
===
```csharp
public static void Clear()
```

***  

## `FindSwitchPair`<a href="method-findswitchpair" id="method-findswitchpair"></a>
===
```csharp
public static Symbol FindSwitchPair(Symbol symbol, Func<Symbol, bool> isExcludeSymbol)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  


***  

## `FireSymbolUpdatedEvent`<a href="method-firesymbolupdatedevent" id="method-firesymbolupdatedevent"></a>
===
```csharp
public static void FireSymbolUpdatedEvent(Symbol symbol)
```
`Action` <mark style="color:red;">*`new`*</mark>  
 *===*  

`SymbolManager` <mark style="color:red;">*`new`*</mark>  
 *===*  


***  

## `Get`<a href="method-get" id="method-get"></a>
===
```csharp
public static Symbol Get(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `Get`<a href="method-get" id="method-get"></a>
===
```csharp
public static Symbol Get(string id)
public static Symbol[] Get(params string[] ids)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *===*  

`string` <mark style="color:red;">*`params`*</mark>  
 *===*  


***  

## `GetAll`<a href="method-getall" id="method-getall"></a>
===
```csharp
public static List<Symbol> GetAll(bool includeDeleted = false)
```
`includeDeleted` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `GetAllOptions`<a href="method-getalloptions" id="method-getalloptions"></a>
===
```csharp
public static List<Symbol> GetAllOptions()
```

***  

## `LoadOrUpdate`<a href="method-loadorupdate" id="method-loadorupdate"></a>
===
```csharp
public static void LoadOrUpdate(byte[] data, DateTime utcSpecChangedTime)
```

`utcSpecChangedTime` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  


***  

## `RiseFavoritesReady`<a href="method-risefavoritesready" id="method-risefavoritesready"></a>
===
```csharp
public static void RiseFavoritesReady()
```

***  

## `RiseSymbolsReady`<a href="method-risesymbolsready" id="method-risesymbolsready"></a>
===
```csharp
public static void RiseSymbolsReady()
```

***  
***  
 ***  
# Свойства

## `ClientSpecLastUpdate`<a href="property-clientspeclastupdate" id="property-clientspeclastupdate"></a>
===
```csharp
public static DateTime ClientSpecLastUpdate { get; set; }
```  
***
***  
 ***  
# События

## `Action`<a href="event-action" id="event-action"></a>
===

```csharp
public static event Action SymbolsReady
```

## `Action`<a href="event-action" id="event-action"></a>
===

```csharp
public static event Action FavoritesReady
```

## `Action`<a href="event-action" id="event-action"></a>
===

```csharp
public static event Action BunchOfOptionsUpdated
```

## `SymbolUpdated;`<a href="event-symbolupdated;" id="event-symbolupdated;"></a>
===

```csharp
public static event Action<Symbol> SymbolUpdated;
```

