
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class LineObjectBase : ObjectBase
```


## Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./LineObjectBase.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./LineObjectBase.cs/Методы/CopyTemplate.md) | *Описание* |
| [`LineObjectBase`](./LineObjectBase.cs/Методы/LineObjectBase.md) | *Описание* |

## Таблица свойств
| Название | Описание |
| --- | --- |
| [`LineBrush`](./LineObjectBase.cs/Свойства/LineBrush.md) | *Описание* |
| [`LineColor`](./LineObjectBase.cs/Свойства/LineColor.md) | *Описание* |
| [`LinePen`](./LineObjectBase.cs/Свойства/LinePen.md) | *Описание* |
| [`LineStyle`](./LineObjectBase.cs/Свойства/LineStyle.md) | *Описание* |
| [`LineWidth`](./LineObjectBase.cs/Свойства/LineWidth.md) | *Описание* |
| [`int`](./LineObjectBase.cs/Свойства/int.md) | *Описание* |




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

## LineObjectBase
Описание

```csharp
protected LineObjectBase()
```

***                
                ***
  ***
  # Свойства

## LineBrush
Описание

```csharp
protected XBrush LineBrush { get; private set; }
```
***

## LineColor
Описание

```csharp
public XColor LineColor { get; set; }
```
***

## LinePen
Описание

```csharp
public XPen LinePen { get; private set; }
```
***

## LineStyle
Описание

```csharp
public XDashStyle LineStyle { get; set; }
```
***

## LineWidth
Описание

```csharp
public int LineWidth { get; set; }
```
***

## int
Описание

```csharp
protected override int PenWidth { get; }
```
***

