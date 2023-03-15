
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class EnvelopesSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./EnvelopesSource.cs/Методы/CopySettings.md) | *Описание* |
| [`EnvelopesSource`](./EnvelopesSource.cs/Методы/EnvelopesSource.md) | *Описание* |
| [`GetSeries`](./EnvelopesSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./EnvelopesSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./EnvelopesSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Factor`](./EnvelopesSource.cs/Свойства/Factor.md) | *Описание* |
| [`MaType`](./EnvelopesSource.cs/Свойства/MaType.md) | *Описание* |
| [`Period`](./EnvelopesSource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./EnvelopesSource.cs/Свойства/Source.md) | *Описание* |





# Методы

## *CopySettings*
Описание

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

<mark style="color:yellow;">`source`</mark> <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  



## *EnvelopesSource*
Описание

```csharp
public EnvelopesSource()
```


## *GetSeries*
Описание

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```

<mark style="color:yellow;">`helper`</mark> <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  



## *GetSeriesList*
Описание

```csharp
public override IEnumerable<string> GetSeriesList()
```
<mark style="color:yellow;">`List`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  



## *ToString*
Описание

```csharp
public override string ToString()
```

# Свойства

## *Factor*
> Описание

```csharp
public int Factor { get; set; }
```

## *MaType*
> Описание

```csharp
public IndicatorMaType MaType { get; set; }
```

## *Period*
> Описание

```csharp
public int Period { get; set; }
```

## *Source*
> Описание

```csharp
public IndicatorSourceBase Source { get; set; }
```

