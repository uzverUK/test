
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public abstract class IndicatorParam<T>
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#Clear-m) | *Описание* |
| [`Copy`](#Copy-m) | *Описание* |
| [`Get`](#Get-m) | *Описание* |
| [`IndicatorParam`](#IndicatorParam-m) | *Описание* |
| [`Set`](#Set-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Value`](#Value-p) | *Описание* |
| [`Values`](#Values-p) | *Описание* |





***  
***  
# Методы

## `Clear`<a href="Set-m" id="Set-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear()
```

***  

## `Copy`<a href="Set-m" id="Set-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Copy(IndicatorParam<T> p)
```

***  

## `Get`<a href="Set-m" id="Set-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T Get(string key, T defaultValue)
```

`key` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`defaultValue` <mark style="color:red;">*`T`*</mark>  
 *Описание*  


***  

## `Get`<a href="Set-m" id="Set-m"></a>
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

## `IndicatorParam`<a href="Set-m" id="Set-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorParam()
```

***  

## `Set`<a href="Set-m" id="Set-m"></a>
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

## `Value`<a href="Values-p" id="Values-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T Value { get; set; }
```  
***

## `Values`<a href="Values-p" id="Values-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<string, T> Values { get; set; }
```  
***

