
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


===

### Синтаксис
```csharp
public sealed class CMOSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CMOSource`](#method-cmosource) | *===* |
| [`CopySettings`](#method-copysettings) | *===* |
| [`GetSeries`](#method-getseries) | *===* |
| [`GetSeriesList`](#method-getserieslist) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Period`](#property-period) | *===* |
| [`Source`](#property-source) | *===* |





***  
***  
# Методы

## `CMOSource`<a href="method-cmosource" id="method-cmosource"></a>
===
```csharp
public CMOSource()
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

## `ToString`<a href="method-tostring" id="method-tostring"></a>
===
```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Period`<a href="property-period" id="property-period"></a>
===
```csharp
public int Period { get; set; }
```  
***

## `Source`<a href="property-source" id="property-source"></a>
===
```csharp
public IndicatorSourceBase Source { get; set; }
```  
***

