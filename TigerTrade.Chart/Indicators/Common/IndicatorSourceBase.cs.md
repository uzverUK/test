
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public abstract class IndicatorSourceBase : INotifyPropertyChanged
```


# Таблица методов
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

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Name`](./IndicatorSourceBase.cs/Свойства/Name.md) | *Описание* |
| [`SelectedSeries`](./IndicatorSourceBase.cs/Свойства/SelectedSeries.md) | *Описание* |

# Таблица событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./IndicatorSourceBase.cs/События/PropertyChanged.md) | *Описание* |





# Методы

## `CloneSource`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSourceBase CloneSource()
```


## `CopySettings`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public abstract void CopySettings(IndicatorSourceBase source)
```

`source` <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  



## `GetSeries`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public abstract double[] GetSeries(IndicatorsHelper helper)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  



## `GetSeriesList`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public abstract IEnumerable<string> GetSeriesList()
```


## `IndicatorSourceBase`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorSourceBase()
```


## `OnPropertyChanged`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## `SetSources`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetSources(List<Type> sources)
```


## `ToString`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

# Свойства

## `Name`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```

## `SelectedSeries`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SelectedSeries { get; set; }
```
# События

## `PropertyChanged`
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

