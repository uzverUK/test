
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


===

### Синтаксис
```csharp
public sealed class EnvelopesSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](#method-copysettings) | *===* |
| [`EnvelopesSource`](#method-envelopessource) | *===* |
| [`GetSeries`](#method-getseries) | *===* |
| [`GetSeriesList`](#method-getserieslist) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Factor`](#property-factor) | *===* |
| [`MaType`](#property-matype) | *===* |
| [`Period`](#property-period) | *===* |
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

## `EnvelopesSource`<a href="method-envelopessource" id="method-envelopessource"></a>
===
```csharp
public EnvelopesSource()
```

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

## `Factor`<a href="property-factor" id="property-factor"></a>
===
```csharp
public int Factor { get; set; }
```  
***

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

