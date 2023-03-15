
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class ATRSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ATRSource`](./ATRSource.cs/Методы/ATRSource.md) | *Описание* |
| [`CopySettings`](./ATRSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./ATRSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./ATRSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./ATRSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Period`](./ATRSource.cs/Свойства/Period.md) | *Описание* |





***  
***  
# Методы

## *ATRSource*
Описание

```csharp
public ATRSource()
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

