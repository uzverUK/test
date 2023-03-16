
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

## `AddAlert`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void AddAlert(ChartAlertSettings settings, string message)
```

`settings` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

`message` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ApplyTheme`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ApplyTheme(IChartTheme theme)
```
`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `BeginDrag`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void BeginDrag()
```

***  

## `CheckAlert`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CheckAlert(List<IndicatorBase> indicators)
```

***  

## `ControlPointEditing`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ControlPointEditing(int index)
```

`index` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `ControlPointsChanged`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ControlPointsChanged()
```

***  

## `CopyTemplate`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `DragObject`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void DragObject(double dx, double dy)
```
`dx` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`dy` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `Draw`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `DrawControlPoint`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void DrawControlPoint(DxVisualQueue visual, Point point)
```
`point` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  


***  

## `DrawControlPoints`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void DrawControlPoints(DxVisualQueue visual)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `DrawObject`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawObject(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `ExtraPointChanged`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ExtraPointChanged(int index, ObjectPoint op)
```
`index` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***  

## `GetAlerts`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartAlertInfo> GetAlerts()
```

***  

## `GetControlPoint`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual int GetControlPoint(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetExtraPoint`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual int GetExtraPoint(int x, int y)
```

***  

## `GetMinDist`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual int GetMinDist(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetMinDistance`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int GetMinDistance(int x, int y)
```

***  

## `GetPropertyHasStandardValues`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyHasStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyReadOnly`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyReadOnly(string propertyName)
```

***  

## `GetPropertyStandardValues`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyVisibility`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyVisibility(string propertyName)
```

***  

## `GetX`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetX(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetY`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetY(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `InObject`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool InObject(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `IsObjectInArea`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool IsObjectInArea()
```

***  

## `IsObjectOnChart`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool IsObjectOnChart()
```

***  

## `ObjectBase`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected ObjectBase()
```

***  

## `OnPropertyChanged`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Prepare`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void Prepare()
```

***  

## `SetCanvas`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetCanvas(IChartCanvas canvas)
```

`canvas` <mark style="color:red;">*`IChartCanvas`*</mark>  
 *Описание*  


***  

## `SetDataProvider`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetDataProvider(IChartDataProvider dp)
```
`dp` <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *Описание*  


***  

## `SetSettings`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetSettings(IChartSettings settings)
```
`settings` <mark style="color:red;">*`IChartSettings`*</mark>  
 *Описание*  


***  

## `ToPoint`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Point ToPoint(ObjectPoint op)
```
`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***  

## `ToPoints`<a href="ToString-m" id="ToString-m"></a>
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

## `Canvas`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartCanvas Canvas { get; private set; }
```  
***

## `ChartDataType`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

## `ControlPointNum`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int ControlPointNum { get; }
```  
***

## `ControlPoints`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPoint[] ControlPoints { get; set; }
```  
***

## `ControlPointsList`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPointInfo[] ControlPointsList { get; }
```  
***

## `DataProvider`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```  
***

## `ID`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `InMove;`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool InMove; {}
```  
***

## `InSetup;`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool InSetup; {}
```  
***

## `Lock`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Lock { get; set; }
```  
***

## `Name`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `ObjectID`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ObjectID { get; set; }
```  
***

## `PenWidth`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual int PenWidth { get; }
```  
***

## `Periods`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPeriods Periods { get; set; }
```  
***

## `Position`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPosition Position { get; set; }
```  
***

## `Settings`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartSettings Settings { get; private set; }
```  
***

## `SnapGrid`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool SnapGrid { get; }
```  
***

## `SymbolID`<a href="Title-p" id="Title-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SymbolID { get; set; }
```  
***

## `Theme`<a href="Title-p" id="Title-p"></a>
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

