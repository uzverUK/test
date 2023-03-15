
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class MACDSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./MACDSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./MACDSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./MACDSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`MACDSource`](./MACDSource.cs/Методы/MACDSource.md) | *Описание* |
| [`ToString`](./MACDSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Fast`](./MACDSource.cs/Свойства/Fast.md) | *Описание* |
| [`Signal`](./MACDSource.cs/Свойства/Signal.md) | *Описание* |
| [`Slow`](./MACDSource.cs/Свойства/Slow.md) | *Описание* |
| [`Source`](./MACDSource.cs/Свойства/Source.md) | *Описание* |




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

## MACDSource
Описание

```csharp
public MACDSource()
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

## Fast
Описание

```csharp
public int Fast { get; set; }
```
***

## Signal
Описание

```csharp
public int Signal { get; set; }
```
***

## Slow
Описание

```csharp
public int Slow { get; set; }
```
***

## Source
Описание

```csharp
public IndicatorSourceBase Source { get; set; }
```
***

