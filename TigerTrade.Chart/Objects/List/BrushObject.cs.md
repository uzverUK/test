
# BrushObject
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)



Описаниеt

### Синтаксис
```csharp
public sealed class BrushObject : LineObjectBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`AddPoint`](./BrushObject.cs/Методы/AddPoint.md) | *Описание* |
| [`ApplyTheme`](./BrushObject.cs/Методы/ApplyTheme.md) | *Описание* |
| [`BrushObject`](./BrushObject.cs/Методы/BrushObject.md) | *Описание* |
| [`CopyTemplate`](./BrushObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./BrushObject.cs/Методы/Draw.md) | *Описание* |
| [`GetMinDist`](./BrushObject.cs/Методы/GetMinDist.md) | *Описание* |
| [`InObject`](./BrushObject.cs/Методы/InObject.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Points`](./BrushObject.cs/Свойства/Points.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./BrushObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |




            ***
  ***
  # Методы

## AddPoint
Описание

```csharp
public void AddPoint(ObjectPoint op)
```

<mark style="color:yellow;">`op`</mark> <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***                

## ApplyTheme
Описание

```csharp
public override void ApplyTheme(IChartTheme theme)
```
<mark style="color:yellow;">`theme`</mark> <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***                

## BrushObject
Описание

```csharp
public BrushObject()
```

***                

## CopyTemplate
Описание

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

<mark style="color:yellow;">`objectBase`</mark> <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***                

## Draw
Описание

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
<mark style="color:yellow;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

<mark style="color:yellow;">`System`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***                

## GetMinDist
Описание

```csharp
protected override int GetMinDist(int x, int y)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## InObject
Описание

```csharp
protected override bool InObject(int x, int y)
```

***                
                ***
  ***
  # Свойства

## Points
Описание

```csharp
public System.Collections.Generic.List<ObjectPoint> Points { get; set; }
```
***

## xsuJlZ3bylFkXacpNF53
Описание

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```
***

