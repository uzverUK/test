
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class ChaikinMoneyFlowSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ChaikinMoneyFlowSource`](./ChaikinMoneyFlowSource.cs/Методы/ChaikinMoneyFlowSource.md) | *Описание* |
| [`CopySettings`](./ChaikinMoneyFlowSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./ChaikinMoneyFlowSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./ChaikinMoneyFlowSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./ChaikinMoneyFlowSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Period`](./ChaikinMoneyFlowSource.cs/Свойства/Period.md) | *Описание* |





# Методы

## `ChaikinMoneyFlowSource`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChaikinMoneyFlowSource()
```


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



## `ToString`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

# Свойства

## `Period`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Period { get; set; }
```

