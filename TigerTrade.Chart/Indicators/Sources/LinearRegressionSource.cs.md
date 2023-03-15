
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class LinearRegressionSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./LinearRegressionSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./LinearRegressionSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./LinearRegressionSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`LinearRegressionSource`](./LinearRegressionSource.cs/Методы/LinearRegressionSource.md) | *Описание* |
| [`ToString`](./LinearRegressionSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./LinearRegressionSource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./LinearRegressionSource.cs/Свойства/Source.md) | *Описание* |




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

## LinearRegressionSource
Описание

```csharp
public LinearRegressionSource()
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

## Period
Описание

```csharp
public int Period { get; set; }
```
***

## Source
Описание

```csharp
public IndicatorSourceBase Source { get; set; }
```
***

