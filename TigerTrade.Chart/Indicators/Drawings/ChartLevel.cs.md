
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


===

### Синтаксис
```csharp
public sealed class ChartLevel : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartLevel`](#method-chartlevel) | *===* |
| [`CopyTheme`](#method-copytheme) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Color`](#property-color) | *===* |
| [`Level`](#property-level) | *===* |
| [`LineBrush`](#property-linebrush) | *===* |
| [`LinePen`](#property-linepen) | *===* |
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

## `ChartLevel`<a href="method-chartlevel" id="method-chartlevel"></a>
===
```csharp
public ChartLevel()
```

***  

## `ChartLevel`<a href="method-chartlevel" id="method-chartlevel"></a>
===
```csharp
public ChartLevel()
public ChartLevel(Decimal level, XColor color)
```

`level` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *===*  


***  

## `CopyTheme`<a href="method-copytheme" id="method-copytheme"></a>
===
```csharp
public void CopyTheme(ChartLevel chartLevel)
```
`chartLevel` <mark style="color:red;">*`ChartLevel`*</mark>  
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

## `Level`<a href="property-level" id="property-level"></a>
===
```csharp
public Decimal Level { get; set; }
```  
***

## `LineBrush`<a href="property-linebrush" id="property-linebrush"></a>
===
```csharp
public XBrush LineBrush { get; private set; }
```  
***

## `LinePen`<a href="property-linepen" id="property-linepen"></a>
===
```csharp
public XPen LinePen { get; private set; }
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

