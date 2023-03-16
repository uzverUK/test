
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartPeriod
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetSequence`](#method-getsequence) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Interval`](#property-interval) | *Описание* |
| [`Type`](#property-type) | *Описание* |





***  
***  
# Методы

## `GetSequence`<a href="method-getsequence" id="method-getsequence"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int GetSequence(ChartPeriodType type, int interval, DateTime dateTime, double timeOffset)
```

`type` <mark style="color:red;">*`ChartPeriodType`*</mark>  
 *Описание*  

`interval` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`dateTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`timeOffset` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetSequence`<a href="method-getsequence" id="method-getsequence"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int GetSequence(ChartPeriodType type, int interval, DateTime dateTime, double timeOffset)
int GetSequence(ChartPeriodType type, int interval, double dateTime, double timeOffset)
```

`type` <mark style="color:red;">*`ChartPeriodType`*</mark>  
 *Описание*  

`interval` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`dateTime` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`timeOffset` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`dateTime` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Interval`<a href="property-interval" id="property-interval"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Interval { get; }
```  
***

## `Type`<a href="property-type" id="property-type"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
ChartPeriodType Type { get; }
```  
***

