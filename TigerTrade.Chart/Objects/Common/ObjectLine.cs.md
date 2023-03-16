
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


===

### Синтаксис
```csharp
public sealed class ObjectLine : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ObjectLine`](#method-objectline) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`LineBrush`](#property-linebrush) | *===* |
| [`LineColor`](#property-linecolor) | *===* |
| [`LinePen`](#property-linepen) | *===* |
| [`LineStyle`](#property-linestyle) | *===* |
| [`LineWidth`](#property-linewidth) | *===* |
| [`ShowLine`](#property-showline) | *===* |
| [`Value`](#property-value) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *===* |





***  
***  
# Методы

## `ObjectLine`<a href="method-objectline" id="method-objectline"></a>
===
```csharp
public ObjectLine()
```

***  

## `ObjectLine`<a href="method-objectline" id="method-objectline"></a>
===
```csharp
public ObjectLine()
public ObjectLine(double value, XColor color)
```

`value` <mark style="color:red;">*`double`*</mark>  
 *===*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *===*  


***  

## `ObjectLine`<a href="method-objectline" id="method-objectline"></a>
===
```csharp
public ObjectLine()
public ObjectLine(double value, XColor color)
public ObjectLine(ObjectLine line)
```

`value` <mark style="color:red;">*`double`*</mark>  
 *===*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *===*  

`line` <mark style="color:red;">*`ObjectLine`*</mark>  
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

## `LineBrush`<a href="property-linebrush" id="property-linebrush"></a>
===
```csharp
public XBrush LineBrush { get; private set; }
```  
***

## `LineColor`<a href="property-linecolor" id="property-linecolor"></a>
===
```csharp
public XColor LineColor { get; set; }
```  
***

## `LinePen`<a href="property-linepen" id="property-linepen"></a>
===
```csharp
public XPen LinePen { get; private set; }
```  
***

## `LineStyle`<a href="property-linestyle" id="property-linestyle"></a>
===
```csharp
public XDashStyle LineStyle { get; set; }
```  
***

## `LineWidth`<a href="property-linewidth" id="property-linewidth"></a>
===
```csharp
public int LineWidth { get; set; }
```  
***

## `ShowLine`<a href="property-showline" id="property-showline"></a>
===
```csharp
public bool ShowLine { get; set; }
```  
***

## `Value`<a href="property-value" id="property-value"></a>
===
```csharp
public double Value { get; set; }
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

