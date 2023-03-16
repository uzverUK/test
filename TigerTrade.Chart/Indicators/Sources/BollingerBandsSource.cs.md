
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


===

### Синтаксис
```csharp
public sealed class BollingerBandsSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BollingerBandsSource`](#method-bollingerbandssource) | *===* |
| [`CopySettings`](#method-copysettings) | *===* |
| [`GetSeries`](#method-getseries) | *===* |
| [`GetSeriesList`](#method-getserieslist) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`MaType`](#property-matype) | *===* |
| [`Period`](#property-period) | *===* |
| [`Source`](#property-source) | *===* |
| [`StdDev`](#property-stddev) | *===* |





***  
***  
# Методы

## `BollingerBandsSource`<a href="method-bollingerbandssource" id="method-bollingerbandssource"></a>
===
```csharp
public BollingerBandsSource()
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

## `MaType`<a href="property-matype" id="property-matype"></a>
===
```csharp
public IndicatorMaType MaType { get; set; }
```  
***

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

## `StdDev`<a href="property-stddev" id="property-stddev"></a>
===
```csharp
public Decimal StdDev { get; set; }
```  
***

