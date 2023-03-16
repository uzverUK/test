
`namespace` [TigerTrade.Tc](../../../../TigerTrade.Tc.md).[Connectors](../../../../TigerTrade.Tc/Connectors.md).[Simulator](../../../../TigerTrade.Tc/Connectors/Simulator.md).[Player](../../../../TigerTrade.Tc/Connectors/Simulator/Player.md)


Описание

### Синтаксис
```csharp
public static class HistoryPlayerModule
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#method-clear) | *Описание* |
| [`GetState`](#method-getstate) | *Описание* |
| [`GetStats`](#method-getstats) | *Описание* |
| [`Init`](#method-init) | *Описание* |
| [`Pause`](#method-pause) | *Описание* |
| [`Play`](#method-play) | *Описание* |
| [`SetSpeed`](#method-setspeed) | *Описание* |
| [`Skip`](#method-skip) | *Описание* |
| [`SkipTo`](#method-skipto) | *Описание* |
| [`Stop`](#method-stop) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`RecordDate`](#property-recorddate) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`StateChanged;`](#event-statechanged;) | *Описание* |
| [`StatsChanged;`](#event-statschanged;) | *Описание* |





***  
***  
# Методы

## `Clear`<a href="method-clear" id="method-clear"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Clear()
```

***  

## `GetState`<a href="method-getstate" id="method-getstate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static HistoryPlayerState GetState()
```

***  

## `GetStats`<a href="method-getstats" id="method-getstats"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<HistoryPlayerStats> GetStats()
```

***  

## `Init`<a href="method-init" id="method-init"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Init(DateTime date, string[] files)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `Init`<a href="method-init" id="method-init"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Init(DateTime date, string[] files)
public static void Init(DateTime date, List<Tuple<Symbol, byte[]>> records)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `Pause`<a href="method-pause" id="method-pause"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Pause()
```

***  

## `Play`<a href="method-play" id="method-play"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Play()
```

***  

## `SetSpeed`<a href="method-setspeed" id="method-setspeed"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetSpeed(int speed)
```

`speed` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `Skip`<a href="method-skip" id="method-skip"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Skip(int seconds)
```
`seconds` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `SkipTo`<a href="method-skipto" id="method-skipto"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SkipTo(TimeSpan time)
```
`time` <mark style="color:red;">*`TimeSpan`*</mark>  
 *Описание*  


***  

## `Stop`<a href="method-stop" id="method-stop"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Stop()
```

***  
***  
 ***  
# Свойства

## `RecordDate`<a href="property-recorddate" id="property-recorddate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime RecordDate { get; private set; }
```  
***
***  
 ***  
# События

## `StateChanged;`<a href="event-statechanged;" id="event-statechanged;"></a>
Описание

```csharp
public static event Action<HistoryPlayerState> StateChanged;
```

## `StatsChanged;`<a href="event-statschanged;" id="event-statschanged;"></a>
Описание

```csharp
public static event Action<HistoryPlayerStats> StatsChanged;
```

