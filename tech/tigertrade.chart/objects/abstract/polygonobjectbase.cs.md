# PolygonObjectBase

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[Abstract](./)

\===

#### Синтаксис

```csharp
public abstract class PolygonObjectBase : ObjectBase
```

## Список методов

| Название                                                                | Описание |
| ----------------------------------------------------------------------- | -------- |
| [`ApplyTheme`](polygonobjectbase.cs.md#method-applytheme)               | _===_    |
| [`CopyTemplate`](polygonobjectbase.cs.md#method-copytemplate)           | _===_    |
| [`PolygonObjectBase`](polygonobjectbase.cs.md#method-polygonobjectbase) | _===_    |

## Список свойств

| Название                                                    | Описание |
| ----------------------------------------------------------- | -------- |
| [`BackBrush`](polygonobjectbase.cs.md#property-backbrush)   | _===_    |
| [`BackColor`](polygonobjectbase.cs.md#property-backcolor)   | _===_    |
| [`DrawBack`](polygonobjectbase.cs.md#property-drawback)     | _===_    |
| [`DrawBorder`](polygonobjectbase.cs.md#property-drawborder) | _===_    |
| [`LineBrush`](polygonobjectbase.cs.md#property-linebrush)   | _===_    |
| [`LineColor`](polygonobjectbase.cs.md#property-linecolor)   | _===_    |
| [`LinePen`](polygonobjectbase.cs.md#property-linepen)       | _===_    |
| [`LineStyle`](polygonobjectbase.cs.md#property-linestyle)   | _===_    |
| [`LineWidth`](polygonobjectbase.cs.md#property-linewidth)   | _===_    |
| [`int`](polygonobjectbase.cs.md#property-int)               | _===_    |

***

***

## Методы

### `ApplyTheme` <a href="#method-applytheme" id="method-applytheme"></a>

\===

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` _<mark style="color:red;">`IChartTheme`</mark>_\
_===_

***

### `CopyTemplate` <a href="#method-copytemplate" id="method-copytemplate"></a>

\===

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` _<mark style="color:red;">`ObjectBase`</mark>_\
_===_

`style` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `PolygonObjectBase` <a href="#method-polygonobjectbase" id="method-polygonobjectbase"></a>

\===

```csharp
protected PolygonObjectBase()
```

***

***

***

## Свойства

### `BackBrush` <a href="#property-backbrush" id="property-backbrush"></a>

\===

```csharp
protected XBrush BackBrush { get; private set; }
```

***

### `BackColor` <a href="#property-backcolor" id="property-backcolor"></a>

\===

```csharp
public XColor BackColor { get; set; }
```

***

### `DrawBack` <a href="#property-drawback" id="property-drawback"></a>

\===

```csharp
public bool DrawBack { get; set; }
```

***

### `DrawBorder` <a href="#property-drawborder" id="property-drawborder"></a>

\===

```csharp
public bool DrawBorder { get; set; }
```

***

### `LineBrush` <a href="#property-linebrush" id="property-linebrush"></a>

\===

```csharp
protected XBrush LineBrush { get; private set; }
```

***

### `LineColor` <a href="#property-linecolor" id="property-linecolor"></a>

\===

```csharp
public XColor LineColor { get; set; }
```

***

### `LinePen` <a href="#property-linepen" id="property-linepen"></a>

\===

```csharp
protected XPen LinePen { get; private set; }
```

***

### `LineStyle` <a href="#property-linestyle" id="property-linestyle"></a>

\===

```csharp
public XDashStyle LineStyle { get; set; }
```

***

### `LineWidth` <a href="#property-linewidth" id="property-linewidth"></a>

\===

```csharp
public int LineWidth { get; set; }
```

***

### `int` <a href="#property-int" id="property-int"></a>

\===

```csharp
protected override int PenWidth { get; }
```

***
