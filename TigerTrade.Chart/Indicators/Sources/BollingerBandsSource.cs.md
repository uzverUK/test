
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class BollingerBandsSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BollingerBandsSource`](./BollingerBandsSource.cs/Методы/BollingerBandsSource.md) | *Описание* |
| [`CopySettings`](./BollingerBandsSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./BollingerBandsSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./BollingerBandsSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./BollingerBandsSource.cs/Методы/ToString.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`MaType`](./BollingerBandsSource.cs/Свойства/MaType.md) | *Описание* |
| [`Period`](./BollingerBandsSource.cs/Свойства/Period.md) | *Описание* |
| [`Source`](./BollingerBandsSource.cs/Свойства/Source.md) | *Описание* |
| [`StdDev`](./BollingerBandsSource.cs/Свойства/StdDev.md) | *Описание* |





***  
***  
# Методы

## `BollingerBandsSource<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BollingerBandsSource()
```

***  

## `CopySettings<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

`source` <mark style="color:red;">*`IndicatorSourceBase`*</mark>  
 *Описание*  


***  

## `GetSeries<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```
`helper` <mark style="color:red;">*`IndicatorsHelper`*</mark>  
 *Описание*  


***  

## `GetSeriesList<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override IEnumerable<string> GetSeriesList()
```
`List` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `ToString<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `MaType`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorMaType MaType { get; set; }
```  
***

## `Period`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Period { get; set; }
```  
***

## `Source`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSourceBase Source { get; set; }
```  
***

## `StdDev`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal StdDev { get; set; }
```  
***

