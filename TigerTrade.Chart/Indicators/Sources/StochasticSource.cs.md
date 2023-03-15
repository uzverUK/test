
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class StochasticSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./StochasticSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./StochasticSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./StochasticSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`StochasticSource`](./StochasticSource.cs/Методы/StochasticSource.md) | *Описание* |
| [`ToString`](./StochasticSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`FastK`](./StochasticSource.cs/Свойства/FastK.md) | *Описание* |
| [`SlowD`](./StochasticSource.cs/Свойства/SlowD.md) | *Описание* |
| [`SlowDMaType`](./StochasticSource.cs/Свойства/SlowDMaType.md) | *Описание* |
| [`Smooth`](./StochasticSource.cs/Свойства/Smooth.md) | *Описание* |





# Методы

## `CopySettings`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

`source` <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  



## `GetSeries`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  



## `GetSeriesList`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override IEnumerable<string> GetSeriesList()
```
`List` <mark style="color:red;">*`new`*</mark>  
 *Описание*  



## `StochasticSource`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public StochasticSource()
```


## `ToString`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

# Свойства

## `FastK`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int FastK { get; set; }
```

## `SlowD`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int SlowD { get; set; }
```

## `SlowDMaType`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorMaType SlowDMaType { get; set; }
```

## `Smooth`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Smooth { get; set; }
```

