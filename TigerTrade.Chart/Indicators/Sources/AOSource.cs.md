
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class AOSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`AOSource`](./AOSource.cs/Методы/AOSource.md) | *Описание* |
| [`CopySettings`](./AOSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./AOSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./AOSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./AOSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`LongPeriod`](./AOSource.cs/Свойства/LongPeriod.md) | *Описание* |
| [`MaType`](./AOSource.cs/Свойства/MaType.md) | *Описание* |
| [`ShortPeriod`](./AOSource.cs/Свойства/ShortPeriod.md) | *Описание* |




            ***
  ***
  # Методы

## AOSource
Описание

```csharp
public AOSource()
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

