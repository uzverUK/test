
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartCanvas
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertTimeFromLocal`](#ConvertTimeFromLocal-m) | *Описание* |
| [`ConvertTimeToLocal`](#ConvertTimeToLocal-m) | *Описание* |
| [`DateToIndex`](#DateToIndex-m) | *Описание* |
| [`FormatTime`](#FormatTime-m) | *Описание* |
| [`FormatValue`](#FormatValue-m) | *Описание* |
| [`GetIndex`](#GetIndex-m) | *Описание* |
| [`GetValue`](#GetValue-m) | *Описание* |
| [`GetValueFromPos`](#GetValueFromPos-m) | *Описание* |
| [`GetX`](#GetX-m) | *Описание* |
| [`GetXScreen`](#GetXScreen-m) | *Описание* |
| [`GetXX`](#GetXX-m) | *Описание* |
| [`GetY`](#GetY-m) | *Описание* |
| [`IndexToDate`](#IndexToDate-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AfterBars`](#AfterBars-p) | *Описание* |
| [`ChartFont`](#ChartFont-p) | *Описание* |
| [`ChartFontBold`](#ChartFontBold-p) | *Описание* |
| [`ColumnPercent`](#ColumnPercent-p) | *Описание* |
| [`ColumnWidth`](#ColumnWidth-p) | *Описание* |
| [`Count`](#Count-p) | *Описание* |
| [`IsStock`](#IsStock-p) | *Описание* |
| [`MaxY`](#MaxY-p) | *Описание* |
| [`MinY`](#MinY-p) | *Описание* |
| [`Rect`](#Rect-p) | *Описание* |
| [`Start`](#Start-p) | *Описание* |
| [`StepHeight`](#StepHeight-p) | *Описание* |
| [`StockType`](#StockType-p) | *Описание* |
| [`Stop`](#Stop-p) | *Описание* |
| [`Theme`](#Theme-p) | *Описание* |





***  
***  
# Методы

## `ConvertTimeFromLocal`<a href="ConvertTimeFromLocal-m" id="ConvertTimeFromLocal-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ConvertTimeToLocal`<a href="ConvertTimeToLocal-m" id="ConvertTimeToLocal-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `DateToIndex`<a href="DateToIndex-m" id="DateToIndex-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int DateToIndex(DateTime dt, int dir)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`dir` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `DateToIndex`<a href="DateToIndex-m" id="DateToIndex-m"></a>
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

## `FormatTime`<a href="FormatTime-m" id="FormatTime-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTime(DateTime dt, string format)
```
`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatValue`<a href="FormatValue-m" id="FormatValue-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatValue(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetIndex`<a href="GetIndex-m" id="GetIndex-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int GetIndex(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetValue`<a href="GetValue-m" id="GetValue-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetValue(double y)
```
`y` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetValueFromPos`<a href="GetValueFromPos-m" id="GetValueFromPos-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Point GetValueFromPos(double x, double y)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetValueFromPos`<a href="GetValueFromPos-m" id="GetValueFromPos-m"></a>
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

## `GetX`<a href="GetX-m" id="GetX-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetXScreen`<a href="GetXScreen-m" id="GetXScreen-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetXScreen(double x)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetXX`<a href="GetXX-m" id="GetXX-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetXX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetY`<a href="GetY-m" id="GetY-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetY(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `IndexToDate`<a href="IndexToDate-m" id="IndexToDate-m"></a>
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

## `AfterBars`<a href="AfterBars-p" id="AfterBars-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int AfterBars { get; }
```  
***

## `ChartFont`<a href="ChartFont-p" id="ChartFont-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
XFont ChartFont { get; }
```  
***

## `ChartFontBold`<a href="ChartFontBold-p" id="ChartFontBold-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
XFont ChartFontBold { get; }
```  
***

## `ColumnPercent`<a href="ColumnPercent-p" id="ColumnPercent-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double ColumnPercent { get; }
```  
***

## `ColumnWidth`<a href="ColumnWidth-p" id="ColumnWidth-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double ColumnWidth { get; }
```  
***

## `Count`<a href="Count-p" id="Count-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Count { get; }
```  
***

## `IsStock`<a href="IsStock-p" id="IsStock-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
bool IsStock { get; }
```  
***

## `MaxY`<a href="MaxY-p" id="MaxY-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double MaxY { get; }
```  
***

## `MinY`<a href="MinY-p" id="MinY-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double MinY { get; }
```  
***

## `Rect`<a href="Rect-p" id="Rect-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Rect Rect { get; }
```  
***

## `Start`<a href="Start-p" id="Start-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Start { get; }
```  
***

## `StepHeight`<a href="StepHeight-p" id="StepHeight-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double StepHeight { get; }
```  
***

## `StockType`<a href="StockType-p" id="StockType-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
ChartStockType StockType { get; }
```  
***

## `Stop`<a href="Stop-p" id="Stop-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Stop { get; }
```  
***

## `Theme`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartTheme Theme { get; }
```  
***

