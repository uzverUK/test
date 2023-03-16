
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


===

### Синтаксис
```csharp
public sealed class ObjectPeriods
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckPeriod`](#method-checkperiod) | *===* |
| [`Copy`](#method-copy) | *===* |
| [`Equals`](#method-equals) | *===* |
| [`ObjectPeriods`](#method-objectperiods) | *===* |
| [`Update`](#method-update) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Periods`](#property-periods) | *===* |





***  
***  
# Методы

## `CheckPeriod`<a href="method-checkperiod" id="method-checkperiod"></a>
===
```csharp
public bool CheckPeriod(IChartPeriod dc)
```

`dc` <mark style="color:red;">*`IChartPeriod`*</mark>  
 *===*  


***  

## `Copy`<a href="method-copy" id="method-copy"></a>
===
```csharp
public ObjectPeriods Copy()
```

***  

## `Equals`<a href="method-equals" id="method-equals"></a>
===
```csharp
public override bool Equals(object obj)
```

`obj` <mark style="color:red;">*`object`*</mark>  
 *===*  


***  

## `ObjectPeriods`<a href="method-objectperiods" id="method-objectperiods"></a>
===
```csharp
public ObjectPeriods()
```

***  

## `Update`<a href="method-update" id="method-update"></a>
===
```csharp
public void Update(string type, bool isChecked, bool checkRange, int min, int max)
```

`type` <mark style="color:red;">*`string`*</mark>  
 *===*  

`isChecked` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`checkRange` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`min` <mark style="color:red;">*`int`*</mark>  
 *===*  

`max` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Periods`<a href="property-periods" id="property-periods"></a>
===
```csharp
public Dictionary<string, ObjectPeriodItem> Periods { get; set; }
```  
***

