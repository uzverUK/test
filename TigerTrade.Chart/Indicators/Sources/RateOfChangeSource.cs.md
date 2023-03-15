
# public sealed class RateOfChangeSource : IndicatorSourceBase
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)



Описаниеt

### Синтаксис
```csharp
public sealed class RateOfChangeSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./RateOfChangeSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./RateOfChangeSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./RateOfChangeSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`RateOfChangeSource`](./RateOfChangeSource.cs/Методы/RateOfChangeSource.md) | *Описание* |
| [`ToString`](./RateOfChangeSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./RateOfChangeSource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./RateOfChangeSource.cs/Свойства/Source.md) | *Описание* |




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

## RateOfChangeSource
Описание

```csharp
public RateOfChangeSource()
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

