# DxVisualQueue

`namespace` [TigerTrade.Dx](./)

\===

#### Синтаксис

```csharp
public sealed class DxVisualQueue
```

## Список методов

| Название                                                                    | Описание |
| --------------------------------------------------------------------------- | -------- |
| [`Clear`](dxvisualqueue.cs.md#method-clear)                                 | _===_    |
| [`DrawArc`](dxvisualqueue.cs.md#method-drawarc)                             | _===_    |
| [`DrawEllipse`](dxvisualqueue.cs.md#method-drawellipse)                     | _===_    |
| [`DrawLine`](dxvisualqueue.cs.md#method-drawline)                           | _===_    |
| [`DrawLines`](dxvisualqueue.cs.md#method-drawlines)                         | _===_    |
| [`DrawPolygon`](dxvisualqueue.cs.md#method-drawpolygon)                     | _===_    |
| [`DrawRectangle`](dxvisualqueue.cs.md#method-drawrectangle)                 | _===_    |
| [`DrawRectangles`](dxvisualqueue.cs.md#method-drawrectangles)               | _===_    |
| [`DrawRoundedRectangle`](dxvisualqueue.cs.md#method-drawroundedrectangle)   | _===_    |
| [`DrawSmoothLines`](dxvisualqueue.cs.md#method-drawsmoothlines)             | _===_    |
| [`DxVisualQueue`](dxvisualqueue.cs.md#method-dxvisualqueue)                 | _===_    |
| [`FillEllipse`](dxvisualqueue.cs.md#method-fillellipse)                     | _===_    |
| [`FillGradientRectangle`](dxvisualqueue.cs.md#method-fillgradientrectangle) | _===_    |
| [`FillPolygon`](dxvisualqueue.cs.md#method-fillpolygon)                     | _===_    |
| [`FillRectangle`](dxvisualqueue.cs.md#method-fillrectangle)                 | _===_    |
| [`FillRectangles`](dxvisualqueue.cs.md#method-fillrectangles)               | _===_    |
| [`FillRoundedRectangle`](dxvisualqueue.cs.md#method-fillroundedrectangle)   | _===_    |
| [`ResetClip`](dxvisualqueue.cs.md#method-resetclip)                         | _===_    |
| [`SetClip`](dxvisualqueue.cs.md#method-setclip)                             | _===_    |

## Список свойств

| Название                                      | Описание |
| --------------------------------------------- | -------- |
| [`Empty`](dxvisualqueue.cs.md#property-empty) | _===_    |

***

***

## Методы

### `Clear` <a href="#method-clear" id="method-clear"></a>

\===

```csharp
public void Clear(XColor color)
```

`color` _<mark style="color:red;">`XColor`</mark>_\
_===_

***

### `DrawArc` <a href="#method-drawarc" id="method-drawarc"></a>

\===

```csharp
public void DrawArc(XPen pen, Point p1, Point p2, double radius, double angle)
```

`pen` _<mark style="color:red;">`XPen`</mark>_\
_===_

`p1` _<mark style="color:red;">`Point`</mark>_\
_===_

`p2` _<mark style="color:red;">`Point`</mark>_\
_===_

`radius` _<mark style="color:red;">`double`</mark>_\
_===_

`angle` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `DrawEllipse` <a href="#method-drawellipse" id="method-drawellipse"></a>

\===

```csharp
public void DrawEllipse(XPen pen, Point center, double radiusX, double radiusY)
```

`center` _<mark style="color:red;">`Point`</mark>_\
_===_

`radiusX` _<mark style="color:red;">`double`</mark>_\
_===_

`radiusY` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `DrawLine` <a href="#method-drawline" id="method-drawline"></a>

\===

```csharp
public void DrawLine(XPen pen, Point p1, Point p2)
```

`pen` _<mark style="color:red;">`XPen`</mark>_\
_===_

`p1` _<mark style="color:red;">`Point`</mark>_\
_===_

`p2` _<mark style="color:red;">`Point`</mark>_\
_===_

***

### `DrawLine` <a href="#method-drawline" id="method-drawline"></a>

\===

```csharp
public void DrawLine(XPen pen, Point p1, Point p2)
public void DrawLine(XPen pen, double x1, double y1, double x2, double y2)
```

`pen` _<mark style="color:red;">`XPen`</mark>_\
_===_

`p1` _<mark style="color:red;">`Point`</mark>_\
_===_

`p2` _<mark style="color:red;">`Point`</mark>_\
_===_

`x1` _<mark style="color:red;">`double`</mark>_\
_===_

`y1` _<mark style="color:red;">`double`</mark>_\
_===_

`x2` _<mark style="color:red;">`double`</mark>_\
_===_

`y2` _<mark style="color:red;">`double`</mark>_\
_===_

`Point` _<mark style="color:red;">`new`</mark>_\
_===_

`Point` _<mark style="color:red;">`new`</mark>_\
_===_

***

### `DrawLines` <a href="#method-drawlines" id="method-drawlines"></a>

\===

```csharp
public void DrawLines(XPen pen, Point[] points)
```

***

### `DrawLines` <a href="#method-drawlines" id="method-drawlines"></a>

\===

```csharp
public void DrawLines(XPen pen, Point[] points)
public void DrawLines(XPen pen, Point[] points, int pointsLength)
```

`pen` _<mark style="color:red;">`XPen`</mark>_\
_===_

`pointsLength` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `DrawPolygon` <a href="#method-drawpolygon" id="method-drawpolygon"></a>

\===

```csharp
public void DrawPolygon(XPen pen, Point[] points)
```

***

### `DrawRectangle` <a href="#method-drawrectangle" id="method-drawrectangle"></a>

\===

```csharp
public void DrawRectangle(XPen pen, Rect rect)
```

`pen` _<mark style="color:red;">`XPen`</mark>_\
_===_

`rect` _<mark style="color:red;">`Rect`</mark>_\
_===_

***

### `DrawRectangles` <a href="#method-drawrectangles" id="method-drawrectangles"></a>

\===

```csharp
public void DrawRectangles(XPen pen, Rect[] rects)
```

***

### `DrawRoundedRectangle` <a href="#method-drawroundedrectangle" id="method-drawroundedrectangle"></a>

\===

```csharp
public void DrawRoundedRectangle(XPen pen, Rect rect, Point radius)
```

`pen` _<mark style="color:red;">`XPen`</mark>_\
_===_

`rect` _<mark style="color:red;">`Rect`</mark>_\
_===_

`radius` _<mark style="color:red;">`Point`</mark>_\
_===_

***

### `DrawSmoothLines` <a href="#method-drawsmoothlines" id="method-drawsmoothlines"></a>

\===

```csharp
public void DrawSmoothLines(XPen pen, Point[] points)
```

***

### `DxVisualQueue` <a href="#method-dxvisualqueue" id="method-dxvisualqueue"></a>

\===

```csharp
public DxVisualQueue(Rect rect)
```

`rect` _<mark style="color:red;">`Rect`</mark>_\
_===_

***

### `FillEllipse` <a href="#method-fillellipse" id="method-fillellipse"></a>

\===

```csharp
public void FillEllipse(XBrush brush, Point center, double radiusX, double radiusY)
```

`brush` _<mark style="color:red;">`XBrush`</mark>_\
_===_

`center` _<mark style="color:red;">`Point`</mark>_\
_===_

`radiusX` _<mark style="color:red;">`double`</mark>_\
_===_

`radiusY` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `FillGradientRectangle` <a href="#method-fillgradientrectangle" id="method-fillgradientrectangle"></a>

\===

```csharp
public void FillGradientRectangle(XBrush brush, XBrush brush2, int dir, Rect rect)
```

`brush2` _<mark style="color:red;">`XBrush`</mark>_\
_===_

`dir` _<mark style="color:red;">`int`</mark>_\
_===_

`rect` _<mark style="color:red;">`Rect`</mark>_\
_===_

***

### `FillPolygon` <a href="#method-fillpolygon" id="method-fillpolygon"></a>

\===

```csharp
public void FillPolygon(XBrush brush, Point[] points)
```

`brush` _<mark style="color:red;">`XBrush`</mark>_\
_===_

***

### `FillRectangle` <a href="#method-fillrectangle" id="method-fillrectangle"></a>

\===

```csharp
public void FillRectangle(XBrush brush, Rect rect)
```

`rect` _<mark style="color:red;">`Rect`</mark>_\
_===_

***

### `FillRectangles` <a href="#method-fillrectangles" id="method-fillrectangles"></a>

\===

```csharp
public void FillRectangles(XBrush brush, Rect[] rects)
```

`brush` _<mark style="color:red;">`XBrush`</mark>_\
_===_

***

### `FillRoundedRectangle` <a href="#method-fillroundedrectangle" id="method-fillroundedrectangle"></a>

\===

```csharp
public void FillRoundedRectangle(XBrush brush, Rect rect, Point radius)
```

`rect` _<mark style="color:red;">`Rect`</mark>_\
_===_

`radius` _<mark style="color:red;">`Point`</mark>_\
_===_

***

### `ResetClip` <a href="#method-resetclip" id="method-resetclip"></a>

\===

```csharp
public void ResetClip()
```

***

### `SetClip` <a href="#method-setclip" id="method-setclip"></a>

\===

```csharp
public void SetClip(Rect rect)
```

`rect` _<mark style="color:red;">`Rect`</mark>_\
_===_

***

***

***

## Свойства

### `Empty` <a href="#property-empty" id="property-empty"></a>

\===

```csharp
public bool Empty { get; set; }
```

***
