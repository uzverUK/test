
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public sealed class ObjectPeriods
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckPeriod`](#test) | *Описание* |
| [`Copy`](#test) | *Описание* |
| [`Equals`](#test) | *Описание* |
| [`ObjectPeriods`](#test) | *Описание* |
| [`Update`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Periods`](./ObjectPeriods.cs/Свойства/Periods.md) | *Описание* |





***  
***  
# Методы

## `CheckPeriod`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CheckPeriod(IChartPeriod dc)
```

`dc` <mark style="color:red;">*`IChartPeriod`*</mark>  
 *Описание*  


***  

## `Copy`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPeriods Copy()
```

***  

## `Equals`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override bool Equals(object obj)
```

`obj` <mark style="color:red;">*`object`*</mark>  
 *Описание*  


***  

## `ObjectPeriods`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPeriods()
```

***  

## `Update`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Update(string type, bool isChecked, bool checkRange, int min, int max)
```

`type` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`isChecked` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`checkRange` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`min` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`max` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Periods`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<string, ObjectPeriodItem> Periods { get; set; }
```  
***

