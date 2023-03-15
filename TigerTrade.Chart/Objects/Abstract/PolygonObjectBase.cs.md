
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class PolygonObjectBase : ObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./PolygonObjectBase.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./PolygonObjectBase.cs/Методы/CopyTemplate.md) | *Описание* |
| [`PolygonObjectBase`](./PolygonObjectBase.cs/Методы/PolygonObjectBase.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`BackBrush`](./PolygonObjectBase.cs/Свойства/BackBrush.md) | *Описание* |
| [`BackColor`](./PolygonObjectBase.cs/Свойства/BackColor.md) | *Описание* |
| [`DrawBack`](./PolygonObjectBase.cs/Свойства/DrawBack.md) | *Описание* |
| [`DrawBorder`](./PolygonObjectBase.cs/Свойства/DrawBorder.md) | *Описание* |
| [`LineBrush`](./PolygonObjectBase.cs/Свойства/LineBrush.md) | *Описание* |
| [`LineColor`](./PolygonObjectBase.cs/Свойства/LineColor.md) | *Описание* |
| [`LinePen`](./PolygonObjectBase.cs/Свойства/LinePen.md) | *Описание* |
| [`LineStyle`](./PolygonObjectBase.cs/Свойства/LineStyle.md) | *Описание* |
| [`LineWidth`](./PolygonObjectBase.cs/Свойства/LineWidth.md) | *Описание* |
| [`int`](./PolygonObjectBase.cs/Свойства/int.md) | *Описание* |





***  
***  
# Методы

## *ApplyTheme*
Описание

```csharp
public override void ApplyTheme(IChartTheme theme)
```

<mark style="color:yellow;">`theme`</mark> <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***                

## *CopyTemplate*
Описание

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
<mark style="color:yellow;">`objectBase`</mark> <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***                

## *PolygonObjectBase*
Описание

```csharp
protected PolygonObjectBase()
```

***                
***
  ***
  # Свойства

## *BackBrush*
Описание

```csharp
protected XBrush BackBrush { get; private set; }
```
***

## *BackColor*
Описание

```csharp
public XColor BackColor { get; set; }
```
***

## *DrawBack*
Описание

```csharp
public bool DrawBack { get; set; }
```
***

## *DrawBorder*
Описание

```csharp
public bool DrawBorder { get; set; }
```
***

## *LineBrush*
Описание

```csharp
protected XBrush LineBrush { get; private set; }
```
***

## *LineColor*
Описание

```csharp
public XColor LineColor { get; set; }
```
***

## *LinePen*
Описание

```csharp
protected XPen LinePen { get; private set; }
```
***

## *LineStyle*
Описание

```csharp
public XDashStyle LineStyle { get; set; }
```
***

## *LineWidth*
Описание

```csharp
public int LineWidth { get; set; }
```
***

## *int*
Описание

```csharp
protected override int PenWidth { get; }
```
***

