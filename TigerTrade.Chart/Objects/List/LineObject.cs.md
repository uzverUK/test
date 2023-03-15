
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class LineObject : LineObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CheckAlert`](./LineObject.cs/Методы/CheckAlert.md) | *Описание* |
| [`CopyTemplate`](./LineObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./LineObject.cs/Методы/Draw.md) | *Описание* |
| [`InObject`](./LineObject.cs/Методы/InObject.md) | *Описание* |
| [`LineObject`](./LineObject.cs/Методы/LineObject.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Alert`](./LineObject.cs/Свойства/Alert.md) | *Описание* |
| [`AlertMinDistance`](./LineObject.cs/Свойства/AlertMinDistance.md) | *Описание* |
| [`OpenEnd`](./LineObject.cs/Свойства/OpenEnd.md) | *Описание* |
| [`OpenStart`](./LineObject.cs/Свойства/OpenStart.md) | *Описание* |
| [`RefPoint`](./LineObject.cs/Свойства/RefPoint.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./LineObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |




            ***
  ***
  # Методы

## CheckAlert
Описание

```csharp
public override void CheckAlert(System.Collections.Generic.List<IndicatorBase> indicators)
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

## InObject
Описание

```csharp
protected override bool InObject(int x, int y)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## LineObject
Описание

```csharp
public LineObject()
```

***                
                ***
  ***
  # Свойства

## Alert
Описание

```csharp
public ChartAlertSettings Alert { get; set; }
```
***

## AlertMinDistance
Описание

```csharp
public int AlertMinDistance { get; set; }
```
***

## OpenEnd
Описание

```csharp
public bool OpenEnd { get; set; }
```
***

## OpenStart
Описание

```csharp
public bool OpenStart { get; set; }
```
***

## RefPoint
Описание

```csharp
public ObjectPoint? RefPoint { get; set; }
```
***

## xsuJlZ3bylFkXacpNF53
Описание

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```
***

