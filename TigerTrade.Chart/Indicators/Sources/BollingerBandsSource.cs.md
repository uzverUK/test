
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class BollingerBandsSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`BollingerBandsSource`](./BollingerBandsSource.cs/Методы/BollingerBandsSource.md) | *Описание* |
| [`CopySettings`](./BollingerBandsSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./BollingerBandsSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./BollingerBandsSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./BollingerBandsSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`MaType`](./BollingerBandsSource.cs/Свойства/MaType.md) | *Описание* |
| [`Period`](./BollingerBandsSource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./BollingerBandsSource.cs/Свойства/Source.md) | *Описание* |
| [`StdDev`](./BollingerBandsSource.cs/Свойства/StdDev.md) | *Описание* |





# Методы

## *BollingerBandsSource*
Описание

```csharp
public BollingerBandsSource()
```


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

## *StdDev*
Описание

```csharp
public Decimal StdDev { get; set; }
```

