
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


===

### Синтаксис
```csharp
public sealed class CandlePatternSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CandlePatternSource`](#method-candlepatternsource) | *===* |
| [`CopySettings`](#method-copysettings) | *===* |
| [`GetSeries`](#method-getseries) | *===* |
| [`GetSeriesList`](#method-getserieslist) | *===* |
| [`SearchPattern`](#method-searchpattern) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`PatternType`](#property-patterntype) | *===* |
| [`Penetration`](#property-penetration) | *===* |





***  
***  
# Методы

## `CandlePatternSource`<a href="method-candlepatternsource" id="method-candlepatternsource"></a>
===
```csharp
public CandlePatternSource()
```

***  

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

## `SearchPattern`<a href="method-searchpattern" id="method-searchpattern"></a>
===
```csharp
public double[] SearchPattern(IndicatorsHelper helper, CandlePatternSourcePatternType type)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *===*  

`type` <mark style="color:red;">*`CandlePatternSourcePatternType`*</mark>  
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

## `PatternType`<a href="property-patterntype" id="property-patterntype"></a>
===
```csharp
public CandlePatternSourcePatternType PatternType { get; set; }
```  
***

## `Penetration`<a href="property-penetration" id="property-penetration"></a>
===
```csharp
public double Penetration { get; set; }
```  
***

