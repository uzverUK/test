
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartCanvas
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ConvertTimeFromLocal`](#test) | *Описание* |
| [`ConvertTimeToLocal`](#test) | *Описание* |
| [`DateToIndex`](#test) | *Описание* |
| [`FormatTime`](#test) | *Описание* |
| [`FormatValue`](#test) | *Описание* |
| [`GetIndex`](#test) | *Описание* |
| [`GetValue`](#test) | *Описание* |
| [`GetValueFromPos`](#test) | *Описание* |
| [`GetX`](#test) | *Описание* |
| [`GetXScreen`](#test) | *Описание* |
| [`GetXX`](#test) | *Описание* |
| [`GetY`](#test) | *Описание* |
| [`IndexToDate`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AfterBars`](./IChartCanvas.cs/Свойства/AfterBars.md) | *Описание* |
| [`ChartFont`](./IChartCanvas.cs/Свойства/ChartFont.md) | *Описание* |
| [`ChartFontBold`](./IChartCanvas.cs/Свойства/ChartFontBold.md) | *Описание* |
| [`ColumnPercent`](./IChartCanvas.cs/Свойства/ColumnPercent.md) | *Описание* |
| [`ColumnWidth`](./IChartCanvas.cs/Свойства/ColumnWidth.md) | *Описание* |
| [`Count`](./IChartCanvas.cs/Свойства/Count.md) | *Описание* |
| [`IsStock`](./IChartCanvas.cs/Свойства/IsStock.md) | *Описание* |
| [`MaxY`](./IChartCanvas.cs/Свойства/MaxY.md) | *Описание* |
| [`MinY`](./IChartCanvas.cs/Свойства/MinY.md) | *Описание* |
| [`Rect`](./IChartCanvas.cs/Свойства/Rect.md) | *Описание* |
| [`Start`](./IChartCanvas.cs/Свойства/Start.md) | *Описание* |
| [`StepHeight`](./IChartCanvas.cs/Свойства/StepHeight.md) | *Описание* |
| [`StockType`](./IChartCanvas.cs/Свойства/StockType.md) | *Описание* |
| [`Stop`](./IChartCanvas.cs/Свойства/Stop.md) | *Описание* |
| [`Theme`](./IChartCanvas.cs/Свойства/Theme.md) | *Описание* |





***  
***  
# Методы

## `ConvertTimeFromLocal`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ConvertTimeToLocal`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `DateToIndex`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int DateToIndex(DateTime dt, int dir)
```

`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`dir` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `DateToIndex`<a href="test" id="test"></a>
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

## `FormatTime`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTime(DateTime dt, string format)
```
`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatValue`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatValue(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetIndex`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int GetIndex(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetValue`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetValue(double y)
```
`y` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetValueFromPos`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Point GetValueFromPos(double x, double y)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetValueFromPos`<a href="test" id="test"></a>
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

## `GetX`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetXScreen`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetXScreen(double x)
```
`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetXX`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetXX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetY`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetY(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `IndexToDate`<a href="test" id="test"></a>
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

## `AfterBars`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int AfterBars { get; }
```  
***

## `ChartFont`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
XFont ChartFont { get; }
```  
***

## `ChartFontBold`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
XFont ChartFontBold { get; }
```  
***

## `ColumnPercent`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double ColumnPercent { get; }
```  
***

## `ColumnWidth`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double ColumnWidth { get; }
```  
***

## `Count`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Count { get; }
```  
***

## `IsStock`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
bool IsStock { get; }
```  
***

## `MaxY`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double MaxY { get; }
```  
***

## `MinY`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double MinY { get; }
```  
***

## `Rect`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Rect Rect { get; }
```  
***

## `Start`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Start { get; }
```  
***

## `StepHeight`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double StepHeight { get; }
```  
***

## `StockType`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
ChartStockType StockType { get; }
```  
***

## `Stop`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Stop { get; }
```  
***

## `Theme`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartTheme Theme { get; }
```  
***

