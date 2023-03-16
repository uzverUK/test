# IndicatorSeriesData

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Common](./)

\===

#### Синтаксис

```csharp
public sealed class IndicatorSeriesData
```

## Список методов

| Название                                                                      | Описание |
| ----------------------------------------------------------------------------- | -------- |
| [`CachePoints`](indicatorseriesdata.cs.md#method-cachepoints)                 | _===_    |
| [`GetDistance`](indicatorseriesdata.cs.md#method-getdistance)                 | _===_    |
| [`IndicatorSeriesData`](indicatorseriesdata.cs.md#method-indicatorseriesdata) | _===_    |
| [`MaxValue`](indicatorseriesdata.cs.md#method-maxvalue)                       | _===_    |
| [`MinValue`](indicatorseriesdata.cs.md#method-minvalue)                       | _===_    |

## Список свойств

| Название                                                  | Описание |
| --------------------------------------------------------- | -------- |
| [`Data`](indicatorseriesdata.cs.md#property-data)         | _===_    |
| [`Length`](indicatorseriesdata.cs.md#property-length)     | _===_    |
| [`Style`](indicatorseriesdata.cs.md#property-style)       | _===_    |
| [`UserData`](indicatorseriesdata.cs.md#property-userdata) | _===_    |

***

***

## Методы

### `CachePoints` <a href="#method-cachepoints" id="method-cachepoints"></a>

\===

```csharp
public void CachePoints(Point[] points, string pointsName)
```

`pointsName` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetDistance` <a href="#method-getdistance" id="method-getdistance"></a>

\===

```csharp
public double GetDistance(double x, double y)
```

`x` _<mark style="color:red;">`double`</mark>_\
_===_

`y` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `IndicatorSeriesData` <a href="#method-indicatorseriesdata" id="method-indicatorseriesdata"></a>

\===

```csharp
public IndicatorSeriesData(double[] data)
```

***

### `IndicatorSeriesData` <a href="#method-indicatorseriesdata" id="method-indicatorseriesdata"></a>

\===

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
```

`style` _<mark style="color:red;">`ChartSeries`</mark>_\
_===_

`name` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `IndicatorSeriesData` <a href="#method-indicatorseriesdata" id="method-indicatorseriesdata"></a>

\===

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
public IndicatorSeriesData(double[] data, ChartRegion style)
```

`style` _<mark style="color:red;">`ChartSeries`</mark>_\
_===_

`name` _<mark style="color:red;">`string`</mark>_\
_===_

`style` _<mark style="color:red;">`ChartRegion`</mark>_\
_===_

***

### `IndicatorSeriesData` <a href="#method-indicatorseriesdata" id="method-indicatorseriesdata"></a>

\===

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
public IndicatorSeriesData(double[] data, ChartRegion style)
public IndicatorSeriesData(double[] data, ChartLine style)
```

`style` _<mark style="color:red;">`ChartSeries`</mark>_\
_===_

`name` _<mark style="color:red;">`string`</mark>_\
_===_

`style` _<mark style="color:red;">`ChartRegion`</mark>_\
_===_

`style` _<mark style="color:red;">`ChartLine`</mark>_\
_===_

***

### `MaxValue` <a href="#method-maxvalue" id="method-maxvalue"></a>

\===

```csharp
public double MaxValue()
```

***

### `MaxValue` <a href="#method-maxvalue" id="method-maxvalue"></a>

\===

```csharp
public double MaxValue()
public double MaxValue(int start, int count)
```

`start` _<mark style="color:red;">`int`</mark>_\
_===_

`count` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `MinValue` <a href="#method-minvalue" id="method-minvalue"></a>

\===

```csharp
public double MinValue()
```

***

### `MinValue` <a href="#method-minvalue" id="method-minvalue"></a>

\===

```csharp
public double MinValue()
public double MinValue(int start, int count)
```

`start` _<mark style="color:red;">`int`</mark>_\
_===_

`count` _<mark style="color:red;">`int`</mark>_\
_===_

***

***

***

## Свойства

### `Data` <a href="#property-data" id="property-data"></a>

\===

```csharp
public double[] Data { get; }
```

***

### `Length` <a href="#property-length" id="property-length"></a>

\===

```csharp
public int Length { get; }
```

***

### `Style` <a href="#property-style" id="property-style"></a>

\===

```csharp
public IndicatorSeriesStyle Style { get; }
```

***

### `UserData` <a href="#property-userdata" id="property-userdata"></a>

\===

```csharp
public Hashtable UserData { get; }
```

***
