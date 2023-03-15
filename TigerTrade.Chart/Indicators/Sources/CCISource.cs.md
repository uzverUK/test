
# public sealed class CCISource : IndicatorSourceBase
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)



Описаниеt

### Синтаксис
```csharp
public sealed class CCISource : IndicatorSourceBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CCISource`](./CCISource.cs/Методы/CCISource.md) | *Описание* |
| [`CopySettings`](./CCISource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./CCISource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./CCISource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./CCISource.cs/Методы/ToString.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./CCISource.cs/Свойства/Period.md) | *Описание* |




            ***
  ***
  # Методы

## CCISource
Описание

```csharp
public CCISource()
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

