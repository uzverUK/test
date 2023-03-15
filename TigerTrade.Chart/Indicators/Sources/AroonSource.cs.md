
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class AroonSource : IndicatorSourceBase
```


## Таблица методов
| Название | Описание |
| --- | --- |
| [`AroonSource`](./AroonSource.cs/Методы/AroonSource.md) | *Описание* |
| [`CopySettings`](./AroonSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./AroonSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./AroonSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./AroonSource.cs/Методы/ToString.md) | *Описание* |

## Таблица свойств
| Название | Описание |
| --- | --- |
| [`Period`](./AroonSource.cs/Свойства/Period.md) | *Описание* |




            ***
  ***
  # Методы

## AroonSource
Описание

```csharp
public AroonSource()
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

