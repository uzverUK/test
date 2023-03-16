
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


===

### Синтаксис
```csharp
public sealed class MACDSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](#method-copysettings) | *===* |
| [`GetSeries`](#method-getseries) | *===* |
| [`GetSeriesList`](#method-getserieslist) | *===* |
| [`MACDSource`](#method-macdsource) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Fast`](#property-fast) | *===* |
| [`Signal`](#property-signal) | *===* |
| [`Slow`](#property-slow) | *===* |
| [`Source`](#property-source) | *===* |





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

## `MACDSource`<a href="method-macdsource" id="method-macdsource"></a>
===
```csharp
public MACDSource()
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

## `Fast`<a href="property-fast" id="property-fast"></a>
===
```csharp
public int Fast { get; set; }
```  
***

## `Signal`<a href="property-signal" id="property-signal"></a>
===
```csharp
public int Signal { get; set; }
```  
***

## `Slow`<a href="property-slow" id="property-slow"></a>
===
```csharp
public int Slow { get; set; }
```  
***

## `Source`<a href="property-source" id="property-source"></a>
===
```csharp
public IndicatorSourceBase Source { get; set; }
```  
***

