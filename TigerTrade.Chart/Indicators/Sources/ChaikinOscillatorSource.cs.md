
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class ChaikinOscillatorSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`ChaikinOscillatorSource`](./ChaikinOscillatorSource.cs/Методы/ChaikinOscillatorSource.md) | *Описание* |
| [`CopySettings`](./ChaikinOscillatorSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./ChaikinOscillatorSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./ChaikinOscillatorSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./ChaikinOscillatorSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`LongPeriod`](./ChaikinOscillatorSource.cs/Свойства/LongPeriod.md) | *Описание* |
| [`MaType`](./ChaikinOscillatorSource.cs/Свойства/MaType.md) | *Описание* |
| [`ShortPeriod`](./ChaikinOscillatorSource.cs/Свойства/ShortPeriod.md) | *Описание* |




            ***
  ***
  # Методы

## ChaikinOscillatorSource
Описание

```csharp
public ChaikinOscillatorSource()
```

***                

## CopySettings
Описание

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

<mark style="color:yellow;">`source`</mark> <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  


***                

## GetSeries
Описание

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```
<mark style="color:yellow;">`helper`</mark> <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  


***                

## GetSeriesList
Описание

```csharp
public override IEnumerable<string> GetSeriesList()
```
<mark style="color:yellow;">`List`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***                

## ToString
Описание

```csharp
public override string ToString()
```

***                
                ***
  ***
  # Свойства

## LongPeriod
Описание

```csharp
public int LongPeriod { get; set; }
```
***

## MaType
Описание

```csharp
public IndicatorMaType MaType { get; set; }
```
***

## ShortPeriod
Описание

```csharp
public int ShortPeriod { get; set; }
```
***

