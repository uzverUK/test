
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public abstract class IndicatorSourceBase : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CloneSource`](./IndicatorSourceBase.cs/Методы/CloneSource.md) | *Описание* |
| [`CopySettings`](./IndicatorSourceBase.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./IndicatorSourceBase.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./IndicatorSourceBase.cs/Методы/GetSeriesList.md) | *Описание* |
| [`IndicatorSourceBase`](./IndicatorSourceBase.cs/Методы/IndicatorSourceBase.md) | *Описание* |
| [`OnPropertyChanged`](./IndicatorSourceBase.cs/Методы/OnPropertyChanged.md) | *Описание* |
| [`SetSources`](./IndicatorSourceBase.cs/Методы/SetSources.md) | *Описание* |
| [`ToString`](./IndicatorSourceBase.cs/Методы/ToString.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Name`](./IndicatorSourceBase.cs/Свойства/Name.md) | *Описание* |
| [`SelectedSeries`](./IndicatorSourceBase.cs/Свойства/SelectedSeries.md) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./IndicatorSourceBase.cs/События/PropertyChanged.md) | *Описание* |





***  
***  
# Методы

## `CloneSource<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSourceBase CloneSource()
```

***  

## `CopySettings<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public abstract void CopySettings(IndicatorSourceBase source)
```

`source` <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  


***  

## `GetSeries<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public abstract double[] GetSeries(IndicatorsHelper helper)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  


***  

## `GetSeriesList<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public abstract IEnumerable<string> GetSeriesList()
```

***  

## `IndicatorSourceBase<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorSourceBase()
```

***  

## `OnPropertyChanged<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `SetSources<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetSources(List<Type> sources)
```

***  

## `ToString<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Name`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `SelectedSeries`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SelectedSeries { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

