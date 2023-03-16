# IChartCanvas

`namespace` [TigerTrade.Chart](../../../).[Base](./)

\===

#### Синтаксис

```csharp
public interface IChartCanvas
```

## Список методов

| Название                                                                 | Описание |
| ------------------------------------------------------------------------ | -------- |
| [`ConvertTimeFromLocal`](ichartcanvas.cs.md#method-converttimefromlocal) | _===_    |
| [`ConvertTimeToLocal`](ichartcanvas.cs.md#method-converttimetolocal)     | _===_    |
| [`DateToIndex`](ichartcanvas.cs.md#method-datetoindex)                   | _===_    |
| [`FormatTime`](ichartcanvas.cs.md#method-formattime)                     | _===_    |
| [`FormatValue`](ichartcanvas.cs.md#method-formatvalue)                   | _===_    |
| [`GetIndex`](ichartcanvas.cs.md#method-getindex)                         | _===_    |
| [`GetValue`](ichartcanvas.cs.md#method-getvalue)                         | _===_    |
| [`GetValueFromPos`](ichartcanvas.cs.md#method-getvaluefrompos)           | _===_    |
| [`GetX`](ichartcanvas.cs.md#method-getx)                                 | _===_    |
| [`GetXScreen`](ichartcanvas.cs.md#method-getxscreen)                     | _===_    |
| [`GetXX`](ichartcanvas.cs.md#method-getxx)                               | _===_    |
| [`GetY`](ichartcanvas.cs.md#method-gety)                                 | _===_    |
| [`IndexToDate`](ichartcanvas.cs.md#method-indextodate)                   | _===_    |

## Список свойств

| Название                                                     | Описание |
| ------------------------------------------------------------ | -------- |
| [`AfterBars`](ichartcanvas.cs.md#property-afterbars)         | _===_    |
| [`ChartFont`](ichartcanvas.cs.md#property-chartfont)         | _===_    |
| [`ChartFontBold`](ichartcanvas.cs.md#property-chartfontbold) | _===_    |
| [`ColumnPercent`](ichartcanvas.cs.md#property-columnpercent) | _===_    |
| [`ColumnWidth`](ichartcanvas.cs.md#property-columnwidth)     | _===_    |
| [`Count`](ichartcanvas.cs.md#property-count)                 | _===_    |
| [`IsStock`](ichartcanvas.cs.md#property-isstock)             | _===_    |
| [`MaxY`](ichartcanvas.cs.md#property-maxy)                   | _===_    |
| [`MinY`](ichartcanvas.cs.md#property-miny)                   | _===_    |
| [`Rect`](ichartcanvas.cs.md#property-rect)                   | _===_    |
| [`Start`](ichartcanvas.cs.md#property-start)                 | _===_    |
| [`StepHeight`](ichartcanvas.cs.md#property-stepheight)       | _===_    |
| [`StockType`](ichartcanvas.cs.md#property-stocktype)         | _===_    |
| [`Stop`](ichartcanvas.cs.md#property-stop)                   | _===_    |
| [`Theme`](ichartcanvas.cs.md#property-theme)                 | _===_    |

***

***

## Методы

### `ConvertTimeFromLocal` <a href="#method-converttimefromlocal" id="method-converttimefromlocal"></a>

\===

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

***

### `ConvertTimeToLocal` <a href="#method-converttimetolocal" id="method-converttimetolocal"></a>

\===

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***

### `DateToIndex` <a href="#method-datetoindex" id="method-datetoindex"></a>

\===

```csharp
int DateToIndex(DateTime dt, int dir)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`dir` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `DateToIndex` <a href="#method-datetoindex" id="method-datetoindex"></a>

\===

```csharp
int DateToIndex(DateTime dt, int dir)
int DateToIndex(double dt, int dir)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`dir` _<mark style="color:red;">`int`</mark>_\
_===_

`dt` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `FormatTime` <a href="#method-formattime" id="method-formattime"></a>

\===

```csharp
string FormatTime(DateTime dt, string format)
```

`format` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `FormatValue` <a href="#method-formatvalue" id="method-formatvalue"></a>

\===

```csharp
string FormatValue(double d)
```

`d` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `GetIndex` <a href="#method-getindex" id="method-getindex"></a>

\===

```csharp
int GetIndex(int i)
```

`i` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `GetValue` <a href="#method-getvalue" id="method-getvalue"></a>

\===

```csharp
double GetValue(double y)
```

`y` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `GetValueFromPos` <a href="#method-getvaluefrompos" id="method-getvaluefrompos"></a>

\===

```csharp
Point GetValueFromPos(double x, double y)
```

`x` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `GetValueFromPos` <a href="#method-getvaluefrompos" id="method-getvaluefrompos"></a>

\===

```csharp
Point GetValueFromPos(double x, double y)
Point GetValueFromPos(double x, double y, bool snapToGrid)
```

`x` _<mark style="color:red;">`double`</mark>_\
_===_

`y` _<mark style="color:red;">`double`</mark>_\
_===_

`snapToGrid` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `GetX` <a href="#method-getx" id="method-getx"></a>

\===

```csharp
double GetX(int i)
```

`i` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `GetXScreen` <a href="#method-getxscreen" id="method-getxscreen"></a>

\===

```csharp
double GetXScreen(double x)
```

`x` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `GetXX` <a href="#method-getxx" id="method-getxx"></a>

\===

```csharp
double GetXX(int i)
```

`i` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `GetY` <a href="#method-gety" id="method-gety"></a>

\===

```csharp
double GetY(double d)
```

`d` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `IndexToDate` <a href="#method-indextodate" id="method-indextodate"></a>

\===

```csharp
DateTime IndexToDate(int i)
```

`i` _<mark style="color:red;">`int`</mark>_\
_===_

***

***

***

## Свойства

### `AfterBars` <a href="#property-afterbars" id="property-afterbars"></a>

\===

```csharp
int AfterBars { get; }
```

***

### `ChartFont` <a href="#property-chartfont" id="property-chartfont"></a>

\===

```csharp
XFont ChartFont { get; }
```

***

### `ChartFontBold` <a href="#property-chartfontbold" id="property-chartfontbold"></a>

\===

```csharp
XFont ChartFontBold { get; }
```

***

### `ColumnPercent` <a href="#property-columnpercent" id="property-columnpercent"></a>

\===

```csharp
double ColumnPercent { get; }
```

***

### `ColumnWidth` <a href="#property-columnwidth" id="property-columnwidth"></a>

\===

```csharp
double ColumnWidth { get; }
```

***

### `Count` <a href="#property-count" id="property-count"></a>

\===

```csharp
int Count { get; }
```

***

### `IsStock` <a href="#property-isstock" id="property-isstock"></a>

\===

```csharp
bool IsStock { get; }
```

***

### `MaxY` <a href="#property-maxy" id="property-maxy"></a>

\===

```csharp
double MaxY { get; }
```

***

### `MinY` <a href="#property-miny" id="property-miny"></a>

\===

```csharp
double MinY { get; }
```

***

### `Rect` <a href="#property-rect" id="property-rect"></a>

\===

```csharp
Rect Rect { get; }
```

***

### `Start` <a href="#property-start" id="property-start"></a>

\===

```csharp
int Start { get; }
```

***

### `StepHeight` <a href="#property-stepheight" id="property-stepheight"></a>

\===

```csharp
double StepHeight { get; }
```

***

### `StockType` <a href="#property-stocktype" id="property-stocktype"></a>

\===

```csharp
ChartStockType StockType { get; }
```

***

### `Stop` <a href="#property-stop" id="property-stop"></a>

\===

```csharp
int Stop { get; }
```

***

### `Theme` <a href="#property-theme" id="property-theme"></a>

\===

```csharp
IChartTheme Theme { get; }
```

***
