
# ChaikinsVolatilitySource
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)



Описаниеt

### Синтаксис
```csharp
public sealed class ChaikinsVolatilitySource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`ChaikinsVolatilitySource`](./ChaikinsVolatilitySource.cs/Методы/ChaikinsVolatilitySource.md) | *Описание* |
| [`CopySettings`](./ChaikinsVolatilitySource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./ChaikinsVolatilitySource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./ChaikinsVolatilitySource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./ChaikinsVolatilitySource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`MaType`](./ChaikinsVolatilitySource.cs/Свойства/MaType.md) | *Описание* |
| [`Period`](./ChaikinsVolatilitySource.cs/Свойства/Period.md) | *Описание* |




            ***
  ***
  # Методы

## ChaikinsVolatilitySource
Описание

```csharp
public ChaikinsVolatilitySource()
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

