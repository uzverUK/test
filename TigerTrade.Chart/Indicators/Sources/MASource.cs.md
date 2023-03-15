
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class MASource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./MASource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./MASource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./MASource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`MASource`](./MASource.cs/Методы/MASource.md) | *Описание* |
| [`ToString`](./MASource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`MaType`](./MASource.cs/Свойства/MaType.md) | *Описание* |
| [`Period`](./MASource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./MASource.cs/Свойства/Source.md) | *Описание* |





# Методы

## *CopySettings*
Описание

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

<mark style="color:yellow;">`source`</mark> <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  



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



## *MASource*
Описание

```csharp
public MASource()
```


## *ToString*
Описание

```csharp
public override string ToString()
```

# Свойства

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

