# SymbolManager

`namespace` [TigerTrade.Tc](../).[Manager](./)

\===

#### Синтаксис

```csharp
public static class SymbolManager
```

## Список методов

| Название                                                                      | Описание |
| ----------------------------------------------------------------------------- | -------- |
| [`Clear`](symbolmanager.cs.md#method-clear)                                   | _===_    |
| [`FindSwitchPair`](symbolmanager.cs.md#method-findswitchpair)                 | _===_    |
| [`FireSymbolUpdatedEvent`](symbolmanager.cs.md#method-firesymbolupdatedevent) | _===_    |
| [`Get`](symbolmanager.cs.md#method-get)                                       | _===_    |
| [`GetAll`](symbolmanager.cs.md#method-getall)                                 | _===_    |
| [`GetAllOptions`](symbolmanager.cs.md#method-getalloptions)                   | _===_    |
| [`LoadOrUpdate`](symbolmanager.cs.md#method-loadorupdate)                     | _===_    |
| [`RiseFavoritesReady`](symbolmanager.cs.md#method-risefavoritesready)         | _===_    |
| [`RiseSymbolsReady`](symbolmanager.cs.md#method-risesymbolsready)             | _===_    |

## Список свойств

| Название                                                                    | Описание |
| --------------------------------------------------------------------------- | -------- |
| [`ClientSpecLastUpdate`](symbolmanager.cs.md#property-clientspeclastupdate) | _===_    |

## Список событий

| Название                                                     | Описание |
| ------------------------------------------------------------ | -------- |
| [`Action`](symbolmanager.cs.md#event-action)                 | _===_    |
| [`Action`](symbolmanager.cs.md#event-action)                 | _===_    |
| [`Action`](symbolmanager.cs.md#event-action)                 | _===_    |
| [`SymbolUpdated;`](symbolmanager.cs.md#event-symbolupdated;) | _===_    |

***

***

## Методы

### `Clear` <a href="#method-clear" id="method-clear"></a>

\===

```csharp
public static void Clear()
```

***

### `FindSwitchPair` <a href="#method-findswitchpair" id="method-findswitchpair"></a>

\===

```csharp
public static Symbol FindSwitchPair(Symbol symbol, Func<Symbol, bool> isExcludeSymbol)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

***

### `FireSymbolUpdatedEvent` <a href="#method-firesymbolupdatedevent" id="method-firesymbolupdatedevent"></a>

\===

```csharp
public static void FireSymbolUpdatedEvent(Symbol symbol)
```

`Action` _<mark style="color:red;">`new`</mark>_\
_===_

`SymbolManager` _<mark style="color:red;">`new`</mark>_\
_===_

***

### `Get` <a href="#method-get" id="method-get"></a>

\===

```csharp
public static Symbol Get(string id)
```

`id` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `Get` <a href="#method-get" id="method-get"></a>

\===

```csharp
public static Symbol Get(string id)
public static Symbol[] Get(params string[] ids)
```

`id` _<mark style="color:red;">`string`</mark>_\
_===_

`string` _<mark style="color:red;">`params`</mark>_\
_===_

***

### `GetAll` <a href="#method-getall" id="method-getall"></a>

\===

```csharp
public static List<Symbol> GetAll(bool includeDeleted = false)
```

`includeDeleted` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `GetAllOptions` <a href="#method-getalloptions" id="method-getalloptions"></a>

\===

```csharp
public static List<Symbol> GetAllOptions()
```

***

### `LoadOrUpdate` <a href="#method-loadorupdate" id="method-loadorupdate"></a>

\===

```csharp
public static void LoadOrUpdate(byte[] data, DateTime utcSpecChangedTime)
```

`utcSpecChangedTime` _<mark style="color:red;">`DateTime`</mark>_\
_===_

***

### `RiseFavoritesReady` <a href="#method-risefavoritesready" id="method-risefavoritesready"></a>

\===

```csharp
public static void RiseFavoritesReady()
```

***

### `RiseSymbolsReady` <a href="#method-risesymbolsready" id="method-risesymbolsready"></a>

\===

```csharp
public static void RiseSymbolsReady()
```

***

***

***

## Свойства

### `ClientSpecLastUpdate` <a href="#property-clientspeclastupdate" id="property-clientspeclastupdate"></a>

\===

```csharp
public static DateTime ClientSpecLastUpdate { get; set; }
```

***

***

***

## События

### `Action` <a href="#event-action" id="event-action"></a>

\===

```csharp
public static event Action SymbolsReady
```

### `Action` <a href="#event-action" id="event-action"></a>

\===

```csharp
public static event Action FavoritesReady
```

### `Action` <a href="#event-action" id="event-action"></a>

\===

```csharp
public static event Action BunchOfOptionsUpdated
```

### `SymbolUpdated;` <a href="#event-symbolupdated" id="event-symbolupdated"></a>

\===

```csharp
public static event Action<Symbol> SymbolUpdated;
```
