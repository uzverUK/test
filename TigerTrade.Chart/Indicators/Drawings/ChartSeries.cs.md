
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
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeries()
```


## *ChartSeries*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeries()
public ChartSeries(ChartSeriesType type, XColor color)
```

<mark style="color:yellow;">`type`</mark> <mark style="color:red;">*`ChartSeriesType`*</mark>  
 *Описание*  

<mark style="color:yellow;">`color`</mark> <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  



## *ChartSeries*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

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
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CopyTheme(ChartSeries chartSeries)
```
<mark style="color:yellow;">`chartSeries`</mark> <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  



## *GetPropertyHasStandardValues*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool GetPropertyHasStandardValues(string propertyName)
```
<mark style="color:yellow;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *GetPropertyReadOnly*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool GetPropertyReadOnly(string propertyName)
```


## *GetPropertyStandardValues*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

<mark style="color:yellow;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *GetPropertyVisibility*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool GetPropertyVisibility(string propertyName)
```


## *ToString*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

# Свойства

## *AllColors*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor AllColors {set; }
```

## *Color*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color { get; set; }
```

## *Color2*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color2 { get; set; }
```

## *ColorSplit*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeriesColorSplit ColorSplit { get; set; }
```

## *DotStyle*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeriesDotStyle DotStyle { get; set; }
```

## *ShowMarker*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowMarker { get; set; }
```

## *Style*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle Style { get; set; }
```

## *Type*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartSeriesType Type { get; set; }
```

## *Visible*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Visible { get; set; }
```

## *Width*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Width { get; set; }
```
# События

## *PropertyChanged*
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

