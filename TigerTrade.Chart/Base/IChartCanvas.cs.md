
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartCanvas
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ConvertTimeFromLocal`](./IChartCanvas.cs/Методы/ConvertTimeFromLocal.md) | *Описание* |
| [`ConvertTimeToLocal`](./IChartCanvas.cs/Методы/ConvertTimeToLocal.md) | *Описание* |
| [`DateToIndex`](./IChartCanvas.cs/Методы/DateToIndex.md) | *Описание* |
| [`FormatTime`](./IChartCanvas.cs/Методы/FormatTime.md) | *Описание* |
| [`FormatValue`](./IChartCanvas.cs/Методы/FormatValue.md) | *Описание* |
| [`GetIndex`](./IChartCanvas.cs/Методы/GetIndex.md) | *Описание* |
| [`GetValue`](./IChartCanvas.cs/Методы/GetValue.md) | *Описание* |
| [`GetValueFromPos`](./IChartCanvas.cs/Методы/GetValueFromPos.md) | *Описание* |
| [`GetX`](./IChartCanvas.cs/Методы/GetX.md) | *Описание* |
| [`GetXScreen`](./IChartCanvas.cs/Методы/GetXScreen.md) | *Описание* |
| [`GetXX`](./IChartCanvas.cs/Методы/GetXX.md) | *Описание* |
| [`GetY`](./IChartCanvas.cs/Методы/GetY.md) | *Описание* |
| [`IndexToDate`](./IChartCanvas.cs/Методы/IndexToDate.md) | *Описание* |

# Таблица свойств
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





# Методы

## *ConvertTimeFromLocal*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

<mark style="color:yellow;">`dt`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  



## *ConvertTimeToLocal*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```


## *DateToIndex*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int DateToIndex(DateTime dt, int dir)
```

<mark style="color:yellow;">`dt`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

<mark style="color:yellow;">`dir`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *DateToIndex*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int DateToIndex(DateTime dt, int dir)
int DateToIndex(double dt, int dir)
```

<mark style="color:yellow;">`dt`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

<mark style="color:yellow;">`dir`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`dt`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *FormatTime*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatTime(DateTime dt, string format)
```
<mark style="color:yellow;">`format`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *FormatValue*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
string FormatValue(double d)
```
<mark style="color:yellow;">`d`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *GetIndex*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int GetIndex(int i)
```
<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *GetValue*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetValue(double y)
```
<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *GetValueFromPos*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Point GetValueFromPos(double x, double y)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *GetValueFromPos*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Point GetValueFromPos(double x, double y)
Point GetValueFromPos(double x, double y, bool snapToGrid)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:yellow;">`snapToGrid`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *GetX*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetX(int i)
```
<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *GetXScreen*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetXScreen(double x)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *GetXX*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetXX(int i)
```
<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *GetY*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double GetY(double d)
```
<mark style="color:yellow;">`d`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *IndexToDate*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime IndexToDate(int i)
```
<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


# Свойства

## *AfterBars*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int AfterBars { get; }
```

## *ChartFont*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
XFont ChartFont { get; }
```

## *ChartFontBold*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
XFont ChartFontBold { get; }
```

## *ColumnPercent*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double ColumnPercent { get; }
```

## *ColumnWidth*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double ColumnWidth { get; }
```

## *Count*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Count { get; }
```

## *IsStock*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
bool IsStock { get; }
```

## *MaxY*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double MaxY { get; }
```

## *MinY*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double MinY { get; }
```

## *Rect*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
Rect Rect { get; }
```

## *Start*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Start { get; }
```

## *StepHeight*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double StepHeight { get; }
```

## *StockType*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
ChartStockType StockType { get; }
```

## *Stop*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Stop { get; }
```

## *Theme*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartTheme Theme { get; }
```

