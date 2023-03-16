
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


Описание

### Синтаксис
```csharp
public sealed class ChartSeries : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartSeries`](#ChartSeries-m) | *Описание* |
| [`CopyTheme`](#CopyTheme-m) | *Описание* |
| [`GetPropertyHasStandardValues`](#GetPropertyHasStandardValues-m) | *Описание* |
| [`GetPropertyReadOnly`](#GetPropertyReadOnly-m) | *Описание* |
| [`GetPropertyStandardValues`](#GetPropertyStandardValues-m) | *Описание* |
| [`GetPropertyVisibility`](#GetPropertyVisibility-m) | *Описание* |
| [`ToString`](#ToString-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AllColors`](#AllColors-p) | *Описание* |
| [`Color`](#Color-p) | *Описание* |
| [`Color2`](#Color2-p) | *Описание* |
| [`ColorSplit`](#ColorSplit-p) | *Описание* |
| [`DotStyle`](#DotStyle-p) | *Описание* |
| [`ShowMarker`](#ShowMarker-p) | *Описание* |
| [`Style`](#Style-p) | *Описание* |
| [`Type`](#Type-p) | *Описание* |
| [`Visible`](#Visible-p) | *Описание* |
| [`Width`](#Width-p) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#PropertyChanged-p) | *Описание* |





***  
***  
# Методы

## `ChartSeries`<a href="ChartSeries-m" id="ChartSeries-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeries()
```

***  

## `ChartSeries`<a href="ChartSeries-m" id="ChartSeries-m"></a>
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

## `ChartSeries`<a href="ChartSeries-m" id="ChartSeries-m"></a>
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

## `CopyTheme`<a href="CopyTheme-m" id="CopyTheme-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CopyTheme(ChartSeries chartSeries)
```
`chartSeries` <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  


***  

## `GetPropertyHasStandardValues`<a href="GetPropertyHasStandardValues-m" id="GetPropertyHasStandardValues-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool GetPropertyHasStandardValues(string propertyName)
```
`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyReadOnly`<a href="GetPropertyReadOnly-m" id="GetPropertyReadOnly-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool GetPropertyReadOnly(string propertyName)
```

***  

## `GetPropertyStandardValues`<a href="GetPropertyStandardValues-m" id="GetPropertyStandardValues-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyVisibility`<a href="GetPropertyVisibility-m" id="GetPropertyVisibility-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool GetPropertyVisibility(string propertyName)
```

***  

## `ToString`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `AllColors`<a href="AllColors-p" id="AllColors-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor AllColors {set; }
```  
***

## `Color`<a href="Color-p" id="Color-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color { get; set; }
```  
***

## `Color2`<a href="Color2-p" id="Color2-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color2 { get; set; }
```  
***

## `ColorSplit`<a href="ColorSplit-p" id="ColorSplit-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeriesColorSplit ColorSplit { get; set; }
```  
***

## `DotStyle`<a href="DotStyle-p" id="DotStyle-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeriesDotStyle DotStyle { get; set; }
```  
***

## `ShowMarker`<a href="ShowMarker-p" id="ShowMarker-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowMarker { get; set; }
```  
***

## `Style`<a href="Style-p" id="Style-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle Style { get; set; }
```  
***

## `Type`<a href="Type-p" id="Type-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeriesType Type { get; set; }
```  
***

## `Visible`<a href="Visible-p" id="Visible-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Visible { get; set; }
```  
***

## `Width`<a href="Width-p" id="Width-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Width { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="PropertyChanged-p" id="PropertyChanged-p"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

