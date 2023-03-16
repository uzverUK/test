
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Collections](../../../TigerTrade.Chart/Indicators/Collections.md)


===

### Синтаксис
```csharp
public sealed class IndicatorSeries : IEnumerable<IndicatorSeriesData>, IEnumerable
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Add`](#method-add) | *===* |
| [`Clear`](#method-clear) | *===* |
| [`GetEnumerator`](#method-getenumerator) | *===* |
| [`IndicatorSeries`](#method-indicatorseries) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Count`](#property-count) | *===* |





***  
***  
# Методы

## `Add`<a href="method-add" id="method-add"></a>
===
```csharp
public void Add(IndicatorSeriesData series)
```

`series` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *===*  


***  

## `Add`<a href="method-add" id="method-add"></a>
===
```csharp
public void Add(IndicatorSeriesData series)
public void Add(IndicatorSeriesData series1, IndicatorSeriesData series2)
```

`series` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *===*  

`series1` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *===*  

`series2` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *===*  


***  

## `Add`<a href="method-add" id="method-add"></a>
===
```csharp
public void Add(IndicatorSeriesData series)
public void Add(IndicatorSeriesData series1, IndicatorSeriesData series2)
public void Add(params IndicatorSeriesData[] series)
```

`series` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *===*  

`series1` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *===*  

`series2` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *===*  

`IndicatorSeriesData` <mark style="color:red;">*`params`*</mark>  
 *===*  


***  

## `Clear`<a href="method-clear" id="method-clear"></a>
===
```csharp
public void Clear()
```

***  

## `GetEnumerator`<a href="method-getenumerator" id="method-getenumerator"></a>
===
```csharp
public IEnumerator<IndicatorSeriesData> GetEnumerator()
```

***  

## `IndicatorSeries`<a href="method-indicatorseries" id="method-indicatorseries"></a>
===
```csharp
public IndicatorSeries()
```

***  
***  
 ***  
# Свойства

## `Count`<a href="property-count" id="property-count"></a>
===
```csharp
public int Count { get; }
```  
***

