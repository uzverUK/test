
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class EldersForceIndexSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./EldersForceIndexSource.cs/Методы/CopySettings.md) | *Описание* |
| [`EldersForceIndexSource`](./EldersForceIndexSource.cs/Методы/EldersForceIndexSource.md) | *Описание* |
| [`GetSeries`](./EldersForceIndexSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./EldersForceIndexSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./EldersForceIndexSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`MaType`](./EldersForceIndexSource.cs/Свойства/MaType.md) | *Описание* |
| [`Period`](./EldersForceIndexSource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./EldersForceIndexSource.cs/Свойства/Source.md) | *Описание* |





# Методы

## *CopySettings*
Описание

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

<mark style="color:yellow;">`source`</mark> <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  



## *EldersForceIndexSource*
Описание

```csharp
public EldersForceIndexSource()
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

## *MaType*
Описание

```csharp
public IndicatorMaType MaType { get; set; }
```

## *Period*
Описание

```csharp
public int Period { get; set; }
```

## *Source*
Описание

```csharp
public IndicatorSourceBase Source { get; set; }
```

