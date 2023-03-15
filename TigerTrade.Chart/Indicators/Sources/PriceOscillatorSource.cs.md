
# PriceOscillatorSource
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)



Описаниеt

### Синтаксис
```csharp
public sealed class PriceOscillatorSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./PriceOscillatorSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./PriceOscillatorSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./PriceOscillatorSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`PriceOscillatorSource`](./PriceOscillatorSource.cs/Методы/PriceOscillatorSource.md) | *Описание* |
| [`ToString`](./PriceOscillatorSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`LongPeriod`](./PriceOscillatorSource.cs/Свойства/LongPeriod.md) | *Описание* |
| [`MaType`](./PriceOscillatorSource.cs/Свойства/MaType.md) | *Описание* |
| [`ShortPeriod`](./PriceOscillatorSource.cs/Свойства/ShortPeriod.md) | *Описание* |
| [`Source`](./PriceOscillatorSource.cs/Свойства/Source.md) | *Описание* |




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

## PriceOscillatorSource
Описание

```csharp
public PriceOscillatorSource()
```

***                

## ToString
Описание

```csharp
public override string ToString()
```

<mark style="color:yellow;">`object`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  


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

## Source
Описание

```csharp
public IndicatorSourceBase Source { get; set; }
```
***

