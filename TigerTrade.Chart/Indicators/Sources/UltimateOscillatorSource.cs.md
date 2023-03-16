
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


===

### Синтаксис
```csharp
public sealed class UltimateOscillatorSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](#method-copysettings) | *===* |
| [`GetSeries`](#method-getseries) | *===* |
| [`GetSeriesList`](#method-getserieslist) | *===* |
| [`ToString`](#method-tostring) | *===* |
| [`UltimateOscillatorSource`](#method-ultimateoscillatorsource) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Period1`](#property-period1) | *===* |
| [`Period2`](#property-period2) | *===* |
| [`Period3`](#property-period3) | *===* |





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

## `ToString`<a href="method-tostring" id="method-tostring"></a>
===
```csharp
public override string ToString()
```

***  

## `UltimateOscillatorSource`<a href="method-ultimateoscillatorsource" id="method-ultimateoscillatorsource"></a>
===
```csharp
public UltimateOscillatorSource()
```

***  
***  
 ***  
# Свойства

## `Period1`<a href="property-period1" id="property-period1"></a>
===
```csharp
public int Period1 { get; set; }
```  
***

## `Period2`<a href="property-period2" id="property-period2"></a>
===
```csharp
public int Period2 { get; set; }
```  
***

## `Period3`<a href="property-period3" id="property-period3"></a>
===
```csharp
public int Period3 { get; set; }
```  
***

