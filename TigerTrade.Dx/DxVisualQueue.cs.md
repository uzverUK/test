
`namespace` [TigerTrade.Dx](../TigerTrade.Dx.md)


===

### Синтаксис
```csharp
public sealed class DxVisualQueue
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#method-clear) | *===* |
| [`DrawArc`](#method-drawarc) | *===* |
| [`DrawEllipse`](#method-drawellipse) | *===* |
| [`DrawLine`](#method-drawline) | *===* |
| [`DrawLines`](#method-drawlines) | *===* |
| [`DrawPolygon`](#method-drawpolygon) | *===* |
| [`DrawRectangle`](#method-drawrectangle) | *===* |
| [`DrawRectangles`](#method-drawrectangles) | *===* |
| [`DrawRoundedRectangle`](#method-drawroundedrectangle) | *===* |
| [`DrawSmoothLines`](#method-drawsmoothlines) | *===* |
| [`DxVisualQueue`](#method-dxvisualqueue) | *===* |
| [`FillEllipse`](#method-fillellipse) | *===* |
| [`FillGradientRectangle`](#method-fillgradientrectangle) | *===* |
| [`FillPolygon`](#method-fillpolygon) | *===* |
| [`FillRectangle`](#method-fillrectangle) | *===* |
| [`FillRectangles`](#method-fillrectangles) | *===* |
| [`FillRoundedRectangle`](#method-fillroundedrectangle) | *===* |
| [`ResetClip`](#method-resetclip) | *===* |
| [`SetClip`](#method-setclip) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Empty`](#property-empty) | *===* |





***  
***  
# Методы

## `Clear`<a href="method-clear" id="method-clear"></a>
===
```csharp
public void Clear(XColor color)
```

`color` <mark style="color:red;">*`XColor`*</mark>  
 *===*  


***  

## `DrawArc`<a href="method-drawarc" id="method-drawarc"></a>
===
```csharp
public void DrawArc(XPen pen, Point p1, Point p2, double radius, double angle)
```
`pen` <mark style="color:red;">*`XPen`*</mark>  
 *===*  

`p1` <mark style="color:red;">*`Point`*</mark>  
 *===*  

`p2` <mark style="color:red;">*`Point`*</mark>  
 *===*  

`radius` <mark style="color:red;">*`double`*</mark>  
 *===*  

`angle` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `DrawEllipse`<a href="method-drawellipse" id="method-drawellipse"></a>
===
```csharp
public void DrawEllipse(XPen pen, Point center, double radiusX, double radiusY)
```
`center` <mark style="color:red;">*`Point`*</mark>  
 *===*  

`radiusX` <mark style="color:red;">*`double`*</mark>  
 *===*  

`radiusY` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `DrawLine`<a href="method-drawline" id="method-drawline"></a>
===
```csharp
public void DrawLine(XPen pen, Point p1, Point p2)
```
`pen` <mark style="color:red;">*`XPen`*</mark>  
 *===*  

`p1` <mark style="color:red;">*`Point`*</mark>  
 *===*  

`p2` <mark style="color:red;">*`Point`*</mark>  
 *===*  


***  

## `DrawLine`<a href="method-drawline" id="method-drawline"></a>
===
```csharp
public void DrawLine(XPen pen, Point p1, Point p2)
public void DrawLine(XPen pen, double x1, double y1, double x2, double y2)
```
`pen` <mark style="color:red;">*`XPen`*</mark>  
 *===*  

`p1` <mark style="color:red;">*`Point`*</mark>  
 *===*  

`p2` <mark style="color:red;">*`Point`*</mark>  
 *===*  

`x1` <mark style="color:red;">*`double`*</mark>  
 *===*  

`y1` <mark style="color:red;">*`double`*</mark>  
 *===*  

`x2` <mark style="color:red;">*`double`*</mark>  
 *===*  

`y2` <mark style="color:red;">*`double`*</mark>  
 *===*  

`Point` <mark style="color:red;">*`new`*</mark>  
 *===*  

`Point` <mark style="color:red;">*`new`*</mark>  
 *===*  


***  

## `DrawLines`<a href="method-drawlines" id="method-drawlines"></a>
===
```csharp
public void DrawLines(XPen pen, Point[] points)
```

***  

## `DrawLines`<a href="method-drawlines" id="method-drawlines"></a>
===
```csharp
public void DrawLines(XPen pen, Point[] points)
public void DrawLines(XPen pen, Point[] points, int pointsLength)
```

`pen` <mark style="color:red;">*`XPen`*</mark>  
 *===*  

`pointsLength` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `DrawPolygon`<a href="method-drawpolygon" id="method-drawpolygon"></a>
===
```csharp
public void DrawPolygon(XPen pen, Point[] points)
```

***  

## `DrawRectangle`<a href="method-drawrectangle" id="method-drawrectangle"></a>
===
```csharp
public void DrawRectangle(XPen pen, Rect rect)
```

`pen` <mark style="color:red;">*`XPen`*</mark>  
 *===*  

`rect` <mark style="color:red;">*`Rect`*</mark>  
 *===*  


***  

## `DrawRectangles`<a href="method-drawrectangles" id="method-drawrectangles"></a>
===
```csharp
public void DrawRectangles(XPen pen, Rect[] rects)
```

***  

## `DrawRoundedRectangle`<a href="method-drawroundedrectangle" id="method-drawroundedrectangle"></a>
===
```csharp
public void DrawRoundedRectangle(XPen pen, Rect rect, Point radius)
```

`pen` <mark style="color:red;">*`XPen`*</mark>  
 *===*  

`rect` <mark style="color:red;">*`Rect`*</mark>  
 *===*  

`radius` <mark style="color:red;">*`Point`*</mark>  
 *===*  


***  

## `DrawSmoothLines`<a href="method-drawsmoothlines" id="method-drawsmoothlines"></a>
===
```csharp
public void DrawSmoothLines(XPen pen, Point[] points)
```

***  

## `DxVisualQueue`<a href="method-dxvisualqueue" id="method-dxvisualqueue"></a>
===
```csharp
public DxVisualQueue(Rect rect)
```

`rect` <mark style="color:red;">*`Rect`*</mark>  
 *===*  


***  

## `FillEllipse`<a href="method-fillellipse" id="method-fillellipse"></a>
===
```csharp
public void FillEllipse(XBrush brush, Point center, double radiusX, double radiusY)
```
`brush` <mark style="color:red;">*`XBrush`*</mark>  
 *===*  

`center` <mark style="color:red;">*`Point`*</mark>  
 *===*  

`radiusX` <mark style="color:red;">*`double`*</mark>  
 *===*  

`radiusY` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `FillGradientRectangle`<a href="method-fillgradientrectangle" id="method-fillgradientrectangle"></a>
===
```csharp
public void FillGradientRectangle(XBrush brush, XBrush brush2, int dir, Rect rect)
```
`brush2` <mark style="color:red;">*`XBrush`*</mark>  
 *===*  

`dir` <mark style="color:red;">*`int`*</mark>  
 *===*  

`rect` <mark style="color:red;">*`Rect`*</mark>  
 *===*  


***  

## `FillPolygon`<a href="method-fillpolygon" id="method-fillpolygon"></a>
===
```csharp
public void FillPolygon(XBrush brush, Point[] points)
```
`brush` <mark style="color:red;">*`XBrush`*</mark>  
 *===*  


***  

## `FillRectangle`<a href="method-fillrectangle" id="method-fillrectangle"></a>
===
```csharp
public void FillRectangle(XBrush brush, Rect rect)
```
`rect` <mark style="color:red;">*`Rect`*</mark>  
 *===*  


***  

## `FillRectangles`<a href="method-fillrectangles" id="method-fillrectangles"></a>
===
```csharp
public void FillRectangles(XBrush brush, Rect[] rects)
```
`brush` <mark style="color:red;">*`XBrush`*</mark>  
 *===*  


***  

## `FillRoundedRectangle`<a href="method-fillroundedrectangle" id="method-fillroundedrectangle"></a>
===
```csharp
public void FillRoundedRectangle(XBrush brush, Rect rect, Point radius)
```
`rect` <mark style="color:red;">*`Rect`*</mark>  
 *===*  

`radius` <mark style="color:red;">*`Point`*</mark>  
 *===*  


***  

## `ResetClip`<a href="method-resetclip" id="method-resetclip"></a>
===
```csharp
public void ResetClip()
```

***  

## `SetClip`<a href="method-setclip" id="method-setclip"></a>
===
```csharp
public void SetClip(Rect rect)
```

`rect` <mark style="color:red;">*`Rect`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Empty`<a href="property-empty" id="property-empty"></a>
===
```csharp
public bool Empty { get; set; }
```  
***

