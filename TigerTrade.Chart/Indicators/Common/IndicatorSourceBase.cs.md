
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





***  
***  
# Методы

## *CloneSource*
Описание

```csharp
public IndicatorSourceBase CloneSource()
```

***                

## *CopySettings*
Описание

```csharp
public abstract void CopySettings(IndicatorSourceBase source)
```

<mark style="color:yellow;">`source`</mark> <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  


***                

## *GetSeries*
Описание

```csharp
public abstract double[] GetSeries(IndicatorsHelper helper)
```
<mark style="color:yellow;">`helper`</mark> <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  


***                

## *GetSeriesList*
Описание

```csharp
public abstract IEnumerable<string> GetSeriesList()
```

***                

## *IndicatorSourceBase*
Описание

```csharp
protected IndicatorSourceBase()
```

***                

## *OnPropertyChanged*
Описание

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

<mark style="color:yellow;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***                

## *SetSources*
Описание

```csharp
public static void SetSources(List<Type> sources)
```

***                

## *ToString*
Описание

```csharp
public override string ToString()
```

***                
***
  ***
  # Свойства

## *Name*
Описание

```csharp
public string Name { get; }
```
***

## *SelectedSeries*
Описание

```csharp
public string SelectedSeries { get; set; }
```
***
***
  ***
  # События

## *PropertyChanged*
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```
***

