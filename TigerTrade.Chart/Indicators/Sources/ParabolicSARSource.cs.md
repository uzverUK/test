
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class ParabolicSARSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./ParabolicSARSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./ParabolicSARSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./ParabolicSARSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ParabolicSARSource`](./ParabolicSARSource.cs/Методы/ParabolicSARSource.md) | *Описание* |
| [`ToString`](./ParabolicSARSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Max`](./ParabolicSARSource.cs/Свойства/Max.md) | *Описание* |
| [`Step`](./ParabolicSARSource.cs/Свойства/Step.md) | *Описание* |




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

## ParabolicSARSource
Описание

```csharp
public ParabolicSARSource()
```

***                

## ToString
Описание

```csharp
public override string ToString()
```

<mark style="color:yellow;">`string`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***                
                ***
  ***
  # Свойства

## Max
Описание

```csharp
public Decimal Max { get; set; }
```
***

## Step
Описание

```csharp
public Decimal Step { get; set; }
```
***

