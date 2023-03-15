
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class RSISource : IndicatorSourceBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./RSISource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./RSISource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./RSISource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`RSISource`](./RSISource.cs/Методы/RSISource.md) | *Описание* |
| [`ToString`](./RSISource.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Period`](./RSISource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./RSISource.cs/Свойства/Source.md) | *Описание* |





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

## *RSISource*
Описание

```csharp
public RSISource()
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

