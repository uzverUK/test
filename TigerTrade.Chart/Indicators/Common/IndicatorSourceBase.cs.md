
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public abstract class IndicatorSourceBase : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CloneSource`](#method-clonesource) | *Описание* |
| [`CopySettings`](#method-copysettings) | *Описание* |
| [`GetSeries`](#method-getseries) | *Описание* |
| [`GetSeriesList`](#method-getserieslist) | *Описание* |
| [`IndicatorSourceBase`](#method-indicatorsourcebase) | *Описание* |
| [`OnPropertyChanged`](#method-onpropertychanged) | *Описание* |
| [`SetSources`](#method-setsources) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Name`](#property-name) | *Описание* |
| [`SelectedSeries`](#property-selectedseries) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *Описание* |





***  
***  
# Методы

## `CloneSource`<a href="method-clonesource" id="method-clonesource"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSourceBase CloneSource()
```

***  

## `CopySettings`<a href="method-copysettings" id="method-copysettings"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public abstract void CopySettings(IndicatorSourceBase source)
```

`source` <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  


***  

## `GetSeries`<a href="method-getseries" id="method-getseries"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public abstract double[] GetSeries(IndicatorsHelper helper)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  


***  

## `GetSeriesList`<a href="method-getserieslist" id="method-getserieslist"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public abstract IEnumerable<string> GetSeriesList()
```

***  

## `IndicatorSourceBase`<a href="method-indicatorsourcebase" id="method-indicatorsourcebase"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorSourceBase()
```

***  

## `OnPropertyChanged`<a href="method-onpropertychanged" id="method-onpropertychanged"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `SetSources`<a href="method-setsources" id="method-setsources"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetSources(List<Type> sources)
```

***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Name`<a href="property-name" id="property-name"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `SelectedSeries`<a href="property-selectedseries" id="property-selectedseries"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SelectedSeries { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

