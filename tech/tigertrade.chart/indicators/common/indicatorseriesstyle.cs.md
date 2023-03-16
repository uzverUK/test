# IndicatorSeriesStyle

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Common](./)

\===

#### Синтаксис

```csharp
public sealed class IndicatorSeriesStyle
```

## Список методов

| Название                                                                         | Описание |
| -------------------------------------------------------------------------------- | -------- |
| [`DisableAll`](indicatorseriesstyle.cs.md#method-disableall)                     | _===_    |
| [`IndicatorSeriesStyle`](indicatorseriesstyle.cs.md#method-indicatorseriesstyle) | _===_    |
| [`Set`](indicatorseriesstyle.cs.md#method-set)                                   | _===_    |

## Список свойств

| Название                                                               | Описание |
| ---------------------------------------------------------------------- | -------- |
| [`Color2;`](indicatorseriesstyle.cs.md#property-color2;)               | _===_    |
| [`Color;`](indicatorseriesstyle.cs.md#property-color;)                 | _===_    |
| [`ColorSplit;`](indicatorseriesstyle.cs.md#property-colorsplit;)       | _===_    |
| [`DisableLabel;`](indicatorseriesstyle.cs.md#property-disablelabel;)   | _===_    |
| [`DisableMinMax;`](indicatorseriesstyle.cs.md#property-disableminmax;) | _===_    |
| [`DisableSelect;`](indicatorseriesstyle.cs.md#property-disableselect;) | _===_    |
| [`DisableValue;`](indicatorseriesstyle.cs.md#property-disablevalue;)   | _===_    |
| [`DotType;`](indicatorseriesstyle.cs.md#property-dottype;)             | _===_    |
| [`HighPercent;`](indicatorseriesstyle.cs.md#property-highpercent;)     | _===_    |
| [`LineStyle;`](indicatorseriesstyle.cs.md#property-linestyle;)         | _===_    |
| [`LineWidth;`](indicatorseriesstyle.cs.md#property-linewidth;)         | _===_    |
| [`LowPercent;`](indicatorseriesstyle.cs.md#property-lowpercent;)       | _===_    |
| [`Name;`](indicatorseriesstyle.cs.md#property-name;)                   | _===_    |
| [`RenderType;`](indicatorseriesstyle.cs.md#property-rendertype;)       | _===_    |
| [`StraightLine;`](indicatorseriesstyle.cs.md#property-straightline;)   | _===_    |
| [`Visible;`](indicatorseriesstyle.cs.md#property-visible;)             | _===_    |

***

***

## Методы

### `DisableAll` <a href="#method-disableall" id="method-disableall"></a>

\===

```csharp
public void DisableAll()
```

***

### `IndicatorSeriesStyle` <a href="#method-indicatorseriesstyle" id="method-indicatorseriesstyle"></a>

\===

```csharp
public IndicatorSeriesStyle()
```

***

### `Set` <a href="#method-set" id="method-set"></a>

\===

```csharp
public void Set(ChartSeries series, string name = "")
```

`series` _<mark style="color:red;">`ChartSeries`</mark>_\
_===_

`name` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `Set` <a href="#method-set" id="method-set"></a>

\===

```csharp
public void Set(ChartSeries series, string name = "")
public void Set(ChartRegion region)
```

`series` _<mark style="color:red;">`ChartSeries`</mark>_\
_===_

`name` _<mark style="color:red;">`string`</mark>_\
_===_

`region` _<mark style="color:red;">`ChartRegion`</mark>_\
_===_

***

### `Set` <a href="#method-set" id="method-set"></a>

\===

```csharp
public void Set(ChartSeries series, string name = "")
public void Set(ChartRegion region)
public void Set(ChartLine line)
```

`series` _<mark style="color:red;">`ChartSeries`</mark>_\
_===_

`name` _<mark style="color:red;">`string`</mark>_\
_===_

`region` _<mark style="color:red;">`ChartRegion`</mark>_\
_===_

`line` _<mark style="color:red;">`ChartLine`</mark>_\
_===_

***

***

***

## Свойства

### `Color2;` <a href="#property-color2" id="property-color2"></a>

\===

```csharp
public XColor Color2; {}
```

***

### `Color;` <a href="#property-color" id="property-color"></a>

\===

```csharp
public XColor Color; {}
```

***

### `ColorSplit;` <a href="#property-colorsplit" id="property-colorsplit"></a>

\===

```csharp
public ChartSeriesColorSplit ColorSplit; {}
```

***

### `DisableLabel;` <a href="#property-disablelabel" id="property-disablelabel"></a>

\===

```csharp
public bool DisableLabel; {}
```

***

### `DisableMinMax;` <a href="#property-disableminmax" id="property-disableminmax"></a>

\===

```csharp
public bool DisableMinMax; {}
```

***

### `DisableSelect;` <a href="#property-disableselect" id="property-disableselect"></a>

\===

```csharp
public bool DisableSelect; {}
```

***

### `DisableValue;` <a href="#property-disablevalue" id="property-disablevalue"></a>

\===

```csharp
public bool DisableValue; {}
```

***

### `DotType;` <a href="#property-dottype" id="property-dottype"></a>

\===

```csharp
public ChartSeriesDotStyle DotType; {}
```

***

### `HighPercent;` <a href="#property-highpercent" id="property-highpercent"></a>

\===

```csharp
public double HighPercent; {}
```

***

### `LineStyle;` <a href="#property-linestyle" id="property-linestyle"></a>

\===

```csharp
public XDashStyle LineStyle; {}
```

***

### `LineWidth;` <a href="#property-linewidth" id="property-linewidth"></a>

\===

```csharp
public int LineWidth; {}
```

***

### `LowPercent;` <a href="#property-lowpercent" id="property-lowpercent"></a>

\===

```csharp
public double LowPercent; {}
```

***

### `Name;` <a href="#property-name" id="property-name"></a>

\===

```csharp
public string Name; {}
```

***

### `RenderType;` <a href="#property-rendertype" id="property-rendertype"></a>

\===

```csharp
public ChartSeriesType RenderType; {}
```

***

### `StraightLine;` <a href="#property-straightline" id="property-straightline"></a>

\===

```csharp
public bool StraightLine; {}
```

***

### `Visible;` <a href="#property-visible" id="property-visible"></a>

\===

```csharp
public bool Visible; {}
```

***
