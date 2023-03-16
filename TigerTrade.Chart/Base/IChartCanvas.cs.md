
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartCanvas
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertTimeFromLocal`](#method-converttimefromlocal) | *Описание* |
| [`ConvertTimeToLocal`](#method-converttimetolocal) | *Описание* |
| [`DateToIndex`](#method-datetoindex) | *Описание* |
| [`FormatTime`](#method-formattime) | *Описание* |
| [`FormatValue`](#method-formatvalue) | *Описание* |
| [`GetIndex`](#method-getindex) | *Описание* |
| [`GetValue`](#method-getvalue) | *Описание* |
| [`GetValueFromPos`](#method-getvaluefrompos) | *Описание* |
| [`GetX`](#method-getx) | *Описание* |
| [`GetXScreen`](#method-getxscreen) | *Описание* |
| [`GetXX`](#method-getxx) | *Описание* |
| [`GetY`](#method-gety) | *Описание* |
| [`IndexToDate`](#method-indextodate) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AfterBars`](#property-afterbars) | *Описание* |
| [`ChartFont`](#property-chartfont) | *Описание* |
| [`ChartFontBold`](#property-chartfontbold) | *Описание* |
| [`ColumnPercent`](#property-columnpercent) | *Описание* |
| [`ColumnWidth`](#property-columnwidth) | *Описание* |
| [`Count`](#property-count) | *Описание* |
| [`IsStock`](#property-isstock) | *Описание* |
| [`MaxY`](#property-maxy) | *Описание* |
| [`MinY`](#property-miny) | *Описание* |
| [`Rect`](#property-rect) | *Описание* |
| [`Start`](#property-start) | *Описание* |
| [`StepHeight`](#property-stepheight) | *Описание* |
| [`StockType`](#property-stocktype) | *Описание* |
| [`Stop`](#property-stop) | *Описание* |
| [`Theme`](#property-theme) | *Описание* |





***  
***  
# Методы

## `ConvertTimeFromLocal`<a href="method-converttimefromlocal" id="method-converttimefromlocal"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ConvertTimeToLocal`<a href="method-converttimetolocal" id="method-converttimetolocal"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `DateToIndex`<a href="method-datetoindex" id="method-datetoindex"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int DateToIndex(DateTime dt, int dir)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`dir` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `DateToIndex`<a href="method-datetoindex" id="method-datetoindex"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int DateToIndex(DateTime dt, int dir)
int DateToIndex(double dt, int dir)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`dir` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`dt` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `FormatTime`<a href="method-formattime" id="method-formattime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTime(DateTime dt, string format)
```
`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatValue`<a href="method-formatvalue" id="method-formatvalue"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatValue(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetIndex`<a href="method-getindex" id="method-getindex"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int GetIndex(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetValue`<a href="method-getvalue" id="method-getvalue"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetValue(double y)
```
`y` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetValueFromPos`<a href="method-getvaluefrompos" id="method-getvaluefrompos"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Point GetValueFromPos(double x, double y)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetValueFromPos`<a href="method-getvaluefrompos" id="method-getvaluefrompos"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Point GetValueFromPos(double x, double y)
Point GetValueFromPos(double x, double y, bool snapToGrid)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`snapToGrid` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetX`<a href="method-getx" id="method-getx"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetXScreen`<a href="method-getxscreen" id="method-getxscreen"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetXScreen(double x)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetXX`<a href="method-getxx" id="method-getxx"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetXX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetY`<a href="method-gety" id="method-gety"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetY(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `IndexToDate`<a href="method-indextodate" id="method-indextodate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime IndexToDate(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `AfterBars`<a href="property-afterbars" id="property-afterbars"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int AfterBars { get; }
```  
***

## `ChartFont`<a href="property-chartfont" id="property-chartfont"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
XFont ChartFont { get; }
```  
***

## `ChartFontBold`<a href="property-chartfontbold" id="property-chartfontbold"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
XFont ChartFontBold { get; }
```  
***

## `ColumnPercent`<a href="property-columnpercent" id="property-columnpercent"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double ColumnPercent { get; }
```  
***

## `ColumnWidth`<a href="property-columnwidth" id="property-columnwidth"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double ColumnWidth { get; }
```  
***

## `Count`<a href="property-count" id="property-count"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Count { get; }
```  
***

## `IsStock`<a href="property-isstock" id="property-isstock"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
bool IsStock { get; }
```  
***

## `MaxY`<a href="property-maxy" id="property-maxy"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double MaxY { get; }
```  
***

## `MinY`<a href="property-miny" id="property-miny"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double MinY { get; }
```  
***

## `Rect`<a href="property-rect" id="property-rect"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Rect Rect { get; }
```  
***

## `Start`<a href="property-start" id="property-start"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Start { get; }
```  
***

## `StepHeight`<a href="property-stepheight" id="property-stepheight"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double StepHeight { get; }
```  
***

## `StockType`<a href="property-stocktype" id="property-stocktype"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
ChartStockType StockType { get; }
```  
***

## `Stop`<a href="property-stop" id="property-stop"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Stop { get; }
```  
***

## `Theme`<a href="property-theme" id="property-theme"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartTheme Theme { get; }
```  
***

