
# public sealed class ACSource : IndicatorSourceBase
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)



Описаниеt

### Синтаксис
```csharp
public sealed class ACSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`ACSource`](./ACSource.cs/Методы/ACSource.md) | *Описание* |
| [`CopySettings`](./ACSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./ACSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./ACSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./ACSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`LongPeriod`](./ACSource.cs/Свойства/LongPeriod.md) | *Описание* |
| [`MaType`](./ACSource.cs/Свойства/MaType.md) | *Описание* |
| [`ShortPeriod`](./ACSource.cs/Свойства/ShortPeriod.md) | *Описание* |




            ***
  ***
  # Методы

## ACSource
Описание

```csharp
public ACSource()
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

