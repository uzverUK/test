
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public abstract class IndicatorParam<T>
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`Clear`](./IndicatorParam1.cs/Методы/Clear.md) | *Описание* |
| [`Copy`](./IndicatorParam1.cs/Методы/Copy.md) | *Описание* |
| [`Get`](./IndicatorParam1.cs/Методы/Get.md) | *Описание* |
| [`IndicatorParam`](./IndicatorParam1.cs/Методы/IndicatorParam.md) | *Описание* |
| [`Set`](./IndicatorParam1.cs/Методы/Set.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Value`](./IndicatorParam1.cs/Свойства/Value.md) | *Описание* |
| [`Values`](./IndicatorParam1.cs/Свойства/Values.md) | *Описание* |





# Методы

## `Clear`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear()
```


## `Copy`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Copy(IndicatorParam<T> p)
```


## `Get`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T Get(string key, T defaultValue)
```

`key` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`defaultValue` <mark style="color:red;">*`T`*</mark>  
 *Описание*  



## `Get`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T Get(string key, T defaultValue)
public T Get(string key)
```

`key` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`defaultValue` <mark style="color:red;">*`T`*</mark>  
 *Описание*  



## `IndicatorParam`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorParam()
```


## `Set`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected bool Set(string key, T value)
```

`key` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`T`*</mark>  
 *Описание*  


# Свойства

## `Value`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T Value { get; set; }
```

## `Values`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<string, T> Values { get; set; }
```

