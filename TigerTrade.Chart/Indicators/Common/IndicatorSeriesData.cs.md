
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public sealed class IndicatorSeriesData
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CachePoints`](./IndicatorSeriesData.cs/Методы/CachePoints.md) | *Описание* |
| [`GetDistance`](./IndicatorSeriesData.cs/Методы/GetDistance.md) | *Описание* |
| [`IndicatorSeriesData`](./IndicatorSeriesData.cs/Методы/IndicatorSeriesData.md) | *Описание* |
| [`MaxValue`](./IndicatorSeriesData.cs/Методы/MaxValue.md) | *Описание* |
| [`MinValue`](./IndicatorSeriesData.cs/Методы/MinValue.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Data`](./IndicatorSeriesData.cs/Свойства/Data.md) | *Описание* |
| [`Length`](./IndicatorSeriesData.cs/Свойства/Length.md) | *Описание* |
| [`Style`](./IndicatorSeriesData.cs/Свойства/Style.md) | *Описание* |
| [`UserData`](./IndicatorSeriesData.cs/Свойства/UserData.md) | *Описание* |





# Методы

## `CachePoints`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CachePoints(Point[] points, string pointsName)
```

<mark style="color:purple;">`pointsName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## `GetDistance`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetDistance(double x, double y)
```
<mark style="color:purple;">`x`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:purple;">`y`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## `IndicatorSeriesData`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesData(double[] data)
```


## `IndicatorSeriesData`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
```

<mark style="color:purple;">`style`</mark> <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  

<mark style="color:purple;">`name`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## `IndicatorSeriesData`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
public IndicatorSeriesData(double[] data, ChartRegion style)
```

<mark style="color:purple;">`style`</mark> <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  

<mark style="color:purple;">`name`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:purple;">`style`</mark> <mark style="color:red;">*`ChartRegion`*</mark>  
 *Описание*  



## `IndicatorSeriesData`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
public IndicatorSeriesData(double[] data, ChartRegion style)
public IndicatorSeriesData(double[] data, ChartLine style)
```

<mark style="color:purple;">`style`</mark> <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  

<mark style="color:purple;">`name`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:purple;">`style`</mark> <mark style="color:red;">*`ChartRegion`*</mark>  
 *Описание*  

<mark style="color:purple;">`style`</mark> <mark style="color:red;">*`ChartLine`*</mark>  
 *Описание*  



## `MaxValue`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MaxValue()
```


## `MaxValue`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MaxValue()
public double MaxValue(int start, int count)
```

<mark style="color:purple;">`start`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:purple;">`count`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## `MinValue`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinValue()
```


## `MinValue`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinValue()
public double MinValue(int start, int count)
```

<mark style="color:purple;">`start`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:purple;">`count`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


# Свойства

## `Data`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Data { get; }
```

## `Length`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Length { get; }
```

## `Style`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeriesStyle Style { get; }
```

## `UserData`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Hashtable UserData { get; }
```

