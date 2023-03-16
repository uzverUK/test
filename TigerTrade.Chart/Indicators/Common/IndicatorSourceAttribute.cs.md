
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public class IndicatorSourceAttribute : Attribute
```


# Список методов
| Название | Описание |
| --- | --- |
| [`IndicatorSourceAttribute`](#IndicatorSourceAttribute-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Name`](#Name-p) | *Описание* |
| [`Type`](#Type-p) | *Описание* |





***  
***  
# Методы

## `IndicatorSourceAttribute`<a href="IndicatorSourceAttribute-m" id="IndicatorSourceAttribute-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSourceAttribute(string name)
```

`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Name`<a href="Type-p" id="Type-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `Type`<a href="Type-p" id="Type-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Type Type { get; set; }
```  
***

