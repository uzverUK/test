
# MoneyFlowIndexSource
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)



Описаниеt

### Синтаксис
```csharp
public sealed class MoneyFlowIndexSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./MoneyFlowIndexSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./MoneyFlowIndexSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./MoneyFlowIndexSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`MoneyFlowIndexSource`](./MoneyFlowIndexSource.cs/Методы/MoneyFlowIndexSource.md) | *Описание* |
| [`ToString`](./MoneyFlowIndexSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./MoneyFlowIndexSource.cs/Свойства/Period.md) | *Описание* |




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

## MoneyFlowIndexSource
Описание

```csharp
public MoneyFlowIndexSource()
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

