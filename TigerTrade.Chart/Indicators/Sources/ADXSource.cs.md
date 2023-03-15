
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class ADXSource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ADXSource`](./ADXSource.cs/Методы/ADXSource.md) | *Описание* |
| [`CopySettings`](./ADXSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./ADXSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./ADXSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./ADXSource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Period`](./ADXSource.cs/Свойства/Period.md) | *Описание* |





***  
***  
# Методы

## *ADXSource*
Описание

```csharp
public ADXSource()
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

