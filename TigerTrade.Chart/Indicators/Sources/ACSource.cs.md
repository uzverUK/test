
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


===

### Синтаксис
```csharp
public sealed class ACSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ACSource`](#method-acsource) | *===* |
| [`CopySettings`](#method-copysettings) | *===* |
| [`GetSeries`](#method-getseries) | *===* |
| [`GetSeriesList`](#method-getserieslist) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`LongPeriod`](#property-longperiod) | *===* |
| [`MaType`](#property-matype) | *===* |
| [`ShortPeriod`](#property-shortperiod) | *===* |





***  
***  
# Методы

## `ACSource`<a href="method-acsource" id="method-acsource"></a>
===
```csharp
public ACSource()
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

## `LongPeriod`<a href="property-longperiod" id="property-longperiod"></a>
===
```csharp
public int LongPeriod { get; set; }
```  
***

## `MaType`<a href="property-matype" id="property-matype"></a>
===
```csharp
public IndicatorMaType MaType { get; set; }
```  
***

## `ShortPeriod`<a href="property-shortperiod" id="property-shortperiod"></a>
===
```csharp
public int ShortPeriod { get; set; }
```  
***

