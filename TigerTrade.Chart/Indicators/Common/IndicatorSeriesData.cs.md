
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





***  
***  
# Методы

## *CachePoints*
Описание

```csharp
public void CachePoints(Point[] points, string pointsName)
```

<mark style="color:yellow;">`pointsName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***                

## *GetDistance*
Описание

```csharp
public double GetDistance(double x, double y)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***                

## *IndicatorSeriesData*
Описание

```csharp
public IndicatorSeriesData(double[] data)
```

***                

## *IndicatorSeriesData*
Описание

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
```

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  

<mark style="color:yellow;">`name`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***                

## *IndicatorSeriesData*
Описание

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
public IndicatorSeriesData(double[] data, ChartRegion style)
```

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  

<mark style="color:yellow;">`name`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`ChartRegion`*</mark>  
 *Описание*  


***                

## *IndicatorSeriesData*
Описание

```csharp
public IndicatorSeriesData(double[] data)
public IndicatorSeriesData(double[] data, ChartSeries style, string name = "")
public IndicatorSeriesData(double[] data, ChartRegion style)
public IndicatorSeriesData(double[] data, ChartLine style)
```

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`ChartSeries`*</mark>  
 *Описание*  

<mark style="color:yellow;">`name`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`ChartRegion`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`ChartLine`*</mark>  
 *Описание*  


***                

## *MaxValue*
Описание

```csharp
public double MaxValue()
```

***                

## *MaxValue*
Описание

```csharp
public double MaxValue()
public double MaxValue(int start, int count)
```

<mark style="color:yellow;">`start`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`count`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## *MinValue*
Описание

```csharp
public double MinValue()
```

***                

## *MinValue*
Описание

```csharp
public double MinValue()
public double MinValue(int start, int count)
```

<mark style="color:yellow;">`start`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`count`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                
***
  ***
  # Свойства

## *Data*
Описание

```csharp
public double[] Data { get; }
```
***

## *Length*
Описание

```csharp
public int Length { get; }
```
***

## *Style*
Описание

```csharp
public IndicatorSeriesStyle Style { get; }
```
***

## *UserData*
Описание

```csharp
public Hashtable UserData { get; }
```
***

