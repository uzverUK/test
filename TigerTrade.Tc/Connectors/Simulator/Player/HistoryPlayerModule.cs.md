
`namespace` [TigerTrade.Tc](../../../../TigerTrade.Tc.md).[Connectors](../../../../TigerTrade.Tc/Connectors.md).[Simulator](../../../../TigerTrade.Tc/Connectors/Simulator.md).[Player](../../../../TigerTrade.Tc/Connectors/Simulator/Player.md)


Описание

### Синтаксис
```csharp
public static class HistoryPlayerModule
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](./HistoryPlayerModule.cs/Методы/Clear.md) | *Описание* |
| [`GetState`](./HistoryPlayerModule.cs/Методы/GetState.md) | *Описание* |
| [`GetStats`](./HistoryPlayerModule.cs/Методы/GetStats.md) | *Описание* |
| [`Init`](./HistoryPlayerModule.cs/Методы/Init.md) | *Описание* |
| [`Pause`](./HistoryPlayerModule.cs/Методы/Pause.md) | *Описание* |
| [`Play`](./HistoryPlayerModule.cs/Методы/Play.md) | *Описание* |
| [`SetSpeed`](./HistoryPlayerModule.cs/Методы/SetSpeed.md) | *Описание* |
| [`Skip`](./HistoryPlayerModule.cs/Методы/Skip.md) | *Описание* |
| [`SkipTo`](./HistoryPlayerModule.cs/Методы/SkipTo.md) | *Описание* |
| [`Stop`](./HistoryPlayerModule.cs/Методы/Stop.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`RecordDate`](./HistoryPlayerModule.cs/Свойства/RecordDate.md) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`StateChanged;`](./HistoryPlayerModule.cs/События/StateChanged;.md) | *Описание* |
| [`StatsChanged;`](./HistoryPlayerModule.cs/События/StatsChanged;.md) | *Описание* |





***  
***  
# Методы

## `Clear`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Clear()
```

***  

## `GetState`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static HistoryPlayerState GetState()
```

***  

## `GetStats`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<HistoryPlayerStats> GetStats()
```

***  

## `Init`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Init(DateTime date, string[] files)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `Init`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Init(DateTime date, string[] files)
public static void Init(DateTime date, List<Tuple<Symbol, byte[]>> records)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `Pause`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Pause()
```

***  

## `Play`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Play()
```

***  

## `SetSpeed`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetSpeed(int speed)
```

`speed` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `Skip`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Skip(int seconds)
```
`seconds` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `SkipTo`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SkipTo(TimeSpan time)
```
`time` <mark style="color:red;">*`TimeSpan`*</mark>  
 *Описание*  


***  

## `Stop`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Stop()
```

***  
***  
 ***  
# Свойства

## `RecordDate`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime RecordDate { get; private set; }
```  
***
***  
 ***  
# События

## `StateChanged;`
Описание

```csharp
public static event Action<HistoryPlayerState> StateChanged;
```

## `StatsChanged;`
Описание

```csharp
public static event Action<HistoryPlayerStats> StatsChanged;
```

