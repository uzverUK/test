
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


Описание

### Синтаксис
```csharp
public sealed class ChartSeries : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartSeries`](#method-chartseries) | *Описание* |
| [`CopyTheme`](#method-copytheme) | *Описание* |
| [`GetPropertyHasStandardValues`](#method-getpropertyhasstandardvalues) | *Описание* |
| [`GetPropertyReadOnly`](#method-getpropertyreadonly) | *Описание* |
| [`GetPropertyStandardValues`](#method-getpropertystandardvalues) | *Описание* |
| [`GetPropertyVisibility`](#method-getpropertyvisibility) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AllColors`](#property-allcolors) | *Описание* |
| [`Color`](#property-color) | *Описание* |
| [`Color2`](#property-color2) | *Описание* |
| [`ColorSplit`](#property-colorsplit) | *Описание* |
| [`DotStyle`](#property-dotstyle) | *Описание* |
| [`ShowMarker`](#property-showmarker) | *Описание* |
| [`Style`](#property-style) | *Описание* |
| [`Type`](#property-type) | *Описание* |
| [`Visible`](#property-visible) | *Описание* |
| [`Width`](#property-width) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *Описание* |





***  
***  
# Методы

## `ChartSeries`<a href="method-chartseries" id="method-chartseries"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeries()
```

***  

## `ChartSeries`<a href="method-chartseries" id="method-chartseries"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeries()
public ChartSeries(ChartSeriesType type, XColor color)
```

`type` <mark style="color:red;">*`ChartSeriesType`*</mark>  
 *Описание*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  


***  

## `ChartSeries`<a href="method-chartseries" id="method-chartseries"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeries()
public ChartSeries(ChartSeriesType type, XColor color)
public ChartSeries(ChartSeriesType type, XColor color, XDashStyle style)
```

`type` <mark style="color:red;">*`ChartSeriesType`*</mark>  
 *Описание*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`XDashStyle`*</mark>  
 *Описание*  


***  

## `CopyTheme`<a href="method-copytheme" id="method-copytheme"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CopyTheme(ChartSeries chartSeries)
```
`chartSeries` <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  


***  

## `GetPropertyHasStandardValues`<a href="method-getpropertyhasstandardvalues" id="method-getpropertyhasstandardvalues"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool GetPropertyHasStandardValues(string propertyName)
```
`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyReadOnly`<a href="method-getpropertyreadonly" id="method-getpropertyreadonly"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool GetPropertyReadOnly(string propertyName)
```

***  

## `GetPropertyStandardValues`<a href="method-getpropertystandardvalues" id="method-getpropertystandardvalues"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyVisibility`<a href="method-getpropertyvisibility" id="method-getpropertyvisibility"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool GetPropertyVisibility(string propertyName)
```

***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `AllColors`<a href="property-allcolors" id="property-allcolors"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor AllColors {set; }
```  
***

## `Color`<a href="property-color" id="property-color"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color { get; set; }
```  
***

## `Color2`<a href="property-color2" id="property-color2"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color2 { get; set; }
```  
***

## `ColorSplit`<a href="property-colorsplit" id="property-colorsplit"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeriesColorSplit ColorSplit { get; set; }
```  
***

## `DotStyle`<a href="property-dotstyle" id="property-dotstyle"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeriesDotStyle DotStyle { get; set; }
```  
***

## `ShowMarker`<a href="property-showmarker" id="property-showmarker"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowMarker { get; set; }
```  
***

## `Style`<a href="property-style" id="property-style"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle Style { get; set; }
```  
***

## `Type`<a href="property-type" id="property-type"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeriesType Type { get; set; }
```  
***

## `Visible`<a href="property-visible" id="property-visible"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Visible { get; set; }
```  
***

## `Width`<a href="property-width" id="property-width"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Width { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

