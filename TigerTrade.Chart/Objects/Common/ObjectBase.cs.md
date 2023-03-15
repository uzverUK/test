
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public abstract class ObjectBase : INotifyPropertyChanged, IDynamicProperty
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`AddAlert`](./ObjectBase.cs/Методы/AddAlert.md) | *Описание* |
| [`ApplyTheme`](./ObjectBase.cs/Методы/ApplyTheme.md) | *Описание* |
| [`BeginDrag`](./ObjectBase.cs/Методы/BeginDrag.md) | *Описание* |
| [`CheckAlert`](./ObjectBase.cs/Методы/CheckAlert.md) | *Описание* |
| [`ControlPointEditing`](./ObjectBase.cs/Методы/ControlPointEditing.md) | *Описание* |
| [`ControlPointsChanged`](./ObjectBase.cs/Методы/ControlPointsChanged.md) | *Описание* |
| [`CopyTemplate`](./ObjectBase.cs/Методы/CopyTemplate.md) | *Описание* |
| [`DragObject`](./ObjectBase.cs/Методы/DragObject.md) | *Описание* |
| [`Draw`](./ObjectBase.cs/Методы/Draw.md) | *Описание* |
| [`DrawControlPoint`](./ObjectBase.cs/Методы/DrawControlPoint.md) | *Описание* |
| [`DrawControlPoints`](./ObjectBase.cs/Методы/DrawControlPoints.md) | *Описание* |
| [`DrawObject`](./ObjectBase.cs/Методы/DrawObject.md) | *Описание* |
| [`ExtraPointChanged`](./ObjectBase.cs/Методы/ExtraPointChanged.md) | *Описание* |
| [`GetAlerts`](./ObjectBase.cs/Методы/GetAlerts.md) | *Описание* |
| [`GetControlPoint`](./ObjectBase.cs/Методы/GetControlPoint.md) | *Описание* |
| [`GetExtraPoint`](./ObjectBase.cs/Методы/GetExtraPoint.md) | *Описание* |
| [`GetMinDist`](./ObjectBase.cs/Методы/GetMinDist.md) | *Описание* |
| [`GetMinDistance`](./ObjectBase.cs/Методы/GetMinDistance.md) | *Описание* |
| [`GetPropertyHasStandardValues`](./ObjectBase.cs/Методы/GetPropertyHasStandardValues.md) | *Описание* |
| [`GetPropertyReadOnly`](./ObjectBase.cs/Методы/GetPropertyReadOnly.md) | *Описание* |
| [`GetPropertyStandardValues`](./ObjectBase.cs/Методы/GetPropertyStandardValues.md) | *Описание* |
| [`GetPropertyVisibility`](./ObjectBase.cs/Методы/GetPropertyVisibility.md) | *Описание* |
| [`GetX`](./ObjectBase.cs/Методы/GetX.md) | *Описание* |
| [`GetY`](./ObjectBase.cs/Методы/GetY.md) | *Описание* |
| [`InObject`](./ObjectBase.cs/Методы/InObject.md) | *Описание* |
| [`IsObjectInArea`](./ObjectBase.cs/Методы/IsObjectInArea.md) | *Описание* |
| [`IsObjectOnChart`](./ObjectBase.cs/Методы/IsObjectOnChart.md) | *Описание* |
| [`ObjectBase`](./ObjectBase.cs/Методы/ObjectBase.md) | *Описание* |
| [`OnPropertyChanged`](./ObjectBase.cs/Методы/OnPropertyChanged.md) | *Описание* |
| [`Prepare`](./ObjectBase.cs/Методы/Prepare.md) | *Описание* |
| [`SetCanvas`](./ObjectBase.cs/Методы/SetCanvas.md) | *Описание* |
| [`SetDataProvider`](./ObjectBase.cs/Методы/SetDataProvider.md) | *Описание* |
| [`SetSettings`](./ObjectBase.cs/Методы/SetSettings.md) | *Описание* |
| [`ToPoint`](./ObjectBase.cs/Методы/ToPoint.md) | *Описание* |
| [`ToPoints`](./ObjectBase.cs/Методы/ToPoints.md) | *Описание* |
| [`ToString`](./ObjectBase.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Canvas`](./ObjectBase.cs/Свойства/Canvas.md) | *Описание* |
| [`ChartDataType`](./ObjectBase.cs/Свойства/ChartDataType.md) | *Описание* |
| [`ControlPointNum`](./ObjectBase.cs/Свойства/ControlPointNum.md) | *Описание* |
| [`ControlPoints`](./ObjectBase.cs/Свойства/ControlPoints.md) | *Описание* |
| [`ControlPointsList`](./ObjectBase.cs/Свойства/ControlPointsList.md) | *Описание* |
| [`DataProvider`](./ObjectBase.cs/Свойства/DataProvider.md) | *Описание* |
| [`ID`](./ObjectBase.cs/Свойства/ID.md) | *Описание* |
| [`InMove;`](./ObjectBase.cs/Свойства/InMove;.md) | *Описание* |
| [`InSetup;`](./ObjectBase.cs/Свойства/InSetup;.md) | *Описание* |
| [`Lock`](./ObjectBase.cs/Свойства/Lock.md) | *Описание* |
| [`Name`](./ObjectBase.cs/Свойства/Name.md) | *Описание* |
| [`ObjectID`](./ObjectBase.cs/Свойства/ObjectID.md) | *Описание* |
| [`PenWidth`](./ObjectBase.cs/Свойства/PenWidth.md) | *Описание* |
| [`Periods`](./ObjectBase.cs/Свойства/Periods.md) | *Описание* |
| [`Position`](./ObjectBase.cs/Свойства/Position.md) | *Описание* |
| [`Settings`](./ObjectBase.cs/Свойства/Settings.md) | *Описание* |
| [`SnapGrid`](./ObjectBase.cs/Свойства/SnapGrid.md) | *Описание* |
| [`SymbolID`](./ObjectBase.cs/Свойства/SymbolID.md) | *Описание* |
| [`Theme`](./ObjectBase.cs/Свойства/Theme.md) | *Описание* |
| [`Title`](./ObjectBase.cs/Свойства/Title.md) | *Описание* |

# Таблица событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ObjectBase.cs/События/PropertyChanged.md) | *Описание* |





# Методы

## *AddAlert*
Описание

```csharp
protected void AddAlert(ChartAlertSettings settings, string message)
```

<mark style="color:yellow;">`settings`</mark> <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

<mark style="color:yellow;">`message`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *ApplyTheme*
Описание

```csharp
public virtual void ApplyTheme(IChartTheme theme)
```
<mark style="color:yellow;">`theme`</mark> <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  



## *BeginDrag*
Описание

```csharp
public virtual void BeginDrag()
```


## *CheckAlert*
Описание

```csharp
public virtual void CheckAlert(List<IndicatorBase> indicators)
```


## *ControlPointEditing*
Описание

```csharp
public virtual void ControlPointEditing(int index)
```

<mark style="color:yellow;">`index`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *ControlPointsChanged*
Описание

```csharp
public virtual void ControlPointsChanged()
```


## *CopyTemplate*
Описание

```csharp
public virtual void CopyTemplate(ObjectBase objectBase, bool style)
```

<mark style="color:yellow;">`objectBase`</mark> <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *DragObject*
Описание

```csharp
public virtual void DragObject(double dx, double dy)
```
<mark style="color:yellow;">`dx`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:yellow;">`dy`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *Draw*
Описание

```csharp
protected abstract void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
<mark style="color:yellow;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

<mark style="color:yellow;">`List`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  



## *DrawControlPoint*
Описание

```csharp
protected void DrawControlPoint(DxVisualQueue visual, Point point)
```
<mark style="color:yellow;">`point`</mark> <mark style="color:red;">*`Point`*</mark>  
 *Описание*  



## *DrawControlPoints*
Описание

```csharp
public virtual void DrawControlPoints(DxVisualQueue visual)
```
<mark style="color:yellow;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  



## *DrawObject*
Описание

```csharp
public void DrawObject(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
<mark style="color:yellow;">`List`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  



## *ExtraPointChanged*
Описание

```csharp
public virtual void ExtraPointChanged(int index, ObjectPoint op)
```
<mark style="color:yellow;">`index`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`op`</mark> <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  



## *GetAlerts*
Описание

```csharp
public List<ChartAlertInfo> GetAlerts()
```


## *GetControlPoint*
Описание

```csharp
public virtual int GetControlPoint(int x, int y)
```

<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *GetExtraPoint*
Описание

```csharp
public virtual int GetExtraPoint(int x, int y)
```


## *GetMinDist*
Описание

```csharp
protected virtual int GetMinDist(int x, int y)
```

<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *GetMinDistance*
Описание

```csharp
public int GetMinDistance(int x, int y)
```


## *GetPropertyHasStandardValues*
Описание

```csharp
public virtual bool GetPropertyHasStandardValues(string propertyName)
```

<mark style="color:yellow;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *GetPropertyReadOnly*
Описание

```csharp
public virtual bool GetPropertyReadOnly(string propertyName)
```


## *GetPropertyStandardValues*
Описание

```csharp
public virtual IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

<mark style="color:yellow;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *GetPropertyVisibility*
Описание

```csharp
public virtual bool GetPropertyVisibility(string propertyName)
```


## *GetX*
Описание

```csharp
protected double GetX(int i)
```

<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *GetY*
Описание

```csharp
protected double GetY(double d)
```
<mark style="color:yellow;">`d`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *InObject*
Описание

```csharp
protected virtual bool InObject(int x, int y)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *IsObjectInArea*
Описание

```csharp
protected virtual bool IsObjectInArea()
```


## *IsObjectOnChart*
Описание

```csharp
protected virtual bool IsObjectOnChart()
```


## *ObjectBase*
Описание

```csharp
protected ObjectBase()
```


## *OnPropertyChanged*
Описание

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

<mark style="color:yellow;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *Prepare*
Описание

```csharp
protected virtual void Prepare()
```


## *SetCanvas*
Описание

```csharp
public void SetCanvas(IChartCanvas canvas)
```

<mark style="color:yellow;">`canvas`</mark> <mark style="color:red;">*`IChartCanvas`*</mark>  
 *Описание*  



## *SetDataProvider*
Описание

```csharp
public void SetDataProvider(IChartDataProvider dp)
```
<mark style="color:yellow;">`dp`</mark> <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *Описание*  



## *SetSettings*
Описание

```csharp
public void SetSettings(IChartSettings settings)
```
<mark style="color:yellow;">`settings`</mark> <mark style="color:red;">*`IChartSettings`*</mark>  
 *Описание*  



## *ToPoint*
Описание

```csharp
public Point ToPoint(ObjectPoint op)
```
<mark style="color:yellow;">`op`</mark> <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  



## *ToPoints*
Описание

```csharp
protected Point[] ToPoints(ObjectPoint[] ops)
```


## *ToString*
Описание

```csharp
public override string ToString()
```

# Свойства

## *Canvas*
Описание

```csharp
protected IChartCanvas Canvas { get; private set; }
```

## *ChartDataType*
Описание

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

## *ControlPointNum*
Описание

```csharp
public int ControlPointNum { get; }
```

## *ControlPoints*
Описание

```csharp
public ObjectPoint[] ControlPoints { get; set; }
```

## *ControlPointsList*
Описание

```csharp
public ObjectPointInfo[] ControlPointsList { get; }
```

## *DataProvider*
Описание

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```

## *ID*
Описание

```csharp
public string ID { get; }
```

## *InMove;*
Описание

```csharp
public bool InMove; {}
```

## *InSetup;*
Описание

```csharp
public bool InSetup; {}
```

## *Lock*
Описание

```csharp
public bool Lock { get; set; }
```

## *Name*
Описание

```csharp
public string Name { get; }
```

## *ObjectID*
Описание

```csharp
public string ObjectID { get; set; }
```

## *PenWidth*
Описание

```csharp
protected virtual int PenWidth { get; }
```

## *Periods*
Описание

```csharp
public ObjectPeriods Periods { get; set; }
```

## *Position*
Описание

```csharp
public ObjectPosition Position { get; set; }
```

## *Settings*
Описание

```csharp
protected IChartSettings Settings { get; private set; }
```

## *SnapGrid*
Описание

```csharp
public virtual bool SnapGrid { get; }
```

## *SymbolID*
Описание

```csharp
public string SymbolID { get; set; }
```

## *Theme*
Описание

```csharp
protected IChartTheme Theme { get; private set; }
```

## *Title*
Описание

```csharp
public string Title { get; }
```
# <font color="Purple">Событияs</font>

## *PropertyChanged*
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

