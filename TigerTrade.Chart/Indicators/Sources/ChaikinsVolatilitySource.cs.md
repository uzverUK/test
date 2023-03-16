
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class ChaikinsVolatilitySource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChaikinsVolatilitySource`](./ChaikinsVolatilitySource.cs/Методы/ChaikinsVolatilitySource.md) | *Описание* |
| [`CopySettings`](./ChaikinsVolatilitySource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./ChaikinsVolatilitySource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./ChaikinsVolatilitySource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ToString`](./ChaikinsVolatilitySource.cs/Методы/ToString.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`MaType`](./ChaikinsVolatilitySource.cs/Свойства/MaType.md) | *Описание* |
| [`Period`](./ChaikinsVolatilitySource.cs/Свойства/Period.md) | *Описание* |





***  
***  
# Методы

## `ChaikinsVolatilitySource<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChaikinsVolatilitySource()
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

