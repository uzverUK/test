
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public sealed class IndicatorSeriesData
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CachePoints`](#CachePoints-m) | *Описание* |
| [`GetDistance`](#GetDistance-m) | *Описание* |
| [`IndicatorSeriesData`](#IndicatorSeriesData-m) | *Описание* |
| [`MaxValue`](#MaxValue-m) | *Описание* |
| [`MinValue`](#MinValue-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Data`](#Data-p) | *Описание* |
| [`Length`](#Length-p) | *Описание* |
| [`Style`](#Style-p) | *Описание* |
| [`UserData`](#UserData-p) | *Описание* |





***  
***  
# Методы

## `CachePoints`<a href="CachePoints-m" id="CachePoints-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CachePoints(Point[] points, string pointsName)
```

`pointsName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetDistance`<a href="GetDistance-m" id="GetDistance-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetDistance(double x, double y)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `IndicatorSeriesData`<a href="IndicatorSeriesData-m" id="IndicatorSeriesData-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesData(double[] data)
```

***  

## `IndicatorSeriesData`<a href="IndicatorSeriesData-m" id="IndicatorSeriesData-m"></a>
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

## `IndicatorSeriesData`<a href="IndicatorSeriesData-m" id="IndicatorSeriesData-m"></a>
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

## `IndicatorSeriesData`<a href="IndicatorSeriesData-m" id="IndicatorSeriesData-m"></a>
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

## `MaxValue`<a href="MaxValue-m" id="MaxValue-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MaxValue()
```

***  

## `MaxValue`<a href="MaxValue-m" id="MaxValue-m"></a>
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

## `MinValue`<a href="MinValue-m" id="MinValue-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinValue()
```

***  

## `MinValue`<a href="MinValue-m" id="MinValue-m"></a>
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

## `Data`<a href="Data-p" id="Data-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Data { get; }
```  
***

## `Length`<a href="Length-p" id="Length-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Length { get; }
```  
***

## `Style`<a href="Style-p" id="Style-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesStyle Style { get; }
```  
***

## `UserData`<a href="UserData-p" id="UserData-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Hashtable UserData { get; }
```  
***

