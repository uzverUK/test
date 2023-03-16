# ChartSeries

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Drawings](./)

\===

#### Синтаксис

```csharp
public sealed class ChartSeries : INotifyPropertyChanged, IDynamicProperty
```

## Список методов

| Название                                                                                | Описание |
| --------------------------------------------------------------------------------------- | -------- |
| [`ChartSeries`](chartseries.cs.md#method-chartseries)                                   | _===_    |
| [`CopyTheme`](chartseries.cs.md#method-copytheme)                                       | _===_    |
| [`GetPropertyHasStandardValues`](chartseries.cs.md#method-getpropertyhasstandardvalues) | _===_    |
| [`GetPropertyReadOnly`](chartseries.cs.md#method-getpropertyreadonly)                   | _===_    |
| [`GetPropertyStandardValues`](chartseries.cs.md#method-getpropertystandardvalues)       | _===_    |
| [`GetPropertyVisibility`](chartseries.cs.md#method-getpropertyvisibility)               | _===_    |
| [`ToString`](chartseries.cs.md#method-tostring)                                         | _===_    |

## Список свойств

| Название                                              | Описание |
| ----------------------------------------------------- | -------- |
| [`AllColors`](chartseries.cs.md#property-allcolors)   | _===_    |
| [`Color`](chartseries.cs.md#property-color)           | _===_    |
| [`Color2`](chartseries.cs.md#property-color2)         | _===_    |
| [`ColorSplit`](chartseries.cs.md#property-colorsplit) | _===_    |
| [`DotStyle`](chartseries.cs.md#property-dotstyle)     | _===_    |
| [`ShowMarker`](chartseries.cs.md#property-showmarker) | _===_    |
| [`Style`](chartseries.cs.md#property-style)           | _===_    |
| [`Type`](chartseries.cs.md#property-type)             | _===_    |
| [`Visible`](chartseries.cs.md#property-visible)       | _===_    |
| [`Width`](chartseries.cs.md#property-width)           | _===_    |

## Список событий

| Название                                                     | Описание |
| ------------------------------------------------------------ | -------- |
| [`PropertyChanged`](chartseries.cs.md#event-propertychanged) | _===_    |

***

***

## Методы

### `ChartSeries` <a href="#method-chartseries" id="method-chartseries"></a>

\===

```csharp
public ChartSeries()
```

***

### `ChartSeries` <a href="#method-chartseries" id="method-chartseries"></a>

\===

```csharp
public ChartSeries()
public ChartSeries(ChartSeriesType type, XColor color)
```

`type` _<mark style="color:red;">`ChartSeriesType`</mark>_\
_===_

`color` _<mark style="color:red;">`XColor`</mark>_\
_===_

***

### `ChartSeries` <a href="#method-chartseries" id="method-chartseries"></a>

\===

```csharp
public ChartSeries()
public ChartSeries(ChartSeriesType type, XColor color)
public ChartSeries(ChartSeriesType type, XColor color, XDashStyle style)
```

`type` _<mark style="color:red;">`ChartSeriesType`</mark>_\
_===_

`color` _<mark style="color:red;">`XColor`</mark>_\
_===_

`style` _<mark style="color:red;">`XDashStyle`</mark>_\
_===_

***

### `CopyTheme` <a href="#method-copytheme" id="method-copytheme"></a>

\===

```csharp
public void CopyTheme(ChartSeries chartSeries)
```

`chartSeries` _<mark style="color:red;">`ChartSeries`</mark>_\
_===_

***

### `GetPropertyHasStandardValues` <a href="#method-getpropertyhasstandardvalues" id="method-getpropertyhasstandardvalues"></a>

\===

```csharp
public bool GetPropertyHasStandardValues(string propertyName)
```

`propertyName` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetPropertyReadOnly` <a href="#method-getpropertyreadonly" id="method-getpropertyreadonly"></a>

\===

```csharp
public bool GetPropertyReadOnly(string propertyName)
```

***

### `GetPropertyStandardValues` <a href="#method-getpropertystandardvalues" id="method-getpropertystandardvalues"></a>

\===

```csharp
public IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetPropertyVisibility` <a href="#method-getpropertyvisibility" id="method-getpropertyvisibility"></a>

\===

```csharp
public bool GetPropertyVisibility(string propertyName)
```

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

***

***

***

## Свойства

### `AllColors` <a href="#property-allcolors" id="property-allcolors"></a>

\===

```csharp
public XColor AllColors {set; }
```

***

### `Color` <a href="#property-color" id="property-color"></a>

\===

```csharp
public XColor Color { get; set; }
```

***

### `Color2` <a href="#property-color2" id="property-color2"></a>

\===

```csharp
public XColor Color2 { get; set; }
```

***

### `ColorSplit` <a href="#property-colorsplit" id="property-colorsplit"></a>

\===

```csharp
public ChartSeriesColorSplit ColorSplit { get; set; }
```

***

### `DotStyle` <a href="#property-dotstyle" id="property-dotstyle"></a>

\===

```csharp
public ChartSeriesDotStyle DotStyle { get; set; }
```

***

### `ShowMarker` <a href="#property-showmarker" id="property-showmarker"></a>

\===

```csharp
public bool ShowMarker { get; set; }
```

***

### `Style` <a href="#property-style" id="property-style"></a>

\===

```csharp
public XDashStyle Style { get; set; }
```

***

### `Type` <a href="#property-type" id="property-type"></a>

\===

```csharp
public ChartSeriesType Type { get; set; }
```

***

### `Visible` <a href="#property-visible" id="property-visible"></a>

\===

```csharp
public bool Visible { get; set; }
```

***

### `Width` <a href="#property-width" id="property-width"></a>

\===

```csharp
public int Width { get; set; }
```

***

***

***

## События

### `PropertyChanged` <a href="#event-propertychanged" id="event-propertychanged"></a>

\===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```
