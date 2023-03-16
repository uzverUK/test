
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


===

### Синтаксис
```csharp
public sealed class ChartSeries : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartSeries`](#method-chartseries) | *===* |
| [`CopyTheme`](#method-copytheme) | *===* |
| [`GetPropertyHasStandardValues`](#method-getpropertyhasstandardvalues) | *===* |
| [`GetPropertyReadOnly`](#method-getpropertyreadonly) | *===* |
| [`GetPropertyStandardValues`](#method-getpropertystandardvalues) | *===* |
| [`GetPropertyVisibility`](#method-getpropertyvisibility) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AllColors`](#property-allcolors) | *===* |
| [`Color`](#property-color) | *===* |
| [`Color2`](#property-color2) | *===* |
| [`ColorSplit`](#property-colorsplit) | *===* |
| [`DotStyle`](#property-dotstyle) | *===* |
| [`ShowMarker`](#property-showmarker) | *===* |
| [`Style`](#property-style) | *===* |
| [`Type`](#property-type) | *===* |
| [`Visible`](#property-visible) | *===* |
| [`Width`](#property-width) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *===* |





***  
***  
# Методы

## `ChartSeries`<a href="method-chartseries" id="method-chartseries"></a>
===
```csharp
public ChartSeries()
```

***  

## `ChartSeries`<a href="method-chartseries" id="method-chartseries"></a>
===
```csharp
public ChartSeries()
public ChartSeries(ChartSeriesType type, XColor color)
```

`type` <mark style="color:red;">*`ChartSeriesType`*</mark>  
 *===*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *===*  


***  

## `ChartSeries`<a href="method-chartseries" id="method-chartseries"></a>
===
```csharp
public ChartSeries()
public ChartSeries(ChartSeriesType type, XColor color)
public ChartSeries(ChartSeriesType type, XColor color, XDashStyle style)
```

`type` <mark style="color:red;">*`ChartSeriesType`*</mark>  
 *===*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *===*  

`style` <mark style="color:red;">*`XDashStyle`*</mark>  
 *===*  


***  

## `CopyTheme`<a href="method-copytheme" id="method-copytheme"></a>
===
```csharp
public void CopyTheme(ChartSeries chartSeries)
```
`chartSeries` <mark style="color:red;">*`ChartSeries`*</mark>  
 *===*  


***  

## `GetPropertyHasStandardValues`<a href="method-getpropertyhasstandardvalues" id="method-getpropertyhasstandardvalues"></a>
===
```csharp
public bool GetPropertyHasStandardValues(string propertyName)
```
`propertyName` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetPropertyReadOnly`<a href="method-getpropertyreadonly" id="method-getpropertyreadonly"></a>
===
```csharp
public bool GetPropertyReadOnly(string propertyName)
```

***  

## `GetPropertyStandardValues`<a href="method-getpropertystandardvalues" id="method-getpropertystandardvalues"></a>
===
```csharp
public IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetPropertyVisibility`<a href="method-getpropertyvisibility" id="method-getpropertyvisibility"></a>
===
```csharp
public bool GetPropertyVisibility(string propertyName)
```

***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
===
```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `AllColors`<a href="property-allcolors" id="property-allcolors"></a>
===
```csharp
public XColor AllColors {set; }
```  
***

## `Color`<a href="property-color" id="property-color"></a>
===
```csharp
public XColor Color { get; set; }
```  
***

## `Color2`<a href="property-color2" id="property-color2"></a>
===
```csharp
public XColor Color2 { get; set; }
```  
***

## `ColorSplit`<a href="property-colorsplit" id="property-colorsplit"></a>
===
```csharp
public ChartSeriesColorSplit ColorSplit { get; set; }
```  
***

## `DotStyle`<a href="property-dotstyle" id="property-dotstyle"></a>
===
```csharp
public ChartSeriesDotStyle DotStyle { get; set; }
```  
***

## `ShowMarker`<a href="property-showmarker" id="property-showmarker"></a>
===
```csharp
public bool ShowMarker { get; set; }
```  
***

## `Style`<a href="property-style" id="property-style"></a>
===
```csharp
public XDashStyle Style { get; set; }
```  
***

## `Type`<a href="property-type" id="property-type"></a>
===
```csharp
public ChartSeriesType Type { get; set; }
```  
***

## `Visible`<a href="property-visible" id="property-visible"></a>
===
```csharp
public bool Visible { get; set; }
```  
***

## `Width`<a href="property-width" id="property-width"></a>
===
```csharp
public int Width { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

