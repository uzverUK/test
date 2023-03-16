
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


===

### Синтаксис
```csharp
public abstract class IndicatorSourceBase : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CloneSource`](#method-clonesource) | *===* |
| [`CopySettings`](#method-copysettings) | *===* |
| [`GetSeries`](#method-getseries) | *===* |
| [`GetSeriesList`](#method-getserieslist) | *===* |
| [`IndicatorSourceBase`](#method-indicatorsourcebase) | *===* |
| [`OnPropertyChanged`](#method-onpropertychanged) | *===* |
| [`SetSources`](#method-setsources) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Name`](#property-name) | *===* |
| [`SelectedSeries`](#property-selectedseries) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *===* |





***  
***  
# Методы

## `CloneSource`<a href="method-clonesource" id="method-clonesource"></a>
===
```csharp
public IndicatorSourceBase CloneSource()
```

***  

## `CopySettings`<a href="method-copysettings" id="method-copysettings"></a>
===
```csharp
public abstract void CopySettings(IndicatorSourceBase source)
```

`source` <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *===*  


***  

## `GetSeries`<a href="method-getseries" id="method-getseries"></a>
===
```csharp
public abstract double[] GetSeries(IndicatorsHelper helper)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *===*  


***  

## `GetSeriesList`<a href="method-getserieslist" id="method-getserieslist"></a>
===
```csharp
public abstract IEnumerable<string> GetSeriesList()
```

***  

## `IndicatorSourceBase`<a href="method-indicatorsourcebase" id="method-indicatorsourcebase"></a>
===
```csharp
protected IndicatorSourceBase()
```

***  

## `OnPropertyChanged`<a href="method-onpropertychanged" id="method-onpropertychanged"></a>
===
```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `SetSources`<a href="method-setsources" id="method-setsources"></a>
===
```csharp
public static void SetSources(List<Type> sources)
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

## `Name`<a href="property-name" id="property-name"></a>
===
```csharp
public string Name { get; }
```  
***

## `SelectedSeries`<a href="property-selectedseries" id="property-selectedseries"></a>
===
```csharp
public string SelectedSeries { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

