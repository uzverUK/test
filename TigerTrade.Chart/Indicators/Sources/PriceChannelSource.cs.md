
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class PriceChannelSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./PriceChannelSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./PriceChannelSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./PriceChannelSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`PriceChannelSource`](./PriceChannelSource.cs/Методы/PriceChannelSource.md) | *Описание* |
| [`ToString`](./PriceChannelSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./PriceChannelSource.cs/Свойства/Period.md) | *Описание* |




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

## PriceChannelSource
Описание

```csharp
public PriceChannelSource()
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

