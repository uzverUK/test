
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


===

### Синтаксис
```csharp
public sealed class StochasticSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](#method-copysettings) | *===* |
| [`GetSeries`](#method-getseries) | *===* |
| [`GetSeriesList`](#method-getserieslist) | *===* |
| [`StochasticSource`](#method-stochasticsource) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`FastK`](#property-fastk) | *===* |
| [`SlowD`](#property-slowd) | *===* |
| [`SlowDMaType`](#property-slowdmatype) | *===* |
| [`Smooth`](#property-smooth) | *===* |





***  
***  
# Методы

## `CopySettings`<a href="method-copysettings" id="method-copysettings"></a>
===
```csharp
public override void CopySettings(IndicatorSourceBase source)
```

`source` <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *===*  


***  

## `GetSeries`<a href="method-getseries" id="method-getseries"></a>
===
```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *===*  


***  

## `GetSeriesList`<a href="method-getserieslist" id="method-getserieslist"></a>
===
```csharp
public override IEnumerable<string> GetSeriesList()
```
`List` <mark style="color:red;">*`new`*</mark>  
 *===*  


***  

## `StochasticSource`<a href="method-stochasticsource" id="method-stochasticsource"></a>
===
```csharp
public StochasticSource()
```

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

## `FastK`<a href="property-fastk" id="property-fastk"></a>
===
```csharp
public int FastK { get; set; }
```  
***

## `SlowD`<a href="property-slowd" id="property-slowd"></a>
===
```csharp
public int SlowD { get; set; }
```  
***

## `SlowDMaType`<a href="property-slowdmatype" id="property-slowdmatype"></a>
===
```csharp
public IndicatorMaType SlowDMaType { get; set; }
```  
***

## `Smooth`<a href="property-smooth" id="property-smooth"></a>
===
```csharp
public int Smooth { get; set; }
```  
***

