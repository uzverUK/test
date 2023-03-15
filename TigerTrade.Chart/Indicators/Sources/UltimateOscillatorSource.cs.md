
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class UltimateOscillatorSource : IndicatorSourceBase
```


## Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./UltimateOscillatorSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./UltimateOscillatorSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./UltimateOscillatorSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./UltimateOscillatorSource.cs/Методы/ToString.md) | *Описание* |
| [`UltimateOscillatorSource`](./UltimateOscillatorSource.cs/Методы/UltimateOscillatorSource.md) | *Описание* |

## Таблица свойств
| Название | Описание |
| --- | --- |
| [`Period1`](./UltimateOscillatorSource.cs/Свойства/Period1.md) | *Описание* |
| [`Period2`](./UltimateOscillatorSource.cs/Свойства/Period2.md) | *Описание* |
| [`Period3`](./UltimateOscillatorSource.cs/Свойства/Period3.md) | *Описание* |




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

## UltimateOscillatorSource
Описание

```csharp
public UltimateOscillatorSource()
```

***                
                ***
  ***
  # Свойства

## Period1
Описание

```csharp
public int Period1 { get; set; }
```
***

## Period2
Описание

```csharp
public int Period2 { get; set; }
```
***

## Period3
Описание

```csharp
public int Period3 { get; set; }
```
***

