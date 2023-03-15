
# public sealed class StochasticSource : IndicatorSourceBase
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)



Описаниеt

### Синтаксис
```csharp
public sealed class StochasticSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./StochasticSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./StochasticSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./StochasticSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`StochasticSource`](./StochasticSource.cs/Методы/StochasticSource.md) | *Описание* |
| [`ToString`](./StochasticSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`FastK`](./StochasticSource.cs/Свойства/FastK.md) | *Описание* |
| [`SlowD`](./StochasticSource.cs/Свойства/SlowD.md) | *Описание* |
| [`SlowDMaType`](./StochasticSource.cs/Свойства/SlowDMaType.md) | *Описание* |
| [`Smooth`](./StochasticSource.cs/Свойства/Smooth.md) | *Описание* |




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

## StochasticSource
Описание

```csharp
public StochasticSource()
```

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

## FastK
Описание

```csharp
public int FastK { get; set; }
```
***

## SlowD
Описание

```csharp
public int SlowD { get; set; }
```
***

## SlowDMaType
Описание

```csharp
public IndicatorMaType SlowDMaType { get; set; }
```
***

## Smooth
Описание

```csharp
public int Smooth { get; set; }
```
***

