
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


===

### Синтаксис
```csharp
public abstract class ObjectBase : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddAlert`](#method-addalert) | *===* |
| [`ApplyTheme`](#method-applytheme) | *===* |
| [`BeginDrag`](#method-begindrag) | *===* |
| [`CheckAlert`](#method-checkalert) | *===* |
| [`ControlPointEditing`](#method-controlpointediting) | *===* |
| [`ControlPointsChanged`](#method-controlpointschanged) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`DragObject`](#method-dragobject) | *===* |
| [`Draw`](#method-draw) | *===* |
| [`DrawControlPoint`](#method-drawcontrolpoint) | *===* |
| [`DrawControlPoints`](#method-drawcontrolpoints) | *===* |
| [`DrawObject`](#method-drawobject) | *===* |
| [`ExtraPointChanged`](#method-extrapointchanged) | *===* |
| [`GetAlerts`](#method-getalerts) | *===* |
| [`GetControlPoint`](#method-getcontrolpoint) | *===* |
| [`GetExtraPoint`](#method-getextrapoint) | *===* |
| [`GetMinDist`](#method-getmindist) | *===* |
| [`GetMinDistance`](#method-getmindistance) | *===* |
| [`GetPropertyHasStandardValues`](#method-getpropertyhasstandardvalues) | *===* |
| [`GetPropertyReadOnly`](#method-getpropertyreadonly) | *===* |
| [`GetPropertyStandardValues`](#method-getpropertystandardvalues) | *===* |
| [`GetPropertyVisibility`](#method-getpropertyvisibility) | *===* |
| [`GetX`](#method-getx) | *===* |
| [`GetY`](#method-gety) | *===* |
| [`InObject`](#method-inobject) | *===* |
| [`IsObjectInArea`](#method-isobjectinarea) | *===* |
| [`IsObjectOnChart`](#method-isobjectonchart) | *===* |
| [`ObjectBase`](#method-objectbase) | *===* |
| [`OnPropertyChanged`](#method-onpropertychanged) | *===* |
| [`Prepare`](#method-prepare) | *===* |
| [`SetCanvas`](#method-setcanvas) | *===* |
| [`SetDataProvider`](#method-setdataprovider) | *===* |
| [`SetSettings`](#method-setsettings) | *===* |
| [`ToPoint`](#method-topoint) | *===* |
| [`ToPoints`](#method-topoints) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Canvas`](#property-canvas) | *===* |
| [`ChartDataType`](#property-chartdatatype) | *===* |
| [`ControlPointNum`](#property-controlpointnum) | *===* |
| [`ControlPoints`](#property-controlpoints) | *===* |
| [`ControlPointsList`](#property-controlpointslist) | *===* |
| [`DataProvider`](#property-dataprovider) | *===* |
| [`ID`](#property-id) | *===* |
| [`InMove;`](#property-inmove;) | *===* |
| [`InSetup;`](#property-insetup;) | *===* |
| [`Lock`](#property-lock) | *===* |
| [`Name`](#property-name) | *===* |
| [`ObjectID`](#property-objectid) | *===* |
| [`PenWidth`](#property-penwidth) | *===* |
| [`Periods`](#property-periods) | *===* |
| [`Position`](#property-position) | *===* |
| [`Settings`](#property-settings) | *===* |
| [`SnapGrid`](#property-snapgrid) | *===* |
| [`SymbolID`](#property-symbolid) | *===* |
| [`Theme`](#property-theme) | *===* |
| [`Title`](#property-title) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *===* |





***  
***  
# Методы

## `AddAlert`<a href="method-addalert" id="method-addalert"></a>
===
```csharp
protected void AddAlert(ChartAlertSettings settings, string message)
```

`settings` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *===*  

`message` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `ApplyTheme`<a href="method-applytheme" id="method-applytheme"></a>
===
```csharp
public virtual void ApplyTheme(IChartTheme theme)
```
`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *===*  


***  

## `BeginDrag`<a href="method-begindrag" id="method-begindrag"></a>
===
```csharp
public virtual void BeginDrag()
```

***  

## `CheckAlert`<a href="method-checkalert" id="method-checkalert"></a>
===
```csharp
public virtual void CheckAlert(List<IndicatorBase> indicators)
```

***  

## `ControlPointEditing`<a href="method-controlpointediting" id="method-controlpointediting"></a>
===
```csharp
public virtual void ControlPointEditing(int index)
```

`index` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `ControlPointsChanged`<a href="method-controlpointschanged" id="method-controlpointschanged"></a>
===
```csharp
public virtual void ControlPointsChanged()
```

***  

## `CopyTemplate`<a href="method-copytemplate" id="method-copytemplate"></a>
===
```csharp
public virtual void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *===*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `DragObject`<a href="method-dragobject" id="method-dragobject"></a>
===
```csharp
public virtual void DragObject(double dx, double dy)
```
`dx` <mark style="color:red;">*`double`*</mark>  
 *===*  

`dy` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `Draw`<a href="method-draw" id="method-draw"></a>
===
```csharp
protected abstract void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *===*  

`List` <mark style="color:red;">*`ref`*</mark>  
 *===*  


***  

## `DrawControlPoint`<a href="method-drawcontrolpoint" id="method-drawcontrolpoint"></a>
===
```csharp
protected void DrawControlPoint(DxVisualQueue visual, Point point)
```
`point` <mark style="color:red;">*`Point`*</mark>  
 *===*  


***  

## `DrawControlPoints`<a href="method-drawcontrolpoints" id="method-drawcontrolpoints"></a>
===
```csharp
public virtual void DrawControlPoints(DxVisualQueue visual)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *===*  


***  

## `DrawObject`<a href="method-drawobject" id="method-drawobject"></a>
===
```csharp
public void DrawObject(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
`List` <mark style="color:red;">*`ref`*</mark>  
 *===*  


***  

## `ExtraPointChanged`<a href="method-extrapointchanged" id="method-extrapointchanged"></a>
===
```csharp
public virtual void ExtraPointChanged(int index, ObjectPoint op)
```
`index` <mark style="color:red;">*`int`*</mark>  
 *===*  

`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *===*  


***  

## `GetAlerts`<a href="method-getalerts" id="method-getalerts"></a>
===
```csharp
public List<ChartAlertInfo> GetAlerts()
```

***  

## `GetControlPoint`<a href="method-getcontrolpoint" id="method-getcontrolpoint"></a>
===
```csharp
public virtual int GetControlPoint(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *===*  

`y` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `GetExtraPoint`<a href="method-getextrapoint" id="method-getextrapoint"></a>
===
```csharp
public virtual int GetExtraPoint(int x, int y)
```

***  

## `GetMinDist`<a href="method-getmindist" id="method-getmindist"></a>
===
```csharp
protected virtual int GetMinDist(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *===*  

`y` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `GetMinDistance`<a href="method-getmindistance" id="method-getmindistance"></a>
===
```csharp
public int GetMinDistance(int x, int y)
```

***  

## `GetPropertyHasStandardValues`<a href="method-getpropertyhasstandardvalues" id="method-getpropertyhasstandardvalues"></a>
===
```csharp
public virtual bool GetPropertyHasStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetPropertyReadOnly`<a href="method-getpropertyreadonly" id="method-getpropertyreadonly"></a>
===
```csharp
public virtual bool GetPropertyReadOnly(string propertyName)
```

***  

## `GetPropertyStandardValues`<a href="method-getpropertystandardvalues" id="method-getpropertystandardvalues"></a>
===
```csharp
public virtual IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetPropertyVisibility`<a href="method-getpropertyvisibility" id="method-getpropertyvisibility"></a>
===
```csharp
public virtual bool GetPropertyVisibility(string propertyName)
```

***  

## `GetX`<a href="method-getx" id="method-getx"></a>
===
```csharp
protected double GetX(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `GetY`<a href="method-gety" id="method-gety"></a>
===
```csharp
protected double GetY(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `InObject`<a href="method-inobject" id="method-inobject"></a>
===
```csharp
protected virtual bool InObject(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *===*  

`y` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `IsObjectInArea`<a href="method-isobjectinarea" id="method-isobjectinarea"></a>
===
```csharp
protected virtual bool IsObjectInArea()
```

***  

## `IsObjectOnChart`<a href="method-isobjectonchart" id="method-isobjectonchart"></a>
===
```csharp
protected virtual bool IsObjectOnChart()
```

***  

## `ObjectBase`<a href="method-objectbase" id="method-objectbase"></a>
===
```csharp
protected ObjectBase()
```

***  

## `OnPropertyChanged`<a href="method-onpropertychanged" id="method-onpropertychanged"></a>
===
```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `Prepare`<a href="method-prepare" id="method-prepare"></a>
===
```csharp
protected virtual void Prepare()
```

***  

## `SetCanvas`<a href="method-setcanvas" id="method-setcanvas"></a>
===
```csharp
public void SetCanvas(IChartCanvas canvas)
```

`canvas` <mark style="color:red;">*`IChartCanvas`*</mark>  
 *===*  


***  

## `SetDataProvider`<a href="method-setdataprovider" id="method-setdataprovider"></a>
===
```csharp
public void SetDataProvider(IChartDataProvider dp)
```
`dp` <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *===*  


***  

## `SetSettings`<a href="method-setsettings" id="method-setsettings"></a>
===
```csharp
public void SetSettings(IChartSettings settings)
```
`settings` <mark style="color:red;">*`IChartSettings`*</mark>  
 *===*  


***  

## `ToPoint`<a href="method-topoint" id="method-topoint"></a>
===
```csharp
public Point ToPoint(ObjectPoint op)
```
`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *===*  


***  

## `ToPoints`<a href="method-topoints" id="method-topoints"></a>
===
```csharp
protected Point[] ToPoints(ObjectPoint[] ops)
```

***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
===
```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Canvas`<a href="property-canvas" id="property-canvas"></a>
===
```csharp
protected IChartCanvas Canvas { get; private set; }
```  
***

## `ChartDataType`<a href="property-chartdatatype" id="property-chartdatatype"></a>
===
```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

## `ControlPointNum`<a href="property-controlpointnum" id="property-controlpointnum"></a>
===
```csharp
public int ControlPointNum { get; }
```  
***

## `ControlPoints`<a href="property-controlpoints" id="property-controlpoints"></a>
===
```csharp
public ObjectPoint[] ControlPoints { get; set; }
```  
***

## `ControlPointsList`<a href="property-controlpointslist" id="property-controlpointslist"></a>
===
```csharp
public ObjectPointInfo[] ControlPointsList { get; }
```  
***

## `DataProvider`<a href="property-dataprovider" id="property-dataprovider"></a>
===
```csharp
protected IChartDataProvider DataProvider { get; private set; }
```  
***

## `ID`<a href="property-id" id="property-id"></a>
===
```csharp
public string ID { get; }
```  
***

## `InMove;`<a href="property-inmove;" id="property-inmove;"></a>
===
```csharp
public bool InMove; {}
```  
***

## `InSetup;`<a href="property-insetup;" id="property-insetup;"></a>
===
```csharp
public bool InSetup; {}
```  
***

## `Lock`<a href="property-lock" id="property-lock"></a>
===
```csharp
public bool Lock { get; set; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
===
```csharp
public string Name { get; }
```  
***

## `ObjectID`<a href="property-objectid" id="property-objectid"></a>
===
```csharp
public string ObjectID { get; set; }
```  
***

## `PenWidth`<a href="property-penwidth" id="property-penwidth"></a>
===
```csharp
protected virtual int PenWidth { get; }
```  
***

## `Periods`<a href="property-periods" id="property-periods"></a>
===
```csharp
public ObjectPeriods Periods { get; set; }
```  
***

## `Position`<a href="property-position" id="property-position"></a>
===
```csharp
public ObjectPosition Position { get; set; }
```  
***

## `Settings`<a href="property-settings" id="property-settings"></a>
===
```csharp
protected IChartSettings Settings { get; private set; }
```  
***

## `SnapGrid`<a href="property-snapgrid" id="property-snapgrid"></a>
===
```csharp
public virtual bool SnapGrid { get; }
```  
***

## `SymbolID`<a href="property-symbolid" id="property-symbolid"></a>
===
```csharp
public string SymbolID { get; set; }
```  
***

## `Theme`<a href="property-theme" id="property-theme"></a>
===
```csharp
protected IChartTheme Theme { get; private set; }
```  
***

## `Title`<a href="property-title" id="property-title"></a>
===
```csharp
public string Title { get; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

