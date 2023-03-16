
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public abstract class ObjectBase : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddAlert`](#AddAlert-m) | *Описание* |
| [`ApplyTheme`](#ApplyTheme-m) | *Описание* |
| [`BeginDrag`](#BeginDrag-m) | *Описание* |
| [`CheckAlert`](#CheckAlert-m) | *Описание* |
| [`ControlPointEditing`](#ControlPointEditing-m) | *Описание* |
| [`ControlPointsChanged`](#ControlPointsChanged-m) | *Описание* |
| [`CopyTemplate`](#CopyTemplate-m) | *Описание* |
| [`DragObject`](#DragObject-m) | *Описание* |
| [`Draw`](#Draw-m) | *Описание* |
| [`DrawControlPoint`](#DrawControlPoint-m) | *Описание* |
| [`DrawControlPoints`](#DrawControlPoints-m) | *Описание* |
| [`DrawObject`](#DrawObject-m) | *Описание* |
| [`ExtraPointChanged`](#ExtraPointChanged-m) | *Описание* |
| [`GetAlerts`](#GetAlerts-m) | *Описание* |
| [`GetControlPoint`](#GetControlPoint-m) | *Описание* |
| [`GetExtraPoint`](#GetExtraPoint-m) | *Описание* |
| [`GetMinDist`](#GetMinDist-m) | *Описание* |
| [`GetMinDistance`](#GetMinDistance-m) | *Описание* |
| [`GetPropertyHasStandardValues`](#GetPropertyHasStandardValues-m) | *Описание* |
| [`GetPropertyReadOnly`](#GetPropertyReadOnly-m) | *Описание* |
| [`GetPropertyStandardValues`](#GetPropertyStandardValues-m) | *Описание* |
| [`GetPropertyVisibility`](#GetPropertyVisibility-m) | *Описание* |
| [`GetX`](#GetX-m) | *Описание* |
| [`GetY`](#GetY-m) | *Описание* |
| [`InObject`](#InObject-m) | *Описание* |
| [`IsObjectInArea`](#IsObjectInArea-m) | *Описание* |
| [`IsObjectOnChart`](#IsObjectOnChart-m) | *Описание* |
| [`ObjectBase`](#ObjectBase-m) | *Описание* |
| [`OnPropertyChanged`](#OnPropertyChanged-m) | *Описание* |
| [`Prepare`](#Prepare-m) | *Описание* |
| [`SetCanvas`](#SetCanvas-m) | *Описание* |
| [`SetDataProvider`](#SetDataProvider-m) | *Описание* |
| [`SetSettings`](#SetSettings-m) | *Описание* |
| [`ToPoint`](#ToPoint-m) | *Описание* |
| [`ToPoints`](#ToPoints-m) | *Описание* |
| [`ToString`](#ToString-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Canvas`](#Canvas-p) | *Описание* |
| [`ChartDataType`](#ChartDataType-p) | *Описание* |
| [`ControlPointNum`](#ControlPointNum-p) | *Описание* |
| [`ControlPoints`](#ControlPoints-p) | *Описание* |
| [`ControlPointsList`](#ControlPointsList-p) | *Описание* |
| [`DataProvider`](#DataProvider-p) | *Описание* |
| [`ID`](#ID-p) | *Описание* |
| [`InMove;`](#InMove;-p) | *Описание* |
| [`InSetup;`](#InSetup;-p) | *Описание* |
| [`Lock`](#Lock-p) | *Описание* |
| [`Name`](#Name-p) | *Описание* |
| [`ObjectID`](#ObjectID-p) | *Описание* |
| [`PenWidth`](#PenWidth-p) | *Описание* |
| [`Periods`](#Periods-p) | *Описание* |
| [`Position`](#Position-p) | *Описание* |
| [`Settings`](#Settings-p) | *Описание* |
| [`SnapGrid`](#SnapGrid-p) | *Описание* |
| [`SymbolID`](#SymbolID-p) | *Описание* |
| [`Theme`](#Theme-p) | *Описание* |
| [`Title`](#Title-p) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#PropertyChanged-p) | *Описание* |





***  
***  
# Методы

## `AddAlert`<a href="AddAlert-m" id="AddAlert-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void AddAlert(ChartAlertSettings settings, string message)
```

`settings` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

`message` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ApplyTheme`<a href="ApplyTheme-m" id="ApplyTheme-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ApplyTheme(IChartTheme theme)
```
`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `BeginDrag`<a href="BeginDrag-m" id="BeginDrag-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void BeginDrag()
```

***  

## `CheckAlert`<a href="CheckAlert-m" id="CheckAlert-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CheckAlert(List<IndicatorBase> indicators)
```

***  

## `ControlPointEditing`<a href="ControlPointEditing-m" id="ControlPointEditing-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ControlPointEditing(int index)
```

`index` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `ControlPointsChanged`<a href="ControlPointsChanged-m" id="ControlPointsChanged-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ControlPointsChanged()
```

***  

## `CopyTemplate`<a href="CopyTemplate-m" id="CopyTemplate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `DragObject`<a href="DragObject-m" id="DragObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void DragObject(double dx, double dy)
```
`dx` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`dy` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `Draw`<a href="Draw-m" id="Draw-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `DrawControlPoint`<a href="DrawControlPoint-m" id="DrawControlPoint-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void DrawControlPoint(DxVisualQueue visual, Point point)
```
`point` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  


***  

## `DrawControlPoints`<a href="DrawControlPoints-m" id="DrawControlPoints-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void DrawControlPoints(DxVisualQueue visual)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `DrawObject`<a href="DrawObject-m" id="DrawObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawObject(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `ExtraPointChanged`<a href="ExtraPointChanged-m" id="ExtraPointChanged-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ExtraPointChanged(int index, ObjectPoint op)
```
`index` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***  

## `GetAlerts`<a href="GetAlerts-m" id="GetAlerts-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartAlertInfo> GetAlerts()
```

***  

## `GetControlPoint`<a href="GetControlPoint-m" id="GetControlPoint-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual int GetControlPoint(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetExtraPoint`<a href="GetExtraPoint-m" id="GetExtraPoint-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual int GetExtraPoint(int x, int y)
```

***  

## `GetMinDist`<a href="GetMinDist-m" id="GetMinDist-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual int GetMinDist(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetMinDistance`<a href="GetMinDistance-m" id="GetMinDistance-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int GetMinDistance(int x, int y)
```

***  

## `GetPropertyHasStandardValues`<a href="GetPropertyHasStandardValues-m" id="GetPropertyHasStandardValues-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyHasStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyReadOnly`<a href="GetPropertyReadOnly-m" id="GetPropertyReadOnly-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyReadOnly(string propertyName)
```

***  

## `GetPropertyStandardValues`<a href="GetPropertyStandardValues-m" id="GetPropertyStandardValues-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyVisibility`<a href="GetPropertyVisibility-m" id="GetPropertyVisibility-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyVisibility(string propertyName)
```

***  

## `GetX`<a href="GetX-m" id="GetX-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetX(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetY`<a href="GetY-m" id="GetY-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetY(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `InObject`<a href="InObject-m" id="InObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool InObject(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `IsObjectInArea`<a href="IsObjectInArea-m" id="IsObjectInArea-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool IsObjectInArea()
```

***  

## `IsObjectOnChart`<a href="IsObjectOnChart-m" id="IsObjectOnChart-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool IsObjectOnChart()
```

***  

## `ObjectBase`<a href="ObjectBase-m" id="ObjectBase-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected ObjectBase()
```

***  

## `OnPropertyChanged`<a href="OnPropertyChanged-m" id="OnPropertyChanged-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Prepare`<a href="Prepare-m" id="Prepare-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void Prepare()
```

***  

## `SetCanvas`<a href="SetCanvas-m" id="SetCanvas-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetCanvas(IChartCanvas canvas)
```

`canvas` <mark style="color:red;">*`IChartCanvas`*</mark>  
 *Описание*  


***  

## `SetDataProvider`<a href="SetDataProvider-m" id="SetDataProvider-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetDataProvider(IChartDataProvider dp)
```
`dp` <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *Описание*  


***  

## `SetSettings`<a href="SetSettings-m" id="SetSettings-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetSettings(IChartSettings settings)
```
`settings` <mark style="color:red;">*`IChartSettings`*</mark>  
 *Описание*  


***  

## `ToPoint`<a href="ToPoint-m" id="ToPoint-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Point ToPoint(ObjectPoint op)
```
`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***  

## `ToPoints`<a href="ToPoints-m" id="ToPoints-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] ToPoints(ObjectPoint[] ops)
```

***  

## `ToString`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Canvas`<a href="Canvas-p" id="Canvas-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartCanvas Canvas { get; private set; }
```  
***

## `ChartDataType`<a href="ChartDataType-p" id="ChartDataType-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

## `ControlPointNum`<a href="ControlPointNum-p" id="ControlPointNum-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int ControlPointNum { get; }
```  
***

## `ControlPoints`<a href="ControlPoints-p" id="ControlPoints-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPoint[] ControlPoints { get; set; }
```  
***

## `ControlPointsList`<a href="ControlPointsList-p" id="ControlPointsList-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPointInfo[] ControlPointsList { get; }
```  
***

## `DataProvider`<a href="DataProvider-p" id="DataProvider-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```  
***

## `ID`<a href="ID-p" id="ID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `InMove;`<a href="InMove;-p" id="InMove;-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool InMove; {}
```  
***

## `InSetup;`<a href="InSetup;-p" id="InSetup;-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool InSetup; {}
```  
***

## `Lock`<a href="Lock-p" id="Lock-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Lock { get; set; }
```  
***

## `Name`<a href="Name-p" id="Name-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `ObjectID`<a href="ObjectID-p" id="ObjectID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ObjectID { get; set; }
```  
***

## `PenWidth`<a href="PenWidth-p" id="PenWidth-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual int PenWidth { get; }
```  
***

## `Periods`<a href="Periods-p" id="Periods-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPeriods Periods { get; set; }
```  
***

## `Position`<a href="Position-p" id="Position-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPosition Position { get; set; }
```  
***

## `Settings`<a href="Settings-p" id="Settings-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartSettings Settings { get; private set; }
```  
***

## `SnapGrid`<a href="SnapGrid-p" id="SnapGrid-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool SnapGrid { get; }
```  
***

## `SymbolID`<a href="SymbolID-p" id="SymbolID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SymbolID { get; set; }
```  
***

## `Theme`<a href="Theme-p" id="Theme-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartTheme Theme { get; private set; }
```  
***

## `Title`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Title { get; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="PropertyChanged-p" id="PropertyChanged-p"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

