
# public sealed class CMOSource : IndicatorSourceBase
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)



Описаниеt

### Синтаксис
```csharp
public sealed class CMOSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CMOSource`](./CMOSource.cs/Методы/CMOSource.md) | *Описание* |
| [`CopySettings`](./CMOSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./CMOSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./CMOSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./CMOSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./CMOSource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./CMOSource.cs/Свойства/Source.md) | *Описание* |




            ***
  ***
  # Методы

## CMOSource
Описание

```csharp
public CMOSource()
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

## Source
Описание

```csharp
public IndicatorSourceBase Source { get; set; }
```
***

