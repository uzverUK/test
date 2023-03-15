
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartPeriod
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`GetSequence`](./IChartPeriod.cs/Методы/GetSequence.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Interval`](./IChartPeriod.cs/Свойства/Interval.md) | *Описание* |
| [`Type`](./IChartPeriod.cs/Свойства/Type.md) | *Описание* |





# Методы

## *GetSequence*
Описание

```csharp
int GetSequence(ChartPeriodType type, int interval, DateTime dateTime, double timeOffset)
```

<mark style="color:yellow;">`type`</mark> <mark style="color:red;">*`ChartPeriodType`*</mark>  
 *Описание*  

<mark style="color:yellow;">`interval`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`dateTime`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

<mark style="color:yellow;">`timeOffset`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *GetSequence*
Описание

```csharp
int GetSequence(ChartPeriodType type, int interval, DateTime dateTime, double timeOffset)
int GetSequence(ChartPeriodType type, int interval, double dateTime, double timeOffset)
```

<mark style="color:yellow;">`type`</mark> <mark style="color:red;">*`ChartPeriodType`*</mark>  
 *Описание*  

<mark style="color:yellow;">`interval`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`dateTime`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

<mark style="color:yellow;">`timeOffset`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:yellow;">`dateTime`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  


# Свойства

## *Interval*
Описание

```csharp
int Interval { get; }
```

## *Type*
Описание

```csharp
ChartPeriodType Type { get; }
```

