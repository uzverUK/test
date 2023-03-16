
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class UltimateOscillatorSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](#method-copysettings) | *Описание* |
| [`GetSeries`](#method-getseries) | *Описание* |
| [`GetSeriesList`](#method-getserieslist) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |
| [`UltimateOscillatorSource`](#method-ultimateoscillatorsource) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Period1`](#property-period1) | *Описание* |
| [`Period2`](#property-period2) | *Описание* |
| [`Period3`](#property-period3) | *Описание* |





***  
***  
# Методы

## `CopySettings`<a href="method-copysettings" id="method-copysettings"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

`source` <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  


***  

## `GetSeries`<a href="method-getseries" id="method-getseries"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  


***  

## `GetSeriesList`<a href="method-getserieslist" id="method-getserieslist"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override IEnumerable<string> GetSeriesList()
```
`List` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  

## `UltimateOscillatorSource`<a href="method-ultimateoscillatorsource" id="method-ultimateoscillatorsource"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UltimateOscillatorSource()
```

***  
***  
 ***  
# Свойства

## `Period1`<a href="property-period1" id="property-period1"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Period1 { get; set; }
```  
***

## `Period2`<a href="property-period2" id="property-period2"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Period2 { get; set; }
```  
***

## `Period3`<a href="property-period3" id="property-period3"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Period3 { get; set; }
```  
***

