
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


===

### Синтаксис
```csharp
public sealed class IndicatorSeriesData
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CachePoints`](#method-cachepoints) | *===* |
| [`GetDistance`](#method-getdistance) | *===* |
| [`IndicatorSeriesData`](#method-indicatorseriesdata) | *===* |
| [`MaxValue`](#method-maxvalue) | *===* |
| [`MinValue`](#method-minvalue) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Data`](#property-data) | *===* |
| [`Length`](#property-length) | *===* |
| [`Style`](#property-style) | *===* |
| [`UserData`](#property-userdata) | *===* |





***  
***  
# Методы

## `CachePoints`<a href="method-cachepoints" id="method-cachepoints"></a>
===
```csharp
public void CachePoints(Point[] points, string pointsName)
```

`pointsName` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetDistance`<a href="method-getdistance" id="method-getdistance"></a>
===
```csharp
public double GetDistance(double x, double y)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *===*  

`y` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `IndicatorSeriesData`<a href="method-indicatorseriesdata" id="method-indicatorseriesdata"></a>
===
```csharp
public IndicatorSeriesData(double[] data)
```

***  

## `IndicatorSeriesData`<a href="method-indicatorseriesdata" id="method-indicatorseriesdata"></a>
===
```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
```

`style` <mark style="color:red;">*`ChartSeries`*</mark>  
 *===*  

`name` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `IndicatorSeriesData`<a href="method-indicatorseriesdata" id="method-indicatorseriesdata"></a>
===
```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
public IndicatorSeriesData(double[] data, ChartRegion style)
```

`style` <mark style="color:red;">*`ChartSeries`*</mark>  
 *===*  

`name` <mark style="color:red;">*`string`*</mark>  
 *===*  

`style` <mark style="color:red;">*`ChartRegion`*</mark>  
 *===*  


***  

## `IndicatorSeriesData`<a href="method-indicatorseriesdata" id="method-indicatorseriesdata"></a>
===
```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
public IndicatorSeriesData(double[] data, ChartRegion style)
public IndicatorSeriesData(double[] data, ChartLine style)
```

`style` <mark style="color:red;">*`ChartSeries`*</mark>  
 *===*  

`name` <mark style="color:red;">*`string`*</mark>  
 *===*  

`style` <mark style="color:red;">*`ChartRegion`*</mark>  
 *===*  

`style` <mark style="color:red;">*`ChartLine`*</mark>  
 *===*  


***  

## `MaxValue`<a href="method-maxvalue" id="method-maxvalue"></a>
===
```csharp
public double MaxValue()
```

***  

## `MaxValue`<a href="method-maxvalue" id="method-maxvalue"></a>
===
```csharp
public double MaxValue()
public double MaxValue(int start, int count)
```

`start` <mark style="color:red;">*`int`*</mark>  
 *===*  

`count` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `MinValue`<a href="method-minvalue" id="method-minvalue"></a>
===
```csharp
public double MinValue()
```

***  

## `MinValue`<a href="method-minvalue" id="method-minvalue"></a>
===
```csharp
public double MinValue()
public double MinValue(int start, int count)
```

`start` <mark style="color:red;">*`int`*</mark>  
 *===*  

`count` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Data`<a href="property-data" id="property-data"></a>
===
```csharp
public double[] Data { get; }
```  
***

## `Length`<a href="property-length" id="property-length"></a>
===
```csharp
public int Length { get; }
```  
***

## `Style`<a href="property-style" id="property-style"></a>
===
```csharp
public IndicatorSeriesStyle Style { get; }
```  
***

## `UserData`<a href="property-userdata" id="property-userdata"></a>
===
```csharp
public Hashtable UserData { get; }
```  
***

