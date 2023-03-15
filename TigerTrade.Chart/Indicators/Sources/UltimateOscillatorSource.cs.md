
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class UltimateOscillatorSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./UltimateOscillatorSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./UltimateOscillatorSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./UltimateOscillatorSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./UltimateOscillatorSource.cs/Методы/ToString.md) | *Описание* |
| [`UltimateOscillatorSource`](./UltimateOscillatorSource.cs/Методы/UltimateOscillatorSource.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Period1`](./UltimateOscillatorSource.cs/Свойства/Period1.md) | *Описание* |
| [`Period2`](./UltimateOscillatorSource.cs/Свойства/Period2.md) | *Описание* |
| [`Period3`](./UltimateOscillatorSource.cs/Свойства/Period3.md) | *Описание* |





# Методы

## *CopySettings*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

<mark style="color:purple;">`source`</mark> <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  



## *GetSeries*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```
<mark style="color:purple;">`helper`</mark> <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  



## *GetSeriesList*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override IEnumerable<string> GetSeriesList()
```
<mark style="color:purple;">`List`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  



## *ToString*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```


## *UltimateOscillatorSource*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UltimateOscillatorSource()
```

# Свойства

## *Period1*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Period1 { get; set; }
```

## *Period2*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Period2 { get; set; }
```

## *Period3*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Period3 { get; set; }
```

