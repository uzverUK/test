# HistoryPlayerModule

`namespace` [TigerTrade.Tc](../../../).[Connectors](../../).[Simulator](../).[Player](./)

\===

#### Синтаксис

```csharp
public static class HistoryPlayerModule
```

## Список методов

| Название                                                | Описание |
| ------------------------------------------------------- | -------- |
| [`Clear`](historyplayermodule.cs.md#method-clear)       | _===_    |
| [`GetState`](historyplayermodule.cs.md#method-getstate) | _===_    |
| [`GetStats`](historyplayermodule.cs.md#method-getstats) | _===_    |
| [`Init`](historyplayermodule.cs.md#method-init)         | _===_    |
| [`Pause`](historyplayermodule.cs.md#method-pause)       | _===_    |
| [`Play`](historyplayermodule.cs.md#method-play)         | _===_    |
| [`SetSpeed`](historyplayermodule.cs.md#method-setspeed) | _===_    |
| [`Skip`](historyplayermodule.cs.md#method-skip)         | _===_    |
| [`SkipTo`](historyplayermodule.cs.md#method-skipto)     | _===_    |
| [`Stop`](historyplayermodule.cs.md#method-stop)         | _===_    |

## Список свойств

| Название                                                      | Описание |
| ------------------------------------------------------------- | -------- |
| [`RecordDate`](historyplayermodule.cs.md#property-recorddate) | _===_    |

## Список событий

| Название                                                         | Описание |
| ---------------------------------------------------------------- | -------- |
| [`StateChanged;`](historyplayermodule.cs.md#event-statechanged;) | _===_    |
| [`StatsChanged;`](historyplayermodule.cs.md#event-statschanged;) | _===_    |

***

***

## Методы

### `Clear` <a href="#method-clear" id="method-clear"></a>

\===

```csharp
public static void Clear()
```

***

### `GetState` <a href="#method-getstate" id="method-getstate"></a>

\===

```csharp
public static HistoryPlayerState GetState()
```

***

### `GetStats` <a href="#method-getstats" id="method-getstats"></a>

\===

```csharp
public static List<HistoryPlayerStats> GetStats()
```

***

### `Init` <a href="#method-init" id="method-init"></a>

\===

```csharp
public static void Init(DateTime date, string[] files)
```

`date` _<mark style="color:red;">`DateTime`</mark>_\
_===_

***

### `Init` <a href="#method-init" id="method-init"></a>

\===

```csharp
public static void Init(DateTime date, string[] files)
public static void Init(DateTime date, List<Tuple<Symbol, byte[]>> records)
```

`date` _<mark style="color:red;">`DateTime`</mark>_\
_===_

***

### `Pause` <a href="#method-pause" id="method-pause"></a>

\===

```csharp
public static void Pause()
```

***

### `Play` <a href="#method-play" id="method-play"></a>

\===

```csharp
public static void Play()
```

***

### `SetSpeed` <a href="#method-setspeed" id="method-setspeed"></a>

\===

```csharp
public static void SetSpeed(int speed)
```

`speed` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `Skip` <a href="#method-skip" id="method-skip"></a>

\===

```csharp
public static void Skip(int seconds)
```

`seconds` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `SkipTo` <a href="#method-skipto" id="method-skipto"></a>

\===

```csharp
public static void SkipTo(TimeSpan time)
```

`time` _<mark style="color:red;">`TimeSpan`</mark>_\
_===_

***

### `Stop` <a href="#method-stop" id="method-stop"></a>

\===

```csharp
public static void Stop()
```

***

***

***

## Свойства

### `RecordDate` <a href="#property-recorddate" id="property-recorddate"></a>

\===

```csharp
public static DateTime RecordDate { get; private set; }
```

***

***

***

## События

### `StateChanged;` <a href="#event-statechanged" id="event-statechanged"></a>

\===

```csharp
public static event Action<HistoryPlayerState> StateChanged;
```

### `StatsChanged;` <a href="#event-statschanged" id="event-statschanged"></a>

\===

```csharp
public static event Action<HistoryPlayerStats> StatsChanged;
```
