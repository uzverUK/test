
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class ChaikinMoneyFlowSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`ChaikinMoneyFlowSource`](./ChaikinMoneyFlowSource.cs/Методы/ChaikinMoneyFlowSource.md) | *Описание* |
| [`CopySettings`](./ChaikinMoneyFlowSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./ChaikinMoneyFlowSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./ChaikinMoneyFlowSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./ChaikinMoneyFlowSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./ChaikinMoneyFlowSource.cs/Свойства/Period.md) | *Описание* |




            ***
  ***
  # Методы

## ChaikinMoneyFlowSource
Описание

```csharp
public ChaikinMoneyFlowSource()
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

## Period
Описание

```csharp
public int Period { get; set; }
```
***

