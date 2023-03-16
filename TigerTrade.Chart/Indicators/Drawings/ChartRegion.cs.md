
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


===

### Синтаксис
```csharp
public sealed class ChartRegion : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartRegion`](#method-chartregion) | *===* |
| [`CopyTheme`](#method-copytheme) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Color`](#property-color) | *===* |
| [`Visible`](#property-visible) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *===* |





***  
***  
# Методы

## `ChartRegion`<a href="method-chartregion" id="method-chartregion"></a>
===
```csharp
public ChartRegion()
```

***  

## `ChartRegion`<a href="method-chartregion" id="method-chartregion"></a>
===
```csharp
public ChartRegion()
public ChartRegion(XColor color)
```

`color` <mark style="color:red;">*`XColor`*</mark>  
 *===*  


***  

## `CopyTheme`<a href="method-copytheme" id="method-copytheme"></a>
===
```csharp
public void CopyTheme(ChartRegion chartRegion)
```
`chartRegion` <mark style="color:red;">*`ChartRegion`*</mark>  
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

## `Visible`<a href="property-visible" id="property-visible"></a>
===
```csharp
public bool Visible { get; set; }
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

