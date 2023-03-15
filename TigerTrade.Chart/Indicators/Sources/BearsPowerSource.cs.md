
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class BearsPowerSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`BearsPowerSource`](./BearsPowerSource.cs/Методы/BearsPowerSource.md) | *Описание* |
| [`CopySettings`](./BearsPowerSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./BearsPowerSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./BearsPowerSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./BearsPowerSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Period`](./BearsPowerSource.cs/Свойства/Period.md) | *Описание* |





***  
***  
# Методы

## *BearsPowerSource*
Описание

```csharp
public BearsPowerSource()
```

***                

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

