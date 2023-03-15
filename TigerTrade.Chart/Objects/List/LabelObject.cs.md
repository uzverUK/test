
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class LabelObject : PolygonObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./LabelObject.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./LabelObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./LabelObject.cs/Методы/Draw.md) | *Описание* |
| [`InObject`](./LabelObject.cs/Методы/InObject.md) | *Описание* |
| [`LabelObject`](./LabelObject.cs/Методы/LabelObject.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`FontSize`](./LabelObject.cs/Свойства/FontSize.md) | *Описание* |
| [`LabelColor`](./LabelObject.cs/Свойства/LabelColor.md) | *Описание* |
| [`LabelText`](./LabelObject.cs/Свойства/LabelText.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./LabelObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |




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

## LabelObject
Описание

```csharp
public LabelObject()
```

***                
                ***
  ***
  # Свойства

## FontSize
Описание

```csharp
public int FontSize { get; set; }
```
***

## LabelColor
Описание

```csharp
public XColor LabelColor { get; set; }
```
***

## LabelText
Описание

```csharp
public string LabelText { get; set; }
```
***

## xsuJlZ3bylFkXacpNF53
Описание

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```
***

