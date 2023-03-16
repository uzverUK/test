
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public abstract class ObjectBase : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddAlert`](#method-addalert) | *Описание* |
| [`ApplyTheme`](#method-applytheme) | *Описание* |
| [`BeginDrag`](#method-begindrag) | *Описание* |
| [`CheckAlert`](#method-checkalert) | *Описание* |
| [`ControlPointEditing`](#method-controlpointediting) | *Описание* |
| [`ControlPointsChanged`](#method-controlpointschanged) | *Описание* |
| [`CopyTemplate`](#method-copytemplate) | *Описание* |
| [`DragObject`](#method-dragobject) | *Описание* |
| [`Draw`](#method-draw) | *Описание* |
| [`DrawControlPoint`](#method-drawcontrolpoint) | *Описание* |
| [`DrawControlPoints`](#method-drawcontrolpoints) | *Описание* |
| [`DrawObject`](#method-drawobject) | *Описание* |
| [`ExtraPointChanged`](#method-extrapointchanged) | *Описание* |
| [`GetAlerts`](#method-getalerts) | *Описание* |
| [`GetControlPoint`](#method-getcontrolpoint) | *Описание* |
| [`GetExtraPoint`](#method-getextrapoint) | *Описание* |
| [`GetMinDist`](#method-getmindist) | *Описание* |
| [`GetMinDistance`](#method-getmindistance) | *Описание* |
| [`GetPropertyHasStandardValues`](#method-getpropertyhasstandardvalues) | *Описание* |
| [`GetPropertyReadOnly`](#method-getpropertyreadonly) | *Описание* |
| [`GetPropertyStandardValues`](#method-getpropertystandardvalues) | *Описание* |
| [`GetPropertyVisibility`](#method-getpropertyvisibility) | *Описание* |
| [`GetX`](#method-getx) | *Описание* |
| [`GetY`](#method-gety) | *Описание* |
| [`InObject`](#method-inobject) | *Описание* |
| [`IsObjectInArea`](#method-isobjectinarea) | *Описание* |
| [`IsObjectOnChart`](#method-isobjectonchart) | *Описание* |
| [`ObjectBase`](#method-objectbase) | *Описание* |
| [`OnPropertyChanged`](#method-onpropertychanged) | *Описание* |
| [`Prepare`](#method-prepare) | *Описание* |
| [`SetCanvas`](#method-setcanvas) | *Описание* |
| [`SetDataProvider`](#method-setdataprovider) | *Описание* |
| [`SetSettings`](#method-setsettings) | *Описание* |
| [`ToPoint`](#method-topoint) | *Описание* |
| [`ToPoints`](#method-topoints) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Canvas`](#property-canvas) | *Описание* |
| [`ChartDataType`](#property-chartdatatype) | *Описание* |
| [`ControlPointNum`](#property-controlpointnum) | *Описание* |
| [`ControlPoints`](#property-controlpoints) | *Описание* |
| [`ControlPointsList`](#property-controlpointslist) | *Описание* |
| [`DataProvider`](#property-dataprovider) | *Описание* |
| [`ID`](#property-id) | *Описание* |
| [`InMove;`](#property-inmove;) | *Описание* |
| [`InSetup;`](#property-insetup;) | *Описание* |
| [`Lock`](#property-lock) | *Описание* |
| [`Name`](#property-name) | *Описание* |
| [`ObjectID`](#property-objectid) | *Описание* |
| [`PenWidth`](#property-penwidth) | *Описание* |
| [`Periods`](#property-periods) | *Описание* |
| [`Position`](#property-position) | *Описание* |
| [`Settings`](#property-settings) | *Описание* |
| [`SnapGrid`](#property-snapgrid) | *Описание* |
| [`SymbolID`](#property-symbolid) | *Описание* |
| [`Theme`](#property-theme) | *Описание* |
| [`Title`](#property-title) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *Описание* |





***  
***  
# Методы

## `AddAlert`<a href="method-addalert" id="method-addalert"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void AddAlert(ChartAlertSettings settings, string message)
```

`settings` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

`message` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ApplyTheme`<a href="method-applytheme" id="method-applytheme"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ApplyTheme(IChartTheme theme)
```
`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `BeginDrag`<a href="method-begindrag" id="method-begindrag"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void BeginDrag()
```

***  

## `CheckAlert`<a href="method-checkalert" id="method-checkalert"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CheckAlert(List<IndicatorBase> indicators)
```

***  

## `ControlPointEditing`<a href="method-controlpointediting" id="method-controlpointediting"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ControlPointEditing(int index)
```

`index` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `ControlPointsChanged`<a href="method-controlpointschanged" id="method-controlpointschanged"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ControlPointsChanged()
```

***  

## `CopyTemplate`<a href="method-copytemplate" id="method-copytemplate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `DragObject`<a href="method-dragobject" id="method-dragobject"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void DragObject(double dx, double dy)
```
`dx` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`dy` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `Draw`<a href="method-draw" id="method-draw"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `DrawControlPoint`<a href="method-drawcontrolpoint" id="method-drawcontrolpoint"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void DrawControlPoint(DxVisualQueue visual, Point point)
```
`point` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  


***  

## `DrawControlPoints`<a href="method-drawcontrolpoints" id="method-drawcontrolpoints"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void DrawControlPoints(DxVisualQueue visual)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `DrawObject`<a href="method-drawobject" id="method-drawobject"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawObject(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `ExtraPointChanged`<a href="method-extrapointchanged" id="method-extrapointchanged"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ExtraPointChanged(int index, ObjectPoint op)
```
`index` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***  

## `GetAlerts`<a href="method-getalerts" id="method-getalerts"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartAlertInfo> GetAlerts()
```

***  

## `GetControlPoint`<a href="method-getcontrolpoint" id="method-getcontrolpoint"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual int GetControlPoint(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetExtraPoint`<a href="method-getextrapoint" id="method-getextrapoint"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual int GetExtraPoint(int x, int y)
```

***  

## `GetMinDist`<a href="method-getmindist" id="method-getmindist"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual int GetMinDist(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetMinDistance`<a href="method-getmindistance" id="method-getmindistance"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int GetMinDistance(int x, int y)
```

***  

## `GetPropertyHasStandardValues`<a href="method-getpropertyhasstandardvalues" id="method-getpropertyhasstandardvalues"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyHasStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyReadOnly`<a href="method-getpropertyreadonly" id="method-getpropertyreadonly"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyReadOnly(string propertyName)
```

***  

## `GetPropertyStandardValues`<a href="method-getpropertystandardvalues" id="method-getpropertystandardvalues"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyVisibility`<a href="method-getpropertyvisibility" id="method-getpropertyvisibility"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyVisibility(string propertyName)
```

***  

## `GetX`<a href="method-getx" id="method-getx"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetX(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetY`<a href="method-gety" id="method-gety"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetY(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `InObject`<a href="method-inobject" id="method-inobject"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool InObject(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `IsObjectInArea`<a href="method-isobjectinarea" id="method-isobjectinarea"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool IsObjectInArea()
```

***  

## `IsObjectOnChart`<a href="method-isobjectonchart" id="method-isobjectonchart"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool IsObjectOnChart()
```

***  

## `ObjectBase`<a href="method-objectbase" id="method-objectbase"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected ObjectBase()
```

***  

## `OnPropertyChanged`<a href="method-onpropertychanged" id="method-onpropertychanged"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Prepare`<a href="method-prepare" id="method-prepare"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void Prepare()
```

***  

## `SetCanvas`<a href="method-setcanvas" id="method-setcanvas"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetCanvas(IChartCanvas canvas)
```

`canvas` <mark style="color:red;">*`IChartCanvas`*</mark>  
 *Описание*  


***  

## `SetDataProvider`<a href="method-setdataprovider" id="method-setdataprovider"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetDataProvider(IChartDataProvider dp)
```
`dp` <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *Описание*  


***  

## `SetSettings`<a href="method-setsettings" id="method-setsettings"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetSettings(IChartSettings settings)
```
`settings` <mark style="color:red;">*`IChartSettings`*</mark>  
 *Описание*  


***  

## `ToPoint`<a href="method-topoint" id="method-topoint"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Point ToPoint(ObjectPoint op)
```
`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***  

## `ToPoints`<a href="method-topoints" id="method-topoints"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] ToPoints(ObjectPoint[] ops)
```

***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Canvas`<a href="property-canvas" id="property-canvas"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartCanvas Canvas { get; private set; }
```  
***

## `ChartDataType`<a href="property-chartdatatype" id="property-chartdatatype"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

## `ControlPointNum`<a href="property-controlpointnum" id="property-controlpointnum"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int ControlPointNum { get; }
```  
***

## `ControlPoints`<a href="property-controlpoints" id="property-controlpoints"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPoint[] ControlPoints { get; set; }
```  
***

## `ControlPointsList`<a href="property-controlpointslist" id="property-controlpointslist"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPointInfo[] ControlPointsList { get; }
```  
***

## `DataProvider`<a href="property-dataprovider" id="property-dataprovider"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```  
***

## `ID`<a href="property-id" id="property-id"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `InMove;`<a href="property-inmove;" id="property-inmove;"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool InMove; {}
```  
***

## `InSetup;`<a href="property-insetup;" id="property-insetup;"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool InSetup; {}
```  
***

## `Lock`<a href="property-lock" id="property-lock"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Lock { get; set; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `ObjectID`<a href="property-objectid" id="property-objectid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ObjectID { get; set; }
```  
***

## `PenWidth`<a href="property-penwidth" id="property-penwidth"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual int PenWidth { get; }
```  
***

## `Periods`<a href="property-periods" id="property-periods"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPeriods Periods { get; set; }
```  
***

## `Position`<a href="property-position" id="property-position"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPosition Position { get; set; }
```  
***

## `Settings`<a href="property-settings" id="property-settings"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartSettings Settings { get; private set; }
```  
***

## `SnapGrid`<a href="property-snapgrid" id="property-snapgrid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool SnapGrid { get; }
```  
***

## `SymbolID`<a href="property-symbolid" id="property-symbolid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SymbolID { get; set; }
```  
***

## `Theme`<a href="property-theme" id="property-theme"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartTheme Theme { get; private set; }
```  
***

## `Title`<a href="property-title" id="property-title"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Title { get; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

