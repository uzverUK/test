
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


Описание

### Синтаксис
```csharp
public sealed class ChartSeries : INotifyPropertyChanged, IDynamicProperty
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ChartSeries`](./ChartSeries.cs/Методы/ChartSeries.md) | *Описание* |
| [`CopyTheme`](./ChartSeries.cs/Методы/CopyTheme.md) | *Описание* |
| [`GetPropertyHasStandardValues`](./ChartSeries.cs/Методы/GetPropertyHasStandardValues.md) | *Описание* |
| [`GetPropertyReadOnly`](./ChartSeries.cs/Методы/GetPropertyReadOnly.md) | *Описание* |
| [`GetPropertyStandardValues`](./ChartSeries.cs/Методы/GetPropertyStandardValues.md) | *Описание* |
| [`GetPropertyVisibility`](./ChartSeries.cs/Методы/GetPropertyVisibility.md) | *Описание* |
| [`ToString`](./ChartSeries.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`AllColors`](./ChartSeries.cs/Свойства/AllColors.md) | *Описание* |
| [`Color`](./ChartSeries.cs/Свойства/Color.md) | *Описание* |
| [`Color2`](./ChartSeries.cs/Свойства/Color2.md) | *Описание* |
| [`ColorSplit`](./ChartSeries.cs/Свойства/ColorSplit.md) | *Описание* |
| [`DotStyle`](./ChartSeries.cs/Свойства/DotStyle.md) | *Описание* |
| [`ShowMarker`](./ChartSeries.cs/Свойства/ShowMarker.md) | *Описание* |
| [`Style`](./ChartSeries.cs/Свойства/Style.md) | *Описание* |
| [`Type`](./ChartSeries.cs/Свойства/Type.md) | *Описание* |
| [`Visible`](./ChartSeries.cs/Свойства/Visible.md) | *Описание* |
| [`Width`](./ChartSeries.cs/Свойства/Width.md) | *Описание* |

# Таблица событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ChartSeries.cs/События/PropertyChanged.md) | *Описание* |





# Методы

## *ChartSeries*
Описание

```csharp
public ChartSeries()
```


## *ChartSeries*
Описание

```csharp
public ChartSeries()
public ChartSeries(ChartSeriesType type, XColor color)
```

<mark style="color:yellow;">`type`</mark> <mark style="color:red;">*`ChartSeriesType`*</mark>  
 *Описание*  

<mark style="color:yellow;">`color`</mark> <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  



## *ChartSeries*
Описание

```csharp
public ChartSeries()
public ChartSeries(ChartSeriesType type, XColor color)
public ChartSeries(ChartSeriesType type, XColor color, XDashStyle style)
```

<mark style="color:yellow;">`type`</mark> <mark style="color:red;">*`ChartSeriesType`*</mark>  
 *Описание*  

<mark style="color:yellow;">`color`</mark> <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`XDashStyle`*</mark>  
 *Описание*  



## *CopyTheme*
Описание

```csharp
public void CopyTheme(ChartSeries chartSeries)
```
<mark style="color:yellow;">`chartSeries`</mark> <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  



## *GetPropertyHasStandardValues*
Описание

```csharp
public bool GetPropertyHasStandardValues(string propertyName)
```
<mark style="color:yellow;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *GetPropertyReadOnly*
Описание

```csharp
public bool GetPropertyReadOnly(string propertyName)
```


## *GetPropertyStandardValues*
Описание

```csharp
public IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

<mark style="color:yellow;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *GetPropertyVisibility*
Описание

```csharp
public bool GetPropertyVisibility(string propertyName)
```


## *ToString*
Описание

```csharp
public override string ToString()
```

# Свойства

## *AllColors*
> Описание

```csharp
public XColor AllColors {set; }
```

## *Color*
> Описание

```csharp
public XColor Color { get; set; }
```

## *Color2*
> Описание

```csharp
public XColor Color2 { get; set; }
```

## *ColorSplit*
> Описание

```csharp
public ChartSeriesColorSplit ColorSplit { get; set; }
```

## *DotStyle*
> Описание

```csharp
public ChartSeriesDotStyle DotStyle { get; set; }
```

## *ShowMarker*
> Описание

```csharp
public bool ShowMarker { get; set; }
```

## *Style*
> Описание

```csharp
public XDashStyle Style { get; set; }
```

## *Type*
> Описание

```csharp
public ChartSeriesType Type { get; set; }
```

## *Visible*
> Описание

```csharp
public bool Visible { get; set; }
```

## *Width*
> Описание

```csharp
public int Width { get; set; }
```
# <font color="Purple">Событияs</font>

## *PropertyChanged*
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

