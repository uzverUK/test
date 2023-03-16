
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Sources](../../../TigerTrade.Chart/Indicators/Sources.md)


Описание

### Синтаксис
```csharp
public sealed class ParabolicSARSource : IndicatorSourceBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopySettings`](./ParabolicSARSource.cs/Методы/CopySettings.md) | *Описание* |
| [`GetSeries`](./ParabolicSARSource.cs/Методы/GetSeries.md) | *Описание* |
| [`GetSeriesList`](./ParabolicSARSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`ParabolicSARSource`](./ParabolicSARSource.cs/Методы/ParabolicSARSource.md) | *Описание* |
| [`ToString`](./ParabolicSARSource.cs/Методы/ToString.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Max`](./ParabolicSARSource.cs/Свойства/Max.md) | *Описание* |
| [`Step`](./ParabolicSARSource.cs/Свойства/Step.md) | *Описание* |





***  
***  
# Методы

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

## `ParabolicSARSource<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ParabolicSARSource()
```

***  

## `ToString<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

`string` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Max`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Max { get; set; }
```  
***

## `Step`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Step { get; set; }
```  
***

