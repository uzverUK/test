
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


===

### Синтаксис
```csharp
public interface IChartCanvas
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertTimeFromLocal`](#method-converttimefromlocal) | *===* |
| [`ConvertTimeToLocal`](#method-converttimetolocal) | *===* |
| [`DateToIndex`](#method-datetoindex) | *===* |
| [`FormatTime`](#method-formattime) | *===* |
| [`FormatValue`](#method-formatvalue) | *===* |
| [`GetIndex`](#method-getindex) | *===* |
| [`GetValue`](#method-getvalue) | *===* |
| [`GetValueFromPos`](#method-getvaluefrompos) | *===* |
| [`GetX`](#method-getx) | *===* |
| [`GetXScreen`](#method-getxscreen) | *===* |
| [`GetXX`](#method-getxx) | *===* |
| [`GetY`](#method-gety) | *===* |
| [`IndexToDate`](#method-indextodate) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AfterBars`](#property-afterbars) | *===* |
| [`ChartFont`](#property-chartfont) | *===* |
| [`ChartFontBold`](#property-chartfontbold) | *===* |
| [`ColumnPercent`](#property-columnpercent) | *===* |
| [`ColumnWidth`](#property-columnwidth) | *===* |
| [`Count`](#property-count) | *===* |
| [`IsStock`](#property-isstock) | *===* |
| [`MaxY`](#property-maxy) | *===* |
| [`MinY`](#property-miny) | *===* |
| [`Rect`](#property-rect) | *===* |
| [`Start`](#property-start) | *===* |
| [`StepHeight`](#property-stepheight) | *===* |
| [`StockType`](#property-stocktype) | *===* |
| [`Stop`](#property-stop) | *===* |
| [`Theme`](#property-theme) | *===* |





***  
***  
# Методы

## `ConvertTimeFromLocal`<a href="method-converttimefromlocal" id="method-converttimefromlocal"></a>
===
```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  


***  

## `ConvertTimeToLocal`<a href="method-converttimetolocal" id="method-converttimetolocal"></a>
===
```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `DateToIndex`<a href="method-datetoindex" id="method-datetoindex"></a>
===
```csharp
int DateToIndex(DateTime dt, int dir)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`dir` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `DateToIndex`<a href="method-datetoindex" id="method-datetoindex"></a>
===
```csharp
int DateToIndex(DateTime dt, int dir)
int DateToIndex(double dt, int dir)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`dir` <mark style="color:red;">*`int`*</mark>  
 *===*  

`dt` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `FormatTime`<a href="method-formattime" id="method-formattime"></a>
===
```csharp
string FormatTime(DateTime dt, string format)
```
`format` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `FormatValue`<a href="method-formatvalue" id="method-formatvalue"></a>
===
```csharp
string FormatValue(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `GetIndex`<a href="method-getindex" id="method-getindex"></a>
===
```csharp
int GetIndex(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `GetValue`<a href="method-getvalue" id="method-getvalue"></a>
===
```csharp
double GetValue(double y)
```
`y` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `GetValueFromPos`<a href="method-getvaluefrompos" id="method-getvaluefrompos"></a>
===
```csharp
Point GetValueFromPos(double x, double y)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `GetValueFromPos`<a href="method-getvaluefrompos" id="method-getvaluefrompos"></a>
===
```csharp
Point GetValueFromPos(double x, double y)
Point GetValueFromPos(double x, double y, bool snapToGrid)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *===*  

`y` <mark style="color:red;">*`double`*</mark>  
 *===*  

`snapToGrid` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `GetX`<a href="method-getx" id="method-getx"></a>
===
```csharp
double GetX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `GetXScreen`<a href="method-getxscreen" id="method-getxscreen"></a>
===
```csharp
double GetXScreen(double x)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `GetXX`<a href="method-getxx" id="method-getxx"></a>
===
```csharp
double GetXX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `GetY`<a href="method-gety" id="method-gety"></a>
===
```csharp
double GetY(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `IndexToDate`<a href="method-indextodate" id="method-indextodate"></a>
===
```csharp
DateTime IndexToDate(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `AfterBars`<a href="property-afterbars" id="property-afterbars"></a>
===
```csharp
int AfterBars { get; }
```  
***

## `ChartFont`<a href="property-chartfont" id="property-chartfont"></a>
===
```csharp
XFont ChartFont { get; }
```  
***

## `ChartFontBold`<a href="property-chartfontbold" id="property-chartfontbold"></a>
===
```csharp
XFont ChartFontBold { get; }
```  
***

## `ColumnPercent`<a href="property-columnpercent" id="property-columnpercent"></a>
===
```csharp
double ColumnPercent { get; }
```  
***

## `ColumnWidth`<a href="property-columnwidth" id="property-columnwidth"></a>
===
```csharp
double ColumnWidth { get; }
```  
***

## `Count`<a href="property-count" id="property-count"></a>
===
```csharp
int Count { get; }
```  
***

## `IsStock`<a href="property-isstock" id="property-isstock"></a>
===
```csharp
bool IsStock { get; }
```  
***

## `MaxY`<a href="property-maxy" id="property-maxy"></a>
===
```csharp
double MaxY { get; }
```  
***

## `MinY`<a href="property-miny" id="property-miny"></a>
===
```csharp
double MinY { get; }
```  
***

## `Rect`<a href="property-rect" id="property-rect"></a>
===
```csharp
Rect Rect { get; }
```  
***

## `Start`<a href="property-start" id="property-start"></a>
===
```csharp
int Start { get; }
```  
***

## `StepHeight`<a href="property-stepheight" id="property-stepheight"></a>
===
```csharp
double StepHeight { get; }
```  
***

## `StockType`<a href="property-stocktype" id="property-stocktype"></a>
===
```csharp
ChartStockType StockType { get; }
```  
***

## `Stop`<a href="property-stop" id="property-stop"></a>
===
```csharp
int Stop { get; }
```  
***

## `Theme`<a href="property-theme" id="property-theme"></a>
===
```csharp
IChartTheme Theme { get; }
```  
***

