
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class CandlePatternSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CandlePatternSource`](./CandlePatternSource.cs/Методы/CandlePatternSource.md) | *Описание* |
| [`CopySettings`](./CandlePatternSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./CandlePatternSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./CandlePatternSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`SearchPattern`](./CandlePatternSource.cs/Методы/SearchPattern.md) | *Описание* |
| [`ToString`](./CandlePatternSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`PatternType`](./CandlePatternSource.cs/Свойства/PatternType.md) | *Описание* |
| [`Penetration`](./CandlePatternSource.cs/Свойства/Penetration.md) | *Описание* |




            ***
  ***
  # Методы

## CandlePatternSource
Описание

```csharp
public CandlePatternSource()
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

## SearchPattern
Описание

```csharp
public double[] SearchPattern(IndicatorsHelper helper, CandlePatternSourcePatternType type)
```
<mark style="color:yellow;">`helper`</mark> <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  

<mark style="color:yellow;">`type`</mark> <mark style="color:red;">*`CandlePatternSourcePatternType`*</mark>  
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

## PatternType
Описание

```csharp
public CandlePatternSourcePatternType PatternType { get; set; }
```
***

## Penetration
Описание

```csharp
public double Penetration { get; set; }
```
***

