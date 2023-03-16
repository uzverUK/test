
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


===

### Синтаксис
```csharp
public sealed class ChartLine : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartLine`](#method-chartline) | *===* |
| [`CopyTheme`](#method-copytheme) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Color`](#property-color) | *===* |
| [`ShowMarker`](#property-showmarker) | *===* |
| [`Style`](#property-style) | *===* |
| [`Visible`](#property-visible) | *===* |
| [`Width`](#property-width) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *===* |





***  
***  
# Методы

## `ChartLine`<a href="method-chartline" id="method-chartline"></a>
===
```csharp
public ChartLine()
```

***  

## `CopyTheme`<a href="method-copytheme" id="method-copytheme"></a>
===
```csharp
public void CopyTheme(ChartLine chartLine)
```

`chartLine` <mark style="color:red;">*`ChartLine`*</mark>  
 *===*  


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

## `Color`<a href="property-color" id="property-color"></a>
===
```csharp
public XColor Color { get; set; }
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

