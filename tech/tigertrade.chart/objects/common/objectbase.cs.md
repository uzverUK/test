# ObjectBase

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[Common](./)

\===

#### Синтаксис

```csharp
public abstract class ObjectBase : INotifyPropertyChanged, IDynamicProperty
```

## Список методов

| Название                                                                               | Описание |
| -------------------------------------------------------------------------------------- | -------- |
| [`AddAlert`](objectbase.cs.md#method-addalert)                                         | _===_    |
| [`ApplyTheme`](objectbase.cs.md#method-applytheme)                                     | _===_    |
| [`BeginDrag`](objectbase.cs.md#method-begindrag)                                       | _===_    |
| [`CheckAlert`](objectbase.cs.md#method-checkalert)                                     | _===_    |
| [`ControlPointEditing`](objectbase.cs.md#method-controlpointediting)                   | _===_    |
| [`ControlPointsChanged`](objectbase.cs.md#method-controlpointschanged)                 | _===_    |
| [`CopyTemplate`](objectbase.cs.md#method-copytemplate)                                 | _===_    |
| [`DragObject`](objectbase.cs.md#method-dragobject)                                     | _===_    |
| [`Draw`](objectbase.cs.md#method-draw)                                                 | _===_    |
| [`DrawControlPoint`](objectbase.cs.md#method-drawcontrolpoint)                         | _===_    |
| [`DrawControlPoints`](objectbase.cs.md#method-drawcontrolpoints)                       | _===_    |
| [`DrawObject`](objectbase.cs.md#method-drawobject)                                     | _===_    |
| [`ExtraPointChanged`](objectbase.cs.md#method-extrapointchanged)                       | _===_    |
| [`GetAlerts`](objectbase.cs.md#method-getalerts)                                       | _===_    |
| [`GetControlPoint`](objectbase.cs.md#method-getcontrolpoint)                           | _===_    |
| [`GetExtraPoint`](objectbase.cs.md#method-getextrapoint)                               | _===_    |
| [`GetMinDist`](objectbase.cs.md#method-getmindist)                                     | _===_    |
| [`GetMinDistance`](objectbase.cs.md#method-getmindistance)                             | _===_    |
| [`GetPropertyHasStandardValues`](objectbase.cs.md#method-getpropertyhasstandardvalues) | _===_    |
| [`GetPropertyReadOnly`](objectbase.cs.md#method-getpropertyreadonly)                   | _===_    |
| [`GetPropertyStandardValues`](objectbase.cs.md#method-getpropertystandardvalues)       | _===_    |
| [`GetPropertyVisibility`](objectbase.cs.md#method-getpropertyvisibility)               | _===_    |
| [`GetX`](objectbase.cs.md#method-getx)                                                 | _===_    |
| [`GetY`](objectbase.cs.md#method-gety)                                                 | _===_    |
| [`InObject`](objectbase.cs.md#method-inobject)                                         | _===_    |
| [`IsObjectInArea`](objectbase.cs.md#method-isobjectinarea)                             | _===_    |
| [`IsObjectOnChart`](objectbase.cs.md#method-isobjectonchart)                           | _===_    |
| [`ObjectBase`](objectbase.cs.md#method-objectbase)                                     | _===_    |
| [`OnPropertyChanged`](objectbase.cs.md#method-onpropertychanged)                       | _===_    |
| [`Prepare`](objectbase.cs.md#method-prepare)                                           | _===_    |
| [`SetCanvas`](objectbase.cs.md#method-setcanvas)                                       | _===_    |
| [`SetDataProvider`](objectbase.cs.md#method-setdataprovider)                           | _===_    |
| [`SetSettings`](objectbase.cs.md#method-setsettings)                                   | _===_    |
| [`ToPoint`](objectbase.cs.md#method-topoint)                                           | _===_    |
| [`ToPoints`](objectbase.cs.md#method-topoints)                                         | _===_    |
| [`ToString`](objectbase.cs.md#method-tostring)                                         | _===_    |

## Список свойств

| Название                                                           | Описание |
| ------------------------------------------------------------------ | -------- |
| [`Canvas`](objectbase.cs.md#property-canvas)                       | _===_    |
| [`ChartDataType`](objectbase.cs.md#property-chartdatatype)         | _===_    |
| [`ControlPointNum`](objectbase.cs.md#property-controlpointnum)     | _===_    |
| [`ControlPoints`](objectbase.cs.md#property-controlpoints)         | _===_    |
| [`ControlPointsList`](objectbase.cs.md#property-controlpointslist) | _===_    |
| [`DataProvider`](objectbase.cs.md#property-dataprovider)           | _===_    |
| [`ID`](objectbase.cs.md#property-id)                               | _===_    |
| [`InMove;`](objectbase.cs.md#property-inmove;)                     | _===_    |
| [`InSetup;`](objectbase.cs.md#property-insetup;)                   | _===_    |
| [`Lock`](objectbase.cs.md#property-lock)                           | _===_    |
| [`Name`](objectbase.cs.md#property-name)                           | _===_    |
| [`ObjectID`](objectbase.cs.md#property-objectid)                   | _===_    |
| [`PenWidth`](objectbase.cs.md#property-penwidth)                   | _===_    |
| [`Periods`](objectbase.cs.md#property-periods)                     | _===_    |
| [`Position`](objectbase.cs.md#property-position)                   | _===_    |
| [`Settings`](objectbase.cs.md#property-settings)                   | _===_    |
| [`SnapGrid`](objectbase.cs.md#property-snapgrid)                   | _===_    |
| [`SymbolID`](objectbase.cs.md#property-symbolid)                   | _===_    |
| [`Theme`](objectbase.cs.md#property-theme)                         | _===_    |
| [`Title`](objectbase.cs.md#property-title)                         | _===_    |

## Список событий

| Название                                                    | Описание |
| ----------------------------------------------------------- | -------- |
| [`PropertyChanged`](objectbase.cs.md#event-propertychanged) | _===_    |

***

***

## Методы

### `AddAlert` <a href="#method-addalert" id="method-addalert"></a>

\===

```csharp
protected void AddAlert(ChartAlertSettings settings, string message)
```

`settings` _<mark style="color:red;">`ChartAlertSettings`</mark>_\
_===_

`message` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `ApplyTheme` <a href="#method-applytheme" id="method-applytheme"></a>

\===

```csharp
public virtual void ApplyTheme(IChartTheme theme)
```

`theme` _<mark style="color:red;">`IChartTheme`</mark>_\
_===_

***

### `BeginDrag` <a href="#method-begindrag" id="method-begindrag"></a>

\===

```csharp
public virtual void BeginDrag()
```

***

### `CheckAlert` <a href="#method-checkalert" id="method-checkalert"></a>

\===

```csharp
public virtual void CheckAlert(List<IndicatorBase> indicators)
```

***

### `ControlPointEditing` <a href="#method-controlpointediting" id="method-controlpointediting"></a>

\===

```csharp
public virtual void ControlPointEditing(int index)
```

`index` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `ControlPointsChanged` <a href="#method-controlpointschanged" id="method-controlpointschanged"></a>

\===

```csharp
public virtual void ControlPointsChanged()
```

***

### `CopyTemplate` <a href="#method-copytemplate" id="method-copytemplate"></a>

\===

```csharp
public virtual void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` _<mark style="color:red;">`ObjectBase`</mark>_\
_===_

`style` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `DragObject` <a href="#method-dragobject" id="method-dragobject"></a>

\===

```csharp
public virtual void DragObject(double dx, double dy)
```

`dx` _<mark style="color:red;">`double`</mark>_\
_===_

`dy` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `Draw` <a href="#method-draw" id="method-draw"></a>

\===

```csharp
protected abstract void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```

`visual` _<mark style="color:red;">`DxVisualQueue`</mark>_\
_===_

`List` _<mark style="color:red;">`ref`</mark>_\
_===_

***

### `DrawControlPoint` <a href="#method-drawcontrolpoint" id="method-drawcontrolpoint"></a>

\===

```csharp
protected void DrawControlPoint(DxVisualQueue visual, Point point)
```

`point` _<mark style="color:red;">`Point`</mark>_\
_===_

***

### `DrawControlPoints` <a href="#method-drawcontrolpoints" id="method-drawcontrolpoints"></a>

\===

```csharp
public virtual void DrawControlPoints(DxVisualQueue visual)
```

`visual` _<mark style="color:red;">`DxVisualQueue`</mark>_\
_===_

***

### `DrawObject` <a href="#method-drawobject" id="method-drawobject"></a>

\===

```csharp
public void DrawObject(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```

`List` _<mark style="color:red;">`ref`</mark>_\
_===_

***

### `ExtraPointChanged` <a href="#method-extrapointchanged" id="method-extrapointchanged"></a>

\===

```csharp
public virtual void ExtraPointChanged(int index, ObjectPoint op)
```

`index` _<mark style="color:red;">`int`</mark>_\
_===_

`op` _<mark style="color:red;">`ObjectPoint`</mark>_\
_===_

***

### `GetAlerts` <a href="#method-getalerts" id="method-getalerts"></a>

\===

```csharp
public List<ChartAlertInfo> GetAlerts()
```

***

### `GetControlPoint` <a href="#method-getcontrolpoint" id="method-getcontrolpoint"></a>

\===

```csharp
public virtual int GetControlPoint(int x, int y)
```

`x` _<mark style="color:red;">`int`</mark>_\
_===_

`y` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `GetExtraPoint` <a href="#method-getextrapoint" id="method-getextrapoint"></a>

\===

```csharp
public virtual int GetExtraPoint(int x, int y)
```

***

### `GetMinDist` <a href="#method-getmindist" id="method-getmindist"></a>

\===

```csharp
protected virtual int GetMinDist(int x, int y)
```

`x` _<mark style="color:red;">`int`</mark>_\
_===_

`y` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `GetMinDistance` <a href="#method-getmindistance" id="method-getmindistance"></a>

\===

```csharp
public int GetMinDistance(int x, int y)
```

***

### `GetPropertyHasStandardValues` <a href="#method-getpropertyhasstandardvalues" id="method-getpropertyhasstandardvalues"></a>

\===

```csharp
public virtual bool GetPropertyHasStandardValues(string propertyName)
```

`propertyName` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetPropertyReadOnly` <a href="#method-getpropertyreadonly" id="method-getpropertyreadonly"></a>

\===

```csharp
public virtual bool GetPropertyReadOnly(string propertyName)
```

***

### `GetPropertyStandardValues` <a href="#method-getpropertystandardvalues" id="method-getpropertystandardvalues"></a>

\===

```csharp
public virtual IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetPropertyVisibility` <a href="#method-getpropertyvisibility" id="method-getpropertyvisibility"></a>

\===

```csharp
public virtual bool GetPropertyVisibility(string propertyName)
```

***

### `GetX` <a href="#method-getx" id="method-getx"></a>

\===

```csharp
protected double GetX(int i)
```

`i` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `GetY` <a href="#method-gety" id="method-gety"></a>

\===

```csharp
protected double GetY(double d)
```

`d` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `InObject` <a href="#method-inobject" id="method-inobject"></a>

\===

```csharp
protected virtual bool InObject(int x, int y)
```

`x` _<mark style="color:red;">`int`</mark>_\
_===_

`y` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `IsObjectInArea` <a href="#method-isobjectinarea" id="method-isobjectinarea"></a>

\===

```csharp
protected virtual bool IsObjectInArea()
```

***

### `IsObjectOnChart` <a href="#method-isobjectonchart" id="method-isobjectonchart"></a>

\===

```csharp
protected virtual bool IsObjectOnChart()
```

***

### `ObjectBase` <a href="#method-objectbase" id="method-objectbase"></a>

\===

```csharp
protected ObjectBase()
```

***

### `OnPropertyChanged` <a href="#method-onpropertychanged" id="method-onpropertychanged"></a>

\===

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `Prepare` <a href="#method-prepare" id="method-prepare"></a>

\===

```csharp
protected virtual void Prepare()
```

***

### `SetCanvas` <a href="#method-setcanvas" id="method-setcanvas"></a>

\===

```csharp
public void SetCanvas(IChartCanvas canvas)
```

`canvas` _<mark style="color:red;">`IChartCanvas`</mark>_\
_===_

***

### `SetDataProvider` <a href="#method-setdataprovider" id="method-setdataprovider"></a>

\===

```csharp
public void SetDataProvider(IChartDataProvider dp)
```

`dp` _<mark style="color:red;">`IChartDataProvider`</mark>_\
_===_

***

### `SetSettings` <a href="#method-setsettings" id="method-setsettings"></a>

\===

```csharp
public void SetSettings(IChartSettings settings)
```

`settings` _<mark style="color:red;">`IChartSettings`</mark>_\
_===_

***

### `ToPoint` <a href="#method-topoint" id="method-topoint"></a>

\===

```csharp
public Point ToPoint(ObjectPoint op)
```

`op` _<mark style="color:red;">`ObjectPoint`</mark>_\
_===_

***

### `ToPoints` <a href="#method-topoints" id="method-topoints"></a>

\===

```csharp
protected Point[] ToPoints(ObjectPoint[] ops)
```

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

***

***

***

## Свойства

### `Canvas` <a href="#property-canvas" id="property-canvas"></a>

\===

```csharp
protected IChartCanvas Canvas { get; private set; }
```

***

### `ChartDataType` <a href="#property-chartdatatype" id="property-chartdatatype"></a>

\===

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***

### `ControlPointNum` <a href="#property-controlpointnum" id="property-controlpointnum"></a>

\===

```csharp
public int ControlPointNum { get; }
```

***

### `ControlPoints` <a href="#property-controlpoints" id="property-controlpoints"></a>

\===

```csharp
public ObjectPoint[] ControlPoints { get; set; }
```

***

### `ControlPointsList` <a href="#property-controlpointslist" id="property-controlpointslist"></a>

\===

```csharp
public ObjectPointInfo[] ControlPointsList { get; }
```

***

### `DataProvider` <a href="#property-dataprovider" id="property-dataprovider"></a>

\===

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```

***

### `ID` <a href="#property-id" id="property-id"></a>

\===

```csharp
public string ID { get; }
```

***

### `InMove;` <a href="#property-inmove" id="property-inmove"></a>

\===

```csharp
public bool InMove; {}
```

***

### `InSetup;` <a href="#property-insetup" id="property-insetup"></a>

\===

```csharp
public bool InSetup; {}
```

***

### `Lock` <a href="#property-lock" id="property-lock"></a>

\===

```csharp
public bool Lock { get; set; }
```

***

### `Name` <a href="#property-name" id="property-name"></a>

\===

```csharp
public string Name { get; }
```

***

### `ObjectID` <a href="#property-objectid" id="property-objectid"></a>

\===

```csharp
public string ObjectID { get; set; }
```

***

### `PenWidth` <a href="#property-penwidth" id="property-penwidth"></a>

\===

```csharp
protected virtual int PenWidth { get; }
```

***

### `Periods` <a href="#property-periods" id="property-periods"></a>

\===

```csharp
public ObjectPeriods Periods { get; set; }
```

***

### `Position` <a href="#property-position" id="property-position"></a>

\===

```csharp
public ObjectPosition Position { get; set; }
```

***

### `Settings` <a href="#property-settings" id="property-settings"></a>

\===

```csharp
protected IChartSettings Settings { get; private set; }
```

***

### `SnapGrid` <a href="#property-snapgrid" id="property-snapgrid"></a>

\===

```csharp
public virtual bool SnapGrid { get; }
```

***

### `SymbolID` <a href="#property-symbolid" id="property-symbolid"></a>

\===

```csharp
public string SymbolID { get; set; }
```

***

### `Theme` <a href="#property-theme" id="property-theme"></a>

\===

```csharp
protected IChartTheme Theme { get; private set; }
```

***

### `Title` <a href="#property-title" id="property-title"></a>

\===

```csharp
public string Title { get; }
```

***

***

***

## События

### `PropertyChanged` <a href="#event-propertychanged" id="event-propertychanged"></a>

\===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```
