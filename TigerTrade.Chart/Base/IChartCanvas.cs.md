
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Base](../../TigerTrade.Chart/Base.md)


Описание

### Синтаксис
```csharp
public interface IChartCanvas
```


### Таблица методов
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

### Свойства
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

## ConvertTimeFromLocal
Описание

```csharp
DateTime ConvertTimeFromLocal(DateTime dt)
```

<mark style="color:yellow;">`dt`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***                

## ConvertTimeToLocal
Описание

```csharp
DateTime ConvertTimeToLocal(DateTime dt)
```

***                

## DateToIndex
Описание

```csharp
int DateToIndex(DateTime dt, int dir)
```

<mark style="color:yellow;">`dt`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

<mark style="color:yellow;">`dir`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## DateToIndex
Описание

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


***                

## FormatTime
Описание

```csharp
string FormatTime(DateTime dt, string format)
```
<mark style="color:yellow;">`format`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***                

## FormatValue
Описание

```csharp
string FormatValue(double d)
```
<mark style="color:yellow;">`d`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***                

## GetIndex
Описание

```csharp
int GetIndex(int i)
```
<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## GetValue
Описание

```csharp
double GetValue(double y)
```
<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***                

## GetValueFromPos
Описание

```csharp
Point GetValueFromPos(double x, double y)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***                

## GetValueFromPos
Описание

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


***                

## GetX
Описание

```csharp
double GetX(int i)
```
<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## GetXScreen
Описание

```csharp
double GetXScreen(double x)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***                

## GetXX
Описание

```csharp
double GetXX(int i)
```
<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## GetY
Описание

```csharp
double GetY(double d)
```
<mark style="color:yellow;">`d`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***                

## IndexToDate
Описание

```csharp
DateTime IndexToDate(int i)
```
<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                
                ***
  ***
  # Свойства

## AfterBars
Описание

```csharp
int AfterBars { get; }
```
***

## ChartFont
Описание

```csharp
XFont ChartFont { get; }
```
***

## ChartFontBold
Описание

```csharp
XFont ChartFontBold { get; }
```
***

## ColumnPercent
Описание

```csharp
double ColumnPercent { get; }
```
***

## ColumnWidth
Описание

```csharp
double ColumnWidth { get; }
```
***

## Count
Описание

```csharp
int Count { get; }
```
***

## IsStock
Описание

```csharp
bool IsStock { get; }
```
***

## MaxY
Описание

```csharp
double MaxY { get; }
```
***

## MinY
Описание

```csharp
double MinY { get; }
```
***

## Rect
Описание

```csharp
Rect Rect { get; }
```
***

## Start
Описание

```csharp
int Start { get; }
```
***

## StepHeight
Описание

```csharp
double StepHeight { get; }
```
***

## StockType
Описание

```csharp
ChartStockType StockType { get; }
```
***

## Stop
Описание

```csharp
int Stop { get; }
```
***

## Theme
Описание

```csharp
IChartTheme Theme { get; }
```
***

