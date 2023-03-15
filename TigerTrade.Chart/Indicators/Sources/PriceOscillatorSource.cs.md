
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class PriceOscillatorSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./PriceOscillatorSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./PriceOscillatorSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./PriceOscillatorSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`PriceOscillatorSource`](./PriceOscillatorSource.cs/Методы/PriceOscillatorSource.md) | *Описание* |
| [`ToString`](./PriceOscillatorSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`LongPeriod`](./PriceOscillatorSource.cs/Свойства/LongPeriod.md) | *Описание* |
| [`MaType`](./PriceOscillatorSource.cs/Свойства/MaType.md) | *Описание* |
| [`ShortPeriod`](./PriceOscillatorSource.cs/Свойства/ShortPeriod.md) | *Описание* |
| [`Source`](./PriceOscillatorSource.cs/Свойства/Source.md) | *Описание* |





# Методы

## `CopySettings`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

<mark style="color:purple;">`source`</mark> <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  



## `GetSeries`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```
<mark style="color:purple;">`helper`</mark> <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  



## `GetSeriesList`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override IEnumerable<string> GetSeriesList()
```
<mark style="color:purple;">`List`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  



## `PriceOscillatorSource`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public PriceOscillatorSource()
```


## `ToString`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

<mark style="color:purple;">`object`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  


# Свойства

## `LongPeriod`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LongPeriod { get; set; }
```

## `MaType`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorMaType MaType { get; set; }
```

## `ShortPeriod`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int ShortPeriod { get; set; }
```

## `Source`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSourceBase Source { get; set; }
```

