
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


===

### Синтаксис
```csharp
public interface IChartPeriod
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetSequence`](#method-getsequence) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Interval`](#property-interval) | *===* |
| [`Type`](#property-type) | *===* |





***  
***  
# Методы

## `GetSequence`<a href="method-getsequence" id="method-getsequence"></a>
===
```csharp
int GetSequence(ChartPeriodType type, int interval, DateTime dateTime, double timeOffset)
```

`type` <mark style="color:red;">*`ChartPeriodType`*</mark>  
 *===*  

`interval` <mark style="color:red;">*`int`*</mark>  
 *===*  

`dateTime` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`timeOffset` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `GetSequence`<a href="method-getsequence" id="method-getsequence"></a>
===
```csharp
int GetSequence(ChartPeriodType type, int interval, DateTime dateTime, double timeOffset)
int GetSequence(ChartPeriodType type, int interval, double dateTime, double timeOffset)
```

`type` <mark style="color:red;">*`ChartPeriodType`*</mark>  
 *===*  

`interval` <mark style="color:red;">*`int`*</mark>  
 *===*  

`dateTime` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`timeOffset` <mark style="color:red;">*`double`*</mark>  
 *===*  

`dateTime` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Interval`<a href="property-interval" id="property-interval"></a>
===
```csharp
int Interval { get; }
```  
***

## `Type`<a href="property-type" id="property-type"></a>
===
```csharp
ChartPeriodType Type { get; }
```  
***

