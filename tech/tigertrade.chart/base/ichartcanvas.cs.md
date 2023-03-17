# IChartCanvas

`namespace` [TigerTrade.Chart](../../../).[Base](./)

\===

#### Синтаксис

```csharp
public interface IChartCanvas
```

## Список методов

| Название                                                                 | Описание                                                                                                                               |
| ------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| [`ConvertTimeFromLocal`](ichartcanvas.cs.md#method-converttimefromlocal) | _===_                                                                                                                                  |
| [`ConvertTimeToLocal`](ichartcanvas.cs.md#method-converttimetolocal)     | _===_                                                                                                                                  |
| [`DateToIndex`](ichartcanvas.cs.md#method-datetoindex)                   | _Возвращает индекс бара находящегося по_ [_`DateTime`_](https://learn.microsoft.com/ru-ru/dotnet/api/system.datetime?view=net-7.0) __  |
| [`FormatTime`](ichartcanvas.cs.md#method-formattime)                     | _===_                                                                                                                                  |
| [`FormatValue`](ichartcanvas.cs.md#method-formatvalue)                   | _===_                                                                                                                                  |
| [`GetIndex`](ichartcanvas.cs.md#method-getindex)                         | _===_                                                                                                                                  |
| [`GetValue`](ichartcanvas.cs.md#method-getvalue)                         | Возвращает ценовое значение Y координаты                                                                                               |
| [`GetValueFromPos`](ichartcanvas.cs.md#method-getvaluefrompos)           | _===_                                                                                                                                  |
| [`GetX`](ichartcanvas.cs.md#method-getx)                                 | _Возвращает X координату индекса бара_                                                                                                 |
| [`GetXScreen`](ichartcanvas.cs.md#method-getxscreen)                     | _===_                                                                                                                                  |
| [`GetXX`](ichartcanvas.cs.md#method-getxx)                               | _===_                                                                                                                                  |
| [`GetY`](ichartcanvas.cs.md#method-gety)                                 | _Возвращает Y координату ценового значения_                                                                                            |
| [`IndexToDate`](ichartcanvas.cs.md#method-indextodate)                   | _Возвращает_ [_`DateTime`_](https://learn.microsoft.com/ru-ru/dotnet/api/system.datetime?view=net-7.0) _индекса бара_                  |

## Список свойств

| Название                                                     | Описание                                                                                                                                                        |
| ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`AfterBars`](ichartcanvas.cs.md#property-afterbars)         | _Возвращает количество пустых столбцов после последнего бара на канвасе_                                                                                        |
| [`ChartFont`](ichartcanvas.cs.md#property-chartfont)         | _Возвращает_ [_шрифт_](https://tigertrade.gitbook.io/doc/tech/tigertrade.dx/xfont.cs) _канваса_                                                                 |
| [`ChartFontBold`](ichartcanvas.cs.md#property-chartfontbold) | _===_                                                                                                                                                           |
| [`ColumnPercent`](ichartcanvas.cs.md#property-columnpercent) | _===_                                                                                                                                                           |
| [`ColumnWidth`](ichartcanvas.cs.md#property-columnwidth)     | _Возвращает ширину столбца_                                                                                                                                     |
| [`Count`](ichartcanvas.cs.md#property-count)                 | _Возвращает количество баров на канвасе_                                                                                                                        |
| [`IsStock`](ichartcanvas.cs.md#property-isstock)             | _===_                                                                                                                                                           |
| [`MaxY`](ichartcanvas.cs.md#property-maxy)                   | _===_                                                                                                                                                           |
| [`MinY`](ichartcanvas.cs.md#property-miny)                   | _===_                                                                                                                                                           |
| [`Rect`](ichartcanvas.cs.md#property-rect)                   | _Возвращает размеры и координаты канваса в виде объекта_ [_Rect_](https://learn.microsoft.com/en-us/dotnet/api/system.windows.rect?view=windowsdesktop-7.0) __  |
| [`Start`](ichartcanvas.cs.md#property-start)                 | _Возвращает индекс (справа налево) последнего бара на канвасе_                                                                                                  |
| [`StepHeight`](ichartcanvas.cs.md#property-stepheight)       | _Возвращает высоту(Y координату) минимального движения цены на канвасе_                                                                                         |
| [`StockType`](ichartcanvas.cs.md#property-stocktype)         | _===_                                                                                                                                                           |
| [`Stop`](ichartcanvas.cs.md#property-stop)                   | _Возвращает индекс первого бара на канвасе_                                                                                                                     |
| [`Theme`](ichartcanvas.cs.md#property-theme)                 | _Возвращает_ [_тему_ ](https://tigertrade.gitbook.io/doc/tech/tigertrade.chart/base/icharttheme.cs)_канваса_                                                    |

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

_Возвращает индекс бара находящегося по_ [_`DateTime`_](https://learn.microsoft.com/ru-ru/dotnet/api/system.datetime?view=net-7.0) __&#x20;

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

Возвращает ценовое значение Y координаты

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

_Возвращает X координату индекса бара_

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

_Возвращает Y координату ценового значения_

```csharp
double GetY(double d)
```

`d` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `IndexToDate` <a href="#method-indextodate" id="method-indextodate"></a>

_Возвращает_ [_`DateTime`_](https://learn.microsoft.com/ru-ru/dotnet/api/system.datetime?view=net-7.0) _индекса бара_

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

_Возвращает количество пустых столбцов после последнего бара на канвасе_

```csharp
int AfterBars { get; }
```

***

### `ChartFont` <a href="#property-chartfont" id="property-chartfont"></a>

_Возвращает_ [_шрифт_](https://tigertrade.gitbook.io/doc/tech/tigertrade.dx/xfont.cs) _канваса_

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

_Возвращает ширину столбца_

```csharp
double ColumnWidth { get; }
```

***

### `Count` <a href="#property-count" id="property-count"></a>

_Возвращает количество баров на канвасе_

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

_Возвращает размеры и координаты канваса в виде объекта_ [_Rect_](https://learn.microsoft.com/en-us/dotnet/api/system.windows.rect?view=windowsdesktop-7.0) __&#x20;

```csharp
Rect Rect { get; }
```

***

### `Start` <a href="#property-start" id="property-start"></a>

_Возвращает индекс (справа налево) последнего бара на канвасе_

```csharp
int Start { get; }
```

***

### `StepHeight` <a href="#property-stepheight" id="property-stepheight"></a>

_Возвращает высоту(Y координату) минимального движения цены на канвасе_

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

_Возвращает индекс первого бара на канвасе_

```csharp
int Stop { get; }
```

***

### `Theme` <a href="#property-theme" id="property-theme"></a>

_Возвращает_ [_тему_ ](https://tigertrade.gitbook.io/doc/tech/tigertrade.chart/base/icharttheme.cs)_канваса_

```csharp
IChartTheme Theme { get; }
```

***
