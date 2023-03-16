# IndicatorSourceBase

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Common](./)

\===

#### Синтаксис

```csharp
public abstract class IndicatorSourceBase : INotifyPropertyChanged
```

## Список методов

| Название                                                                      | Описание |
| ----------------------------------------------------------------------------- | -------- |
| [`CloneSource`](indicatorsourcebase.cs.md#method-clonesource)                 | _===_    |
| [`CopySettings`](indicatorsourcebase.cs.md#method-copysettings)               | _===_    |
| [`GetSeries`](indicatorsourcebase.cs.md#method-getseries)                     | _===_    |
| [`GetSeriesList`](indicatorsourcebase.cs.md#method-getserieslist)             | _===_    |
| [`IndicatorSourceBase`](indicatorsourcebase.cs.md#method-indicatorsourcebase) | _===_    |
| [`OnPropertyChanged`](indicatorsourcebase.cs.md#method-onpropertychanged)     | _===_    |
| [`SetSources`](indicatorsourcebase.cs.md#method-setsources)                   | _===_    |
| [`ToString`](indicatorsourcebase.cs.md#method-tostring)                       | _===_    |

## Список свойств

| Название                                                              | Описание |
| --------------------------------------------------------------------- | -------- |
| [`Name`](indicatorsourcebase.cs.md#property-name)                     | _===_    |
| [`SelectedSeries`](indicatorsourcebase.cs.md#property-selectedseries) | _===_    |

## Список событий

| Название                                                             | Описание |
| -------------------------------------------------------------------- | -------- |
| [`PropertyChanged`](indicatorsourcebase.cs.md#event-propertychanged) | _===_    |

***

***

## Методы

### `CloneSource` <a href="#method-clonesource" id="method-clonesource"></a>

\===

```csharp
public IndicatorSourceBase CloneSource()
```

***

### `CopySettings` <a href="#method-copysettings" id="method-copysettings"></a>

\===

```csharp
public abstract void CopySettings(IndicatorSourceBase source)
```

`source` _<mark style="color:red;">`IndicatorSourceBase`</mark>_\
_===_

***

### `GetSeries` <a href="#method-getseries" id="method-getseries"></a>

\===

```csharp
public abstract double[] GetSeries(IndicatorsHelper helper)
```

`helper` _<mark style="color:red;">`IndicatorsHelper`</mark>_\
_===_

***

### `GetSeriesList` <a href="#method-getserieslist" id="method-getserieslist"></a>

\===

```csharp
public abstract IEnumerable<string> GetSeriesList()
```

***

### `IndicatorSourceBase` <a href="#method-indicatorsourcebase" id="method-indicatorsourcebase"></a>

\===

```csharp
protected IndicatorSourceBase()
```

***

### `OnPropertyChanged` <a href="#method-onpropertychanged" id="method-onpropertychanged"></a>

\===

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `SetSources` <a href="#method-setsources" id="method-setsources"></a>

\===

```csharp
public static void SetSources(List<Type> sources)
```

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

***

***

***

## Свойства

### `Name` <a href="#property-name" id="property-name"></a>

\===

```csharp
public string Name { get; }
```

***

### `SelectedSeries` <a href="#property-selectedseries" id="property-selectedseries"></a>

\===

```csharp
public string SelectedSeries { get; set; }
```

***

***

***

## События

### `PropertyChanged` <a href="#event-propertychanged" id="event-propertychanged"></a>

\===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```
