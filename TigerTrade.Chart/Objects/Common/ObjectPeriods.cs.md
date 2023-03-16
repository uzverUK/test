
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public sealed class ObjectPeriods
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckPeriod`](#CheckPeriod-m) | *Описание* |
| [`Copy`](#Copy-m) | *Описание* |
| [`Equals`](#Equals-m) | *Описание* |
| [`ObjectPeriods`](#ObjectPeriods-m) | *Описание* |
| [`Update`](#Update-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Periods`](#Periods-p) | *Описание* |





***  
***  
# Методы

## `CheckPeriod`<a href="CheckPeriod-m" id="CheckPeriod-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CheckPeriod(IChartPeriod dc)
```

`dc` <mark style="color:red;">*`IChartPeriod`*</mark>  
 *Описание*  


***  

## `Copy`<a href="Copy-m" id="Copy-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPeriods Copy()
```

***  

## `Equals`<a href="Equals-m" id="Equals-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override bool Equals(object obj)
```

`obj` <mark style="color:red;">*`object`*</mark>  
 *Описание*  


***  

## `ObjectPeriods`<a href="ObjectPeriods-m" id="ObjectPeriods-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPeriods()
```

***  

## `Update`<a href="Update-m" id="Update-m"></a>
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

## `Periods`<a href="Periods-p" id="Periods-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Dictionary<string, ObjectPeriodItem> Periods { get; set; }
```  
***

