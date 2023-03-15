
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class CandlePatternSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CandlePatternSource`](./CandlePatternSource.cs/Методы/CandlePatternSource.md) | *Описание* |
| [`CopySettings`](./CandlePatternSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./CandlePatternSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./CandlePatternSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`SearchPattern`](./CandlePatternSource.cs/Методы/SearchPattern.md) | *Описание* |
| [`ToString`](./CandlePatternSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`PatternType`](./CandlePatternSource.cs/Свойства/PatternType.md) | *Описание* |
| [`Penetration`](./CandlePatternSource.cs/Свойства/Penetration.md) | *Описание* |





# Методы

## `CandlePatternSource`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public CandlePatternSource()
```


## `CopySettings`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

`source` <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  



## `GetSeries`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  



## `GetSeriesList`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override IEnumerable<string> GetSeriesList()
```
`List` <mark style="color:red;">*`new`*</mark>  
 *Описание*  



## `SearchPattern`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] SearchPattern(IndicatorsHelper helper, CandlePatternSourcePatternType type)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  

`type` <mark style="color:red;">*`CandlePatternSourcePatternType`*</mark>  
 *Описание*  



## `ToString`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

# Свойства

## `PatternType`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public CandlePatternSourcePatternType PatternType { get; set; }
```

## `Penetration`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Penetration { get; set; }
```

