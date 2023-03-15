
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public class HorizontalLineObject : LineObjectBase
```


## Таблица методов
| Название | Описание |
| --- | --- |
| [`CheckAlert`](./HorizontalLineObject.cs/Методы/CheckAlert.md) | *Описание* |
| [`CopyTemplate`](./HorizontalLineObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./HorizontalLineObject.cs/Методы/Draw.md) | *Описание* |
| [`DrawControlPoints`](./HorizontalLineObject.cs/Методы/DrawControlPoints.md) | *Описание* |
| [`DrawText`](./HorizontalLineObject.cs/Методы/DrawText.md) | *Описание* |
| [`HorizontalLineObject`](./HorizontalLineObject.cs/Методы/HorizontalLineObject.md) | *Описание* |
| [`InObject`](./HorizontalLineObject.cs/Методы/InObject.md) | *Описание* |
| [`IsObjectOnChart`](./HorizontalLineObject.cs/Методы/IsObjectOnChart.md) | *Описание* |

## Таблица свойств
| Название | Описание |
| --- | --- |
| [`Alert`](./HorizontalLineObject.cs/Свойства/Alert.md) | *Описание* |
| [`AlertMinDistance`](./HorizontalLineObject.cs/Свойства/AlertMinDistance.md) | *Описание* |
| [`FontSize`](./HorizontalLineObject.cs/Свойства/FontSize.md) | *Описание* |
| [`LineRect;`](./HorizontalLineObject.cs/Свойства/LineRect;.md) | *Описание* |
| [`Price`](./HorizontalLineObject.cs/Свойства/Price.md) | *Описание* |
| [`Text`](./HorizontalLineObject.cs/Свойства/Text.md) | *Описание* |
| [`TextAlignment`](./HorizontalLineObject.cs/Свойства/TextAlignment.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./HorizontalLineObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |




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

## DrawControlPoints
Описание

```csharp
public override void DrawControlPoints(DxVisualQueue visual)
```

***                

## DrawText
Описание

```csharp
protected void DrawText(DxVisualQueue visual)
```

<mark style="color:yellow;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***                

## HorizontalLineObject
Описание

```csharp
public HorizontalLineObject()
```

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

## IsObjectOnChart
Описание

```csharp
protected override bool IsObjectOnChart()
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

## FontSize
Описание

```csharp
public int FontSize { get; set; }
```
***

## LineRect;
Описание

```csharp
protected Rect LineRect; {}
```
***

## Price
Описание

```csharp
public Decimal Price { get; set; }
```
***

## Text
Описание

```csharp
public string Text { get; set; }
```
***

## TextAlignment
Описание

```csharp
public ObjectTextAlignment TextAlignment { get; set; }
```
***

## xsuJlZ3bylFkXacpNF53
Описание

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```
***

