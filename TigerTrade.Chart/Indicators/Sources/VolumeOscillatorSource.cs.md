
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class VolumeOscillatorSource : IndicatorSourceBase
```


## Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./VolumeOscillatorSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./VolumeOscillatorSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./VolumeOscillatorSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./VolumeOscillatorSource.cs/Методы/ToString.md) | *Описание* |
| [`VolumeOscillatorSource`](./VolumeOscillatorSource.cs/Методы/VolumeOscillatorSource.md) | *Описание* |

## Таблица свойств
| Название | Описание |
| --- | --- |
| [`LongPeriod`](./VolumeOscillatorSource.cs/Свойства/LongPeriod.md) | *Описание* |
| [`MaType`](./VolumeOscillatorSource.cs/Свойства/MaType.md) | *Описание* |
| [`ShortPeriod`](./VolumeOscillatorSource.cs/Свойства/ShortPeriod.md) | *Описание* |




            ***
  ***
  # Методы

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

## VolumeOscillatorSource
Описание

```csharp
public VolumeOscillatorSource()
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

