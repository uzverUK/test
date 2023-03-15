
# public sealed class KeltnerChannelSource : IndicatorSourceBase
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)



Описаниеt

### Синтаксис
```csharp
public sealed class KeltnerChannelSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./KeltnerChannelSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./KeltnerChannelSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./KeltnerChannelSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`KeltnerChannelSource`](./KeltnerChannelSource.cs/Методы/KeltnerChannelSource.md) | *Описание* |
| [`ToString`](./KeltnerChannelSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Factor`](./KeltnerChannelSource.cs/Свойства/Factor.md) | *Описание* |
| [`MaType`](./KeltnerChannelSource.cs/Свойства/MaType.md) | *Описание* |
| [`Period`](./KeltnerChannelSource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./KeltnerChannelSource.cs/Свойства/Source.md) | *Описание* |




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

## KeltnerChannelSource
Описание

```csharp
public KeltnerChannelSource()
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

## Factor
Описание

```csharp
public int Factor { get; set; }
```
***

## MaType
Описание

```csharp
public IndicatorMaType MaType { get; set; }
```
***

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

