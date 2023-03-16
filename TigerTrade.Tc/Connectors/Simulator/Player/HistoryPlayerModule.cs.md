
`namespace` [TigerTrade.Tc](../../../../TigerTrade.Tc.md).[Connectors](../../../../TigerTrade.Tc/Connectors.md).[Simulator](../../../../TigerTrade.Tc/Connectors/Simulator.md).[Player](../../../../TigerTrade.Tc/Connectors/Simulator/Player.md)


===

### Синтаксис
```csharp
public static class HistoryPlayerModule
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#method-clear) | *===* |
| [`GetState`](#method-getstate) | *===* |
| [`GetStats`](#method-getstats) | *===* |
| [`Init`](#method-init) | *===* |
| [`Pause`](#method-pause) | *===* |
| [`Play`](#method-play) | *===* |
| [`SetSpeed`](#method-setspeed) | *===* |
| [`Skip`](#method-skip) | *===* |
| [`SkipTo`](#method-skipto) | *===* |
| [`Stop`](#method-stop) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`RecordDate`](#property-recorddate) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`StateChanged;`](#event-statechanged;) | *===* |
| [`StatsChanged;`](#event-statschanged;) | *===* |





***  
***  
# Методы

## `Clear`<a href="method-clear" id="method-clear"></a>
===
```csharp
public static void Clear()
```

***  

## `GetState`<a href="method-getstate" id="method-getstate"></a>
===
```csharp
public static HistoryPlayerState GetState()
```

***  

## `GetStats`<a href="method-getstats" id="method-getstats"></a>
===
```csharp
public static List<HistoryPlayerStats> GetStats()
```

***  

## `Init`<a href="method-init" id="method-init"></a>
===
```csharp
public static void Init(DateTime date, string[] files)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  


***  

## `Init`<a href="method-init" id="method-init"></a>
===
```csharp
public static void Init(DateTime date, string[] files)
public static void Init(DateTime date, List<Tuple<Symbol, byte[]>> records)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  


***  

## `Pause`<a href="method-pause" id="method-pause"></a>
===
```csharp
public static void Pause()
```

***  

## `Play`<a href="method-play" id="method-play"></a>
===
```csharp
public static void Play()
```

***  

## `SetSpeed`<a href="method-setspeed" id="method-setspeed"></a>
===
```csharp
public static void SetSpeed(int speed)
```

`speed` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `Skip`<a href="method-skip" id="method-skip"></a>
===
```csharp
public static void Skip(int seconds)
```
`seconds` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `SkipTo`<a href="method-skipto" id="method-skipto"></a>
===
```csharp
public static void SkipTo(TimeSpan time)
```
`time` <mark style="color:red;">*`TimeSpan`*</mark>  
 *===*  


***  

## `Stop`<a href="method-stop" id="method-stop"></a>
===
```csharp
public static void Stop()
```

***  
***  
 ***  
# Свойства

## `RecordDate`<a href="property-recorddate" id="property-recorddate"></a>
===
```csharp
public static DateTime RecordDate { get; private set; }
```  
***
***  
 ***  
# События

## `StateChanged;`<a href="event-statechanged;" id="event-statechanged;"></a>
===

```csharp
public static event Action<HistoryPlayerState> StateChanged;
```

## `StatsChanged;`<a href="event-statschanged;" id="event-statschanged;"></a>
===

```csharp
public static event Action<HistoryPlayerStats> StatsChanged;
```

