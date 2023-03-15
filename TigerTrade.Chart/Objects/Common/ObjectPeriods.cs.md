
# public sealed class ObjectPeriods
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)



Описаниеt

### Синтаксис
```csharp
public sealed class ObjectPeriods
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CheckPeriod`](./ObjectPeriods.cs/Методы/CheckPeriod.md) | *Описание* |
| [`Copy`](./ObjectPeriods.cs/Методы/Copy.md) | *Описание* |
| [`Equals`](./ObjectPeriods.cs/Методы/Equals.md) | *Описание* |
| [`ObjectPeriods`](./ObjectPeriods.cs/Методы/ObjectPeriods.md) | *Описание* |
| [`Update`](./ObjectPeriods.cs/Методы/Update.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Periods`](./ObjectPeriods.cs/Свойства/Periods.md) | *Описание* |




            ***
  ***
  # Методы

## CheckPeriod
Описание

```csharp
public bool CheckPeriod(IChartPeriod dc)
```

<mark style="color:yellow;">`dc`</mark> <mark style="color:red;">*`IChartPeriod`*</mark>  
 *Описание*  


***                

## Copy
Описание

```csharp
public ObjectPeriods Copy()
```

***                

## Equals
Описание

```csharp
public override bool Equals(object obj)
```

<mark style="color:yellow;">`obj`</mark> <mark style="color:red;">*`object`*</mark>  
 *Описание*  


***                

## ObjectPeriods
Описание

```csharp
public ObjectPeriods()
```

***                

## Update
Описание

```csharp
public void Update(string type, bool isChecked, bool checkRange, int min, int max)
```

<mark style="color:yellow;">`type`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:yellow;">`isChecked`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

<mark style="color:yellow;">`checkRange`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

<mark style="color:yellow;">`min`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`max`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                
                ***
  ***
  # Свойства

## Periods
Описание

```csharp
public Dictionary<string, ObjectPeriodItem> Periods { get; set; }
```
***

