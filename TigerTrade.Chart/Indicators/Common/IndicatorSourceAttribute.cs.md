
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public class IndicatorSourceAttribute : Attribute
```


# Список методов
| Название | Описание |
| --- | --- |
| [`IndicatorSourceAttribute`](#method-indicatorsourceattribute) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Name`](#property-name) | *Описание* |
| [`Type`](#property-type) | *Описание* |





***  
***  
# Методы

## `IndicatorSourceAttribute`<a href="method-indicatorsourceattribute" id="method-indicatorsourceattribute"></a>
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

## `Name`<a href="property-name" id="property-name"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `Type`<a href="property-type" id="property-type"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Type Type { get; set; }
```  
***

