
`namespace` [TigerTrade.Tc](../../../../TigerTrade.Tc.md).[Connectors](../../../../TigerTrade.Tc/Connectors.md).[Simulator](../../../../TigerTrade.Tc/Connectors/Simulator.md).[Player](../../../../TigerTrade.Tc/Connectors/Simulator/Player.md)


Описание

### Синтаксис
```csharp
public static class HistoryPlayerModule
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#test) | *Описание* |
| [`GetState`](#test) | *Описание* |
| [`GetStats`](#test) | *Описание* |
| [`Init`](#test) | *Описание* |
| [`Pause`](#test) | *Описание* |
| [`Play`](#test) | *Описание* |
| [`SetSpeed`](#test) | *Описание* |
| [`Skip`](#test) | *Описание* |
| [`SkipTo`](#test) | *Описание* |
| [`Stop`](#test) | *Описание* |

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

## `Clear`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Clear()
```

***  

## `GetState`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static HistoryPlayerState GetState()
```

***  

## `GetStats`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<HistoryPlayerStats> GetStats()
```

***  

## `Init`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Init(DateTime date, string[] files)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `Init`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Init(DateTime date, string[] files)
public static void Init(DateTime date, List<Tuple<Symbol, byte[]>> records)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `Pause`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Pause()
```

***  

## `Play`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Play()
```

***  

## `SetSpeed`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetSpeed(int speed)
```

`speed` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `Skip`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Skip(int seconds)
```
`seconds` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `SkipTo`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SkipTo(TimeSpan time)
```
`time` <mark style="color:red;">*`TimeSpan`*</mark>  
 *Описание*  


***  

## `Stop`<a href="test" id="test"></a>
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

