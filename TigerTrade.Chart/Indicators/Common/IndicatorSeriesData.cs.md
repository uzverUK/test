
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public sealed class IndicatorSeriesData
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CachePoints`](#method-cachepoints) | *Описание* |
| [`GetDistance`](#method-getdistance) | *Описание* |
| [`IndicatorSeriesData`](#method-indicatorseriesdata) | *Описание* |
| [`MaxValue`](#method-maxvalue) | *Описание* |
| [`MinValue`](#method-minvalue) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Data`](#property-data) | *Описание* |
| [`Length`](#property-length) | *Описание* |
| [`Style`](#property-style) | *Описание* |
| [`UserData`](#property-userdata) | *Описание* |





***  
***  
# Методы

## `CachePoints`<a href="method-cachepoints" id="method-cachepoints"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CachePoints(Point[] points, string pointsName)
```

`pointsName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetDistance`<a href="method-getdistance" id="method-getdistance"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetDistance(double x, double y)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `IndicatorSeriesData`<a href="method-indicatorseriesdata" id="method-indicatorseriesdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesData(double[] data)
```

***  

## `IndicatorSeriesData`<a href="method-indicatorseriesdata" id="method-indicatorseriesdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
```

`style` <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  

`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `IndicatorSeriesData`<a href="method-indicatorseriesdata" id="method-indicatorseriesdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
public IndicatorSeriesData(double[] data, ChartRegion style)
```

`style` <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  

`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`ChartRegion`*</mark>  
 *Описание*  


***  

## `IndicatorSeriesData`<a href="method-indicatorseriesdata" id="method-indicatorseriesdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
public IndicatorSeriesData(double[] data, ChartRegion style)
public IndicatorSeriesData(double[] data, ChartLine style)
```

`style` <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  

`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`ChartRegion`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`ChartLine`*</mark>  
 *Описание*  


***  

## `MaxValue`<a href="method-maxvalue" id="method-maxvalue"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MaxValue()
```

***  

## `MaxValue`<a href="method-maxvalue" id="method-maxvalue"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MaxValue()
public double MaxValue(int start, int count)
```

`start` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`count` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `MinValue`<a href="method-minvalue" id="method-minvalue"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinValue()
```

***  

## `MinValue`<a href="method-minvalue" id="method-minvalue"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinValue()
public double MinValue(int start, int count)
```

`start` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`count` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Data`<a href="property-data" id="property-data"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Data { get; }
```  
***

## `Length`<a href="property-length" id="property-length"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Length { get; }
```  
***

## `Style`<a href="property-style" id="property-style"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesStyle Style { get; }
```  
***

## `UserData`<a href="property-userdata" id="property-userdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Hashtable UserData { get; }
```  
***

