
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


===

### Синтаксис
```csharp
public sealed class IchimokuSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](#method-copysettings) | *===* |
| [`GetSeries`](#method-getseries) | *===* |
| [`GetSeriesList`](#method-getserieslist) | *===* |
| [`IchimokuSource`](#method-ichimokusource) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Period1`](#property-period1) | *===* |
| [`Period2`](#property-period2) | *===* |
| [`Period3`](#property-period3) | *===* |
| [`Period4`](#property-period4) | *===* |
| [`Period5`](#property-period5) | *===* |





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

## `IchimokuSource`<a href="method-ichimokusource" id="method-ichimokusource"></a>
===
```csharp
public IchimokuSource()
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

## `Period4`<a href="property-period4" id="property-period4"></a>
===
```csharp
public int Period4 { get; set; }
```  
***

## `Period5`<a href="property-period5" id="property-period5"></a>
===
```csharp
public int Period5 { get; set; }
```  
***

