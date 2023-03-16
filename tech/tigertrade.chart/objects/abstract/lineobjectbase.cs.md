# LineObjectBase

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[Abstract](./)

\===

#### Синтаксис

```csharp
public abstract class LineObjectBase : ObjectBase
```

## Список методов

| Название                                                       | Описание |
| -------------------------------------------------------------- | -------- |
| [`ApplyTheme`](lineobjectbase.cs.md#method-applytheme)         | _===_    |
| [`CopyTemplate`](lineobjectbase.cs.md#method-copytemplate)     | _===_    |
| [`LineObjectBase`](lineobjectbase.cs.md#method-lineobjectbase) | _===_    |

## Список свойств

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`LineBrush`](lineobjectbase.cs.md#property-linebrush) | _===_    |
| [`LineColor`](lineobjectbase.cs.md#property-linecolor) | _===_    |
| [`LinePen`](lineobjectbase.cs.md#property-linepen)     | _===_    |
| [`LineStyle`](lineobjectbase.cs.md#property-linestyle) | _===_    |
| [`LineWidth`](lineobjectbase.cs.md#property-linewidth) | _===_    |
| [`int`](lineobjectbase.cs.md#property-int)             | _===_    |

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

### `LineObjectBase` <a href="#method-lineobjectbase" id="method-lineobjectbase"></a>

\===

```csharp
protected LineObjectBase()
```

***

***

***

## Свойства

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
public XPen LinePen { get; private set; }
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
