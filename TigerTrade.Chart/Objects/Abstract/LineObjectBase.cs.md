
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


===

### Синтаксис
```csharp
public abstract class LineObjectBase : ObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#method-applytheme) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`LineObjectBase`](#method-lineobjectbase) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
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

## `LineObjectBase`<a href="method-lineobjectbase" id="method-lineobjectbase"></a>
===
```csharp
protected LineObjectBase()
```

***  
***  
 ***  
# Свойства

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
public XPen LinePen { get; private set; }
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

