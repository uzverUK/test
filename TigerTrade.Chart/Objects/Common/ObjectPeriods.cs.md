
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public sealed class ObjectPeriods
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CheckPeriod`](./ObjectPeriods.cs/Методы/CheckPeriod.md) | *Описание* |
| [`Copy`](./ObjectPeriods.cs/Методы/Copy.md) | *Описание* |
| [`Equals`](./ObjectPeriods.cs/Методы/Equals.md) | *Описание* |
| [`ObjectPeriods`](./ObjectPeriods.cs/Методы/ObjectPeriods.md) | *Описание* |
| [`Update`](./ObjectPeriods.cs/Методы/Update.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Periods`](./ObjectPeriods.cs/Свойства/Periods.md) | *Описание* |





# Методы

## `CheckPeriod`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CheckPeriod(IChartPeriod dc)
```

<mark style="color:purple;">`dc`</mark> <mark style="color:red;">*`IChartPeriod`*</mark>  
 *Описание*  



## `Copy`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPeriods Copy()
```


## `Equals`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override bool Equals(object obj)
```

<mark style="color:purple;">`obj`</mark> <mark style="color:red;">*`object`*</mark>  
 *Описание*  



## `ObjectPeriods`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPeriods()
```


## `Update`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Update(string type, bool isChecked, bool checkRange, int min, int max)
```

<mark style="color:purple;">`type`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:purple;">`isChecked`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

<mark style="color:purple;">`checkRange`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

<mark style="color:purple;">`min`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:purple;">`max`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


# Свойства

## `Periods`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<string, ObjectPeriodItem> Periods { get; set; }
```

