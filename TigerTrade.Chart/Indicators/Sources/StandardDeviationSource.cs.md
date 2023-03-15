
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class StandardDeviationSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./StandardDeviationSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./StandardDeviationSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./StandardDeviationSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`StandardDeviationSource`](./StandardDeviationSource.cs/Методы/StandardDeviationSource.md) | *Описание* |
| [`ToString`](./StandardDeviationSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./StandardDeviationSource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./StandardDeviationSource.cs/Свойства/Source.md) | *Описание* |




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

## StandardDeviationSource
Описание

```csharp
public StandardDeviationSource()
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

