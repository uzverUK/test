
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class VolumeOscillatorSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./VolumeOscillatorSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./VolumeOscillatorSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./VolumeOscillatorSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./VolumeOscillatorSource.cs/Методы/ToString.md) | *Описание* |
| [`VolumeOscillatorSource`](./VolumeOscillatorSource.cs/Методы/VolumeOscillatorSource.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`LongPeriod`](./VolumeOscillatorSource.cs/Свойства/LongPeriod.md) | *Описание* |
| [`MaType`](./VolumeOscillatorSource.cs/Свойства/MaType.md) | *Описание* |
| [`ShortPeriod`](./VolumeOscillatorSource.cs/Свойства/ShortPeriod.md) | *Описание* |





# Методы

## *CopySettings*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

<mark style="color:yellow;">`source`</mark> <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  



## *GetSeries*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```
<mark style="color:yellow;">`helper`</mark> <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  



## *GetSeriesList*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override IEnumerable<string> GetSeriesList()
```
<mark style="color:yellow;">`List`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  



## *ToString*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```


## *VolumeOscillatorSource*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public VolumeOscillatorSource()
```

# Свойства

## *LongPeriod*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LongPeriod { get; set; }
```

## *MaType*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorMaType MaType { get; set; }
```

## *ShortPeriod*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int ShortPeriod { get; set; }
```

