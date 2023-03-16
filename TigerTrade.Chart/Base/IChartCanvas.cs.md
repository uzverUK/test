
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

## `ConvertTimeFromLocal`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ConvertTimeToLocal`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `DateToIndex`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int DateToIndex(DateTime dt, int dir)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`dir` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `DateToIndex`<a href="IndexToDate-m" id="IndexToDate-m"></a>
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

## `FormatTime`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTime(DateTime dt, string format)
```
`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatValue`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatValue(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetIndex`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int GetIndex(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetValue`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetValue(double y)
```
`y` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetValueFromPos`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Point GetValueFromPos(double x, double y)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetValueFromPos`<a href="IndexToDate-m" id="IndexToDate-m"></a>
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

## `GetX`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetXScreen`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetXScreen(double x)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetXX`<a href="IndexToDate-m" id="IndexToDate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetXX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetY`<a href="IndexToDate-m" id="IndexToDate-m"></a>
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

## `AfterBars`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int AfterBars { get; }
```  
***

## `ChartFont`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
XFont ChartFont { get; }
```  
***

## `ChartFontBold`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
XFont ChartFontBold { get; }
```  
***

## `ColumnPercent`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double ColumnPercent { get; }
```  
***

## `ColumnWidth`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double ColumnWidth { get; }
```  
***

## `Count`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Count { get; }
```  
***

## `IsStock`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
bool IsStock { get; }
```  
***

## `MaxY`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double MaxY { get; }
```  
***

## `MinY`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double MinY { get; }
```  
***

## `Rect`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Rect Rect { get; }
```  
***

## `Start`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Start { get; }
```  
***

## `StepHeight`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double StepHeight { get; }
```  
***

## `StockType`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
ChartStockType StockType { get; }
```  
***

## `Stop`<a href="Theme-p" id="Theme-p"></a>
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

