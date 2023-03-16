
`namespace` [TigerTrade.Tc](../../../../TigerTrade.Tc.md).[Connectors](../../../../TigerTrade.Tc/Connectors.md).[Simulator](../../../../TigerTrade.Tc/Connectors/Simulator.md).[Player](../../../../TigerTrade.Tc/Connectors/Simulator/Player.md)


Описание

### Синтаксис
```csharp
public static class HistoryPlayerModule
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#Clear-m) | *Описание* |
| [`GetState`](#GetState-m) | *Описание* |
| [`GetStats`](#GetStats-m) | *Описание* |
| [`Init`](#Init-m) | *Описание* |
| [`Pause`](#Pause-m) | *Описание* |
| [`Play`](#Play-m) | *Описание* |
| [`SetSpeed`](#SetSpeed-m) | *Описание* |
| [`Skip`](#Skip-m) | *Описание* |
| [`SkipTo`](#SkipTo-m) | *Описание* |
| [`Stop`](#Stop-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`RecordDate`](#RecordDate-p) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`StateChanged;`](#StateChanged;-p) | *Описание* |
| [`StatsChanged;`](#StatsChanged;-p) | *Описание* |





***  
***  
# Методы

## `Clear`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Clear()
```

***  

## `GetState`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static HistoryPlayerState GetState()
```

***  

## `GetStats`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<HistoryPlayerStats> GetStats()
```

***  

## `Init`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Init(DateTime date, string[] files)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `Init`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Init(DateTime date, string[] files)
public static void Init(DateTime date, List<Tuple<Symbol, byte[]>> records)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `Pause`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Pause()
```

***  

## `Play`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Play()
```

***  

## `SetSpeed`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetSpeed(int speed)
```

`speed` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `Skip`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Skip(int seconds)
```
`seconds` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `SkipTo`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SkipTo(TimeSpan time)
```
`time` <mark style="color:red;">*`TimeSpan`*</mark>  
 *Описание*  


***  

## `Stop`<a href="Stop-m" id="Stop-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Stop()
```

***  
***  
 ***  
# Свойства

## `RecordDate`<a href="RecordDate-p" id="RecordDate-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static DateTime RecordDate { get; private set; }
```  
***
***  
 ***  
# События

## `StateChanged;`<a href="StatsChanged;-p" id="StatsChanged;-p"></a>
Описание

```csharp
public static event Action<HistoryPlayerState> StateChanged;
```

## `StatsChanged;`<a href="StatsChanged;-p" id="StatsChanged;-p"></a>
Описание

```csharp
public static event Action<HistoryPlayerStats> StatsChanged;
```

