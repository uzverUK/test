
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public class IndicatorSourceAttribute : Attribute
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`IndicatorSourceAttribute`](./IndicatorSourceAttribute.cs/Методы/IndicatorSourceAttribute.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Name`](./IndicatorSourceAttribute.cs/Свойства/Name.md) | *Описание* |
| [`Type`](./IndicatorSourceAttribute.cs/Свойства/Type.md) | *Описание* |





# Методы

## `IndicatorSourceAttribute`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSourceAttribute(string name)
```

`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


# Свойства

## `Name`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```

## `Type`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Type Type { get; set; }
```

