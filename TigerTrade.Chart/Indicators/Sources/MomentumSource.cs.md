
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class MomentumSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./MomentumSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./MomentumSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./MomentumSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`MomentumSource`](./MomentumSource.cs/Методы/MomentumSource.md) | *Описание* |
| [`ToString`](./MomentumSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Period`](./MomentumSource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./MomentumSource.cs/Свойства/Source.md) | *Описание* |





***  
***  
# Методы

## *CopySettings*
Описание

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

<mark style="color:yellow;">`source`</mark> <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  


***                

## *GetSeries*
Описание

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```
<mark style="color:yellow;">`helper`</mark> <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  


***                

## *GetSeriesList*
Описание

```csharp
public override IEnumerable<string> GetSeriesList()
```
<mark style="color:yellow;">`List`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***                

## *MomentumSource*
Описание

```csharp
public MomentumSource()
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

## *Period*
Описание

```csharp
public int Period { get; set; }
```
***

## *Source*
Описание

```csharp
public IndicatorSourceBase Source { get; set; }
```
***

