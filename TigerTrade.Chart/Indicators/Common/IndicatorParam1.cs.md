
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public abstract class IndicatorParam<T>
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#method-clear) | *Описание* |
| [`Copy`](#method-copy) | *Описание* |
| [`Get`](#method-get) | *Описание* |
| [`IndicatorParam`](#method-indicatorparam) | *Описание* |
| [`Set`](#method-set) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Value`](#property-value) | *Описание* |
| [`Values`](#property-values) | *Описание* |





***  
***  
# Методы

## `Clear`<a href="method-clear" id="method-clear"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear()
```

***  

## `Copy`<a href="method-copy" id="method-copy"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Copy(IndicatorParam<T> p)
```

***  

## `Get`<a href="method-get" id="method-get"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T Get(string key, T defaultValue)
```

`key` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`defaultValue` <mark style="color:red;">*`T`*</mark>  
 *Описание*  


***  

## `Get`<a href="method-get" id="method-get"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T Get(string key, T defaultValue)
public T Get(string key)
```

`key` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`defaultValue` <mark style="color:red;">*`T`*</mark>  
 *Описание*  


***  

## `IndicatorParam`<a href="method-indicatorparam" id="method-indicatorparam"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorParam()
```

***  

## `Set`<a href="method-set" id="method-set"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected bool Set(string key, T value)
```

`key` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`T`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Value`<a href="property-value" id="property-value"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T Value { get; set; }
```  
***

## `Values`<a href="property-values" id="property-values"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<string, T> Values { get; set; }
```  
***

