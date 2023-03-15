
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class VHFSource : IndicatorSourceBase
```


## Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./VHFSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./VHFSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./VHFSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./VHFSource.cs/Методы/ToString.md) | *Описание* |
| [`VHFSource`](./VHFSource.cs/Методы/VHFSource.md) | *Описание* |

## Таблица свойств
| Название | Описание |
| --- | --- |
| [`Period`](./VHFSource.cs/Свойства/Period.md) | *Описание* |




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

## VHFSource
Описание

```csharp
public VHFSource()
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

