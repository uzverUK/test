
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class IchimokuSource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./IchimokuSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./IchimokuSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./IchimokuSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`IchimokuSource`](./IchimokuSource.cs/Методы/IchimokuSource.md) | *Описание* |
| [`ToString`](./IchimokuSource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Period1`](./IchimokuSource.cs/Свойства/Period1.md) | *Описание* |
| [`Period2`](./IchimokuSource.cs/Свойства/Period2.md) | *Описание* |
| [`Period3`](./IchimokuSource.cs/Свойства/Period3.md) | *Описание* |
| [`Period4`](./IchimokuSource.cs/Свойства/Period4.md) | *Описание* |
| [`Period5`](./IchimokuSource.cs/Свойства/Period5.md) | *Описание* |




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

## IchimokuSource
Описание

```csharp
public IchimokuSource()
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

## Period1
Описание

```csharp
public int Period1 { get; set; }
```
***

## Period2
Описание

```csharp
public int Period2 { get; set; }
```
***

## Period3
Описание

```csharp
public int Period3 { get; set; }
```
***

## Period4
Описание

```csharp
public int Period4 { get; set; }
```
***

## Period5
Описание

```csharp
public int Period5 { get; set; }
```
***

