
`namespace` [TigerTrade.Dx](../TigerTrade.Dx.md)


Описание

### Синтаксис
```csharp
public sealed class DxVisualQueue
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#Clear-m) | *Описание* |
| [`DrawArc`](#DrawArc-m) | *Описание* |
| [`DrawEllipse`](#DrawEllipse-m) | *Описание* |
| [`DrawLine`](#DrawLine-m) | *Описание* |
| [`DrawLines`](#DrawLines-m) | *Описание* |
| [`DrawPolygon`](#DrawPolygon-m) | *Описание* |
| [`DrawRectangle`](#DrawRectangle-m) | *Описание* |
| [`DrawRectangles`](#DrawRectangles-m) | *Описание* |
| [`DrawRoundedRectangle`](#DrawRoundedRectangle-m) | *Описание* |
| [`DrawSmoothLines`](#DrawSmoothLines-m) | *Описание* |
| [`DxVisualQueue`](#DxVisualQueue-m) | *Описание* |
| [`FillEllipse`](#FillEllipse-m) | *Описание* |
| [`FillGradientRectangle`](#FillGradientRectangle-m) | *Описание* |
| [`FillPolygon`](#FillPolygon-m) | *Описание* |
| [`FillRectangle`](#FillRectangle-m) | *Описание* |
| [`FillRectangles`](#FillRectangles-m) | *Описание* |
| [`FillRoundedRectangle`](#FillRoundedRectangle-m) | *Описание* |
| [`ResetClip`](#ResetClip-m) | *Описание* |
| [`SetClip`](#SetClip-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Empty`](#Empty-p) | *Описание* |





***  
***  
# Методы

## `Clear`<a href="Clear-m" id="Clear-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear(XColor color)
```

`color` <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  


***  

## `DrawArc`<a href="DrawArc-m" id="DrawArc-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawArc(XPen pen, Point p1, Point p2, double radius, double angle)
```
`pen` <mark style="color:red;">*`XPen`*</mark>  
 *Описание*  

`p1` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  

`p2` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  

`radius` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`angle` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `DrawEllipse`<a href="DrawEllipse-m" id="DrawEllipse-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawEllipse(XPen pen, Point center, double radiusX, double radiusY)
```
`center` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  

`radiusX` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`radiusY` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `DrawLine`<a href="DrawLine-m" id="DrawLine-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawLine(XPen pen, Point p1, Point p2)
```
`pen` <mark style="color:red;">*`XPen`*</mark>  
 *Описание*  

`p1` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  

`p2` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  


***  

## `DrawLine`<a href="DrawLine-m" id="DrawLine-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawLine(XPen pen, Point p1, Point p2)
public void DrawLine(XPen pen, double x1, double y1, double x2, double y2)
```
`pen` <mark style="color:red;">*`XPen`*</mark>  
 *Описание*  

`p1` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  

`p2` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  

`x1` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`y1` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`x2` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`y2` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`Point` <mark style="color:red;">*`new`*</mark>  
 *Описание*  

`Point` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `DrawLines`<a href="DrawLines-m" id="DrawLines-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawLines(XPen pen, Point[] points)
```

***  

## `DrawLines`<a href="DrawLines-m" id="DrawLines-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawLines(XPen pen, Point[] points)
public void DrawLines(XPen pen, Point[] points, int pointsLength)
```

`pen` <mark style="color:red;">*`XPen`*</mark>  
 *Описание*  

`pointsLength` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `DrawPolygon`<a href="DrawPolygon-m" id="DrawPolygon-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawPolygon(XPen pen, Point[] points)
```

***  

## `DrawRectangle`<a href="DrawRectangle-m" id="DrawRectangle-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawRectangle(XPen pen, Rect rect)
```

`pen` <mark style="color:red;">*`XPen`*</mark>  
 *Описание*  

`rect` <mark style="color:red;">*`Rect`*</mark>  
 *Описание*  


***  

## `DrawRectangles`<a href="DrawRectangles-m" id="DrawRectangles-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawRectangles(XPen pen, Rect[] rects)
```

***  

## `DrawRoundedRectangle`<a href="DrawRoundedRectangle-m" id="DrawRoundedRectangle-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawRoundedRectangle(XPen pen, Rect rect, Point radius)
```

`pen` <mark style="color:red;">*`XPen`*</mark>  
 *Описание*  

`rect` <mark style="color:red;">*`Rect`*</mark>  
 *Описание*  

`radius` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  


***  

## `DrawSmoothLines`<a href="DrawSmoothLines-m" id="DrawSmoothLines-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawSmoothLines(XPen pen, Point[] points)
```

***  

## `DxVisualQueue`<a href="DxVisualQueue-m" id="DxVisualQueue-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DxVisualQueue(Rect rect)
```

`rect` <mark style="color:red;">*`Rect`*</mark>  
 *Описание*  


***  

## `FillEllipse`<a href="FillEllipse-m" id="FillEllipse-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void FillEllipse(XBrush brush, Point center, double radiusX, double radiusY)
```
`brush` <mark style="color:red;">*`XBrush`*</mark>  
 *Описание*  

`center` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  

`radiusX` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`radiusY` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `FillGradientRectangle`<a href="FillGradientRectangle-m" id="FillGradientRectangle-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void FillGradientRectangle(XBrush brush, XBrush brush2, int dir, Rect rect)
```
`brush2` <mark style="color:red;">*`XBrush`*</mark>  
 *Описание*  

`dir` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`rect` <mark style="color:red;">*`Rect`*</mark>  
 *Описание*  


***  

## `FillPolygon`<a href="FillPolygon-m" id="FillPolygon-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void FillPolygon(XBrush brush, Point[] points)
```
`brush` <mark style="color:red;">*`XBrush`*</mark>  
 *Описание*  


***  

## `FillRectangle`<a href="FillRectangle-m" id="FillRectangle-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void FillRectangle(XBrush brush, Rect rect)
```
`rect` <mark style="color:red;">*`Rect`*</mark>  
 *Описание*  


***  

## `FillRectangles`<a href="FillRectangles-m" id="FillRectangles-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void FillRectangles(XBrush brush, Rect[] rects)
```
`brush` <mark style="color:red;">*`XBrush`*</mark>  
 *Описание*  


***  

## `FillRoundedRectangle`<a href="FillRoundedRectangle-m" id="FillRoundedRectangle-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void FillRoundedRectangle(XBrush brush, Rect rect, Point radius)
```
`rect` <mark style="color:red;">*`Rect`*</mark>  
 *Описание*  

`radius` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  


***  

## `ResetClip`<a href="ResetClip-m" id="ResetClip-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void ResetClip()
```

***  

## `SetClip`<a href="SetClip-m" id="SetClip-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetClip(Rect rect)
```

`rect` <mark style="color:red;">*`Rect`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Empty`<a href="Empty-p" id="Empty-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Empty { get; set; }
```  
***

