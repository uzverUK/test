
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


===

### Синтаксис
```csharp
public abstract class IndicatorParam<T>
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#method-clear) | *===* |
| [`Copy`](#method-copy) | *===* |
| [`Get`](#method-get) | *===* |
| [`IndicatorParam`](#method-indicatorparam) | *===* |
| [`Set`](#method-set) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Value`](#property-value) | *===* |
| [`Values`](#property-values) | *===* |





***  
***  
# Методы

## `Clear`<a href="method-clear" id="method-clear"></a>
===
```csharp
public void Clear()
```

***  

## `Copy`<a href="method-copy" id="method-copy"></a>
===
```csharp
public void Copy(IndicatorParam<T> p)
```

***  

## `Get`<a href="method-get" id="method-get"></a>
===
```csharp
public T Get(string key, T defaultValue)
```

`key` <mark style="color:red;">*`string`*</mark>  
 *===*  

`defaultValue` <mark style="color:red;">*`T`*</mark>  
 *===*  


***  

## `Get`<a href="method-get" id="method-get"></a>
===
```csharp
public T Get(string key, T defaultValue)
public T Get(string key)
```

`key` <mark style="color:red;">*`string`*</mark>  
 *===*  

`defaultValue` <mark style="color:red;">*`T`*</mark>  
 *===*  


***  

## `IndicatorParam`<a href="method-indicatorparam" id="method-indicatorparam"></a>
===
```csharp
protected IndicatorParam()
```

***  

## `Set`<a href="method-set" id="method-set"></a>
===
```csharp
protected bool Set(string key, T value)
```

`key` <mark style="color:red;">*`string`*</mark>  
 *===*  

`value` <mark style="color:red;">*`T`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Value`<a href="property-value" id="property-value"></a>
===
```csharp
public T Value { get; set; }
```  
***

## `Values`<a href="property-values" id="property-values"></a>
===
```csharp
public Dictionary<string, T> Values { get; set; }
```  
***

