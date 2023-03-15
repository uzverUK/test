
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public class IconObject : ObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./IconObject.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./IconObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./IconObject.cs/Методы/Draw.md) | *Описание* |
| [`IconObject`](./IconObject.cs/Методы/IconObject.md) | *Описание* |
| [`InObject`](./IconObject.cs/Методы/InObject.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Brush`](./IconObject.cs/Свойства/Brush.md) | *Описание* |
| [`Color`](./IconObject.cs/Свойства/Color.md) | *Описание* |
| [`Icon`](./IconObject.cs/Свойства/Icon.md) | *Описание* |
| [`Size`](./IconObject.cs/Свойства/Size.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./IconObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |




            ***
  ***
  # Методы

## ApplyTheme
Описание

```csharp
public override void ApplyTheme(IChartTheme theme)
```

<mark style="color:yellow;">`theme`</mark> <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


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

## IconObject
Описание

```csharp
public IconObject()
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
                ***
  ***
  # Свойства

## Brush
Описание

```csharp
protected XBrush Brush { get; private set; }
```
***

## Color
Описание

```csharp
public XColor Color { get; set; }
```
***

## Icon
Описание

```csharp
public string Icon { get; set; }
```
***

## Size
Описание

```csharp
public int Size { get; set; }
```
***

## xsuJlZ3bylFkXacpNF53
Описание

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```
***

