
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





***  
***  
# Методы

## *Clear*
Описание

```csharp
public void Clear()
```

***                

## *Copy*
Описание

```csharp
public void Copy(IndicatorParam<T> p)
```

***                

## *Get*
Описание

```csharp
public T Get(string key, T defaultValue)
```

<mark style="color:yellow;">`key`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:yellow;">`defaultValue`</mark> <mark style="color:red;">*`T`*</mark>  
 *Описание*  


***                

## *Get*
Описание

```csharp
public T Get(string key, T defaultValue)
public T Get(string key)
```

<mark style="color:yellow;">`key`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:yellow;">`defaultValue`</mark> <mark style="color:red;">*`T`*</mark>  
 *Описание*  


***                

## *IndicatorParam*
Описание

```csharp
protected IndicatorParam()
```

***                

## *Set*
Описание

```csharp
protected bool Set(string key, T value)
```

<mark style="color:yellow;">`key`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:yellow;">`value`</mark> <mark style="color:red;">*`T`*</mark>  
 *Описание*  


***                
***
  ***
  # Свойства

## *Value*
Описание

```csharp
public T Value { get; set; }
```
***

## *Values*
Описание

```csharp
public Dictionary<string, T> Values { get; set; }
```
***

