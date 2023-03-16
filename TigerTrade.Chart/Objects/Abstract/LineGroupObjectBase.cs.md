
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


===

### Синтаксис
```csharp
public abstract class LineGroupObjectBase : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CalcPoint`](#method-calcpoint) | *===* |
| [`Draw`](#method-draw) | *===* |
| [`InObject`](#method-inobject) | *===* |
| [`LineGroupObjectBase`](#method-linegroupobjectbase) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`EndPoints;`](#property-endpoints;) | *===* |
| [`StartPoints;`](#property-startpoints;) | *===* |





***  
***  
# Методы

## `CalcPoint`<a href="method-calcpoint" id="method-calcpoint"></a>
===
```csharp
protected virtual void CalcPoint()
```

***  

## `Draw`<a href="method-draw" id="method-draw"></a>
===
```csharp
protected override void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *===*  

`List` <mark style="color:red;">*`ref`*</mark>  
 *===*  


***  

## `InObject`<a href="method-inobject" id="method-inobject"></a>
===
```csharp
protected override bool InObject(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *===*  

`y` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `LineGroupObjectBase`<a href="method-linegroupobjectbase" id="method-linegroupobjectbase"></a>
===
```csharp
protected LineGroupObjectBase()
```

***  
***  
 ***  
# Свойства

## `EndPoints;`<a href="property-endpoints;" id="property-endpoints;"></a>
===
```csharp
protected Point[] EndPoints; {}
```  
***

## `StartPoints;`<a href="property-startpoints;" id="property-startpoints;"></a>
===
```csharp
protected Point[] StartPoints; {}
```  
***

