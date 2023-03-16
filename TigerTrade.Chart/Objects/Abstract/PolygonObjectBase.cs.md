
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


===

### Синтаксис
```csharp
public abstract class PolygonObjectBase : ObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#method-applytheme) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`PolygonObjectBase`](#method-polygonobjectbase) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`BackBrush`](#property-backbrush) | *===* |
| [`BackColor`](#property-backcolor) | *===* |
| [`DrawBack`](#property-drawback) | *===* |
| [`DrawBorder`](#property-drawborder) | *===* |
| [`LineBrush`](#property-linebrush) | *===* |
| [`LineColor`](#property-linecolor) | *===* |
| [`LinePen`](#property-linepen) | *===* |
| [`LineStyle`](#property-linestyle) | *===* |
| [`LineWidth`](#property-linewidth) | *===* |
| [`int`](#property-int) | *===* |





***  
***  
# Методы

## `ApplyTheme`<a href="method-applytheme" id="method-applytheme"></a>
===
```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *===*  


***  

## `CopyTemplate`<a href="method-copytemplate" id="method-copytemplate"></a>
===
```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *===*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `PolygonObjectBase`<a href="method-polygonobjectbase" id="method-polygonobjectbase"></a>
===
```csharp
protected PolygonObjectBase()
```

***  
***  
 ***  
# Свойства

## `BackBrush`<a href="property-backbrush" id="property-backbrush"></a>
===
```csharp
protected XBrush BackBrush { get; private set; }
```  
***

## `BackColor`<a href="property-backcolor" id="property-backcolor"></a>
===
```csharp
public XColor BackColor { get; set; }
```  
***

## `DrawBack`<a href="property-drawback" id="property-drawback"></a>
===
```csharp
public bool DrawBack { get; set; }
```  
***

## `DrawBorder`<a href="property-drawborder" id="property-drawborder"></a>
===
```csharp
public bool DrawBorder { get; set; }
```  
***

## `LineBrush`<a href="property-linebrush" id="property-linebrush"></a>
===
```csharp
protected XBrush LineBrush { get; private set; }
```  
***

## `LineColor`<a href="property-linecolor" id="property-linecolor"></a>
===
```csharp
public XColor LineColor { get; set; }
```  
***

## `LinePen`<a href="property-linepen" id="property-linepen"></a>
===
```csharp
protected XPen LinePen { get; private set; }
```  
***

## `LineStyle`<a href="property-linestyle" id="property-linestyle"></a>
===
```csharp
public XDashStyle LineStyle { get; set; }
```  
***

## `LineWidth`<a href="property-linewidth" id="property-linewidth"></a>
===
```csharp
public int LineWidth { get; set; }
```  
***

## `int`<a href="property-int" id="property-int"></a>
===
```csharp
protected override int PenWidth { get; }
```  
***

