
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


===

### Синтаксис
```csharp
public abstract class IndicatorBase : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddAlert`](#method-addalert) | *===* |
| [`ApplyColors`](#method-applycolors) | *===* |
| [`CheckNeedRedraw`](#method-checkneedredraw) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`Execute`](#method-execute) | *===* |
| [`GetAlerts`](#method-getalerts) | *===* |
| [`GetDistance`](#method-getdistance) | *===* |
| [`GetLabels`](#method-getlabels) | *===* |
| [`GetMinMax`](#method-getminmax) | *===* |
| [`GetPoints`](#method-getpoints) | *===* |
| [`GetPropertyHasStandardValues`](#method-getpropertyhasstandardvalues) | *===* |
| [`GetPropertyReadOnly`](#method-getpropertyreadonly) | *===* |
| [`GetPropertyStandardValues`](#method-getpropertystandardvalues) | *===* |
| [`GetPropertyVisibility`](#method-getpropertyvisibility) | *===* |
| [`GetTitle`](#method-gettitle) | *===* |
| [`GetValues`](#method-getvalues) | *===* |
| [`GetX`](#method-getx) | *===* |
| [`GetY`](#method-gety) | *===* |
| [`IndicatorBase`](#method-indicatorbase) | *===* |
| [`OnPropertyChanged`](#method-onpropertychanged) | *===* |
| [`PropChanged`](#method-propchanged) | *===* |
| [`Render`](#method-render) | *===* |
| [`Run`](#method-run) | *===* |
| [`SetSettingsParam`](#method-setsettingsparam) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Calculation`](#property-calculation) | *===* |
| [`Canvas`](#property-canvas) | *===* |
| [`ChartDataType`](#property-chartdatatype) | *===* |
| [`ClearData`](#property-cleardata) | *===* |
| [`DataProvider`](#property-dataprovider) | *===* |
| [`DefaultCalculation`](#property-defaultcalculation) | *===* |
| [`DisableRender`](#property-disablerender) | *===* |
| [`Helper`](#property-helper) | *===* |
| [`ID`](#property-id) | *===* |
| [`IntegerValues`](#property-integervalues) | *===* |
| [`IsStock`](#property-isstock) | *===* |
| [`Levels`](#property-levels) | *===* |
| [`Name`](#property-name) | *===* |
| [`Panel`](#property-panel) | *===* |
| [`Panels`](#property-panels) | *===* |
| [`Series`](#property-series) | *===* |
| [`SettingsLongKey`](#property-settingslongkey) | *===* |
| [`SettingsShortKey`](#property-settingsshortkey) | *===* |
| [`ShowIndicator`](#property-showindicator) | *===* |
| [`ShowIndicatorLabels`](#property-showindicatorlabels) | *===* |
| [`ShowIndicatorLabelsParam`](#property-showindicatorlabelsparam) | *===* |
| [`ShowIndicatorParam`](#property-showindicatorparam) | *===* |
| [`ShowIndicatorTitle`](#property-showindicatortitle) | *===* |
| [`ShowIndicatorTitleParam`](#property-showindicatortitleparam) | *===* |
| [`ShowIndicatorValues`](#property-showindicatorvalues) | *===* |
| [`ShowIndicatorValuesParam`](#property-showindicatorvaluesparam) | *===* |
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

## `ApplyColors`<a href="method-applycolors" id="method-applycolors"></a>
===
```csharp
public virtual void ApplyColors(IChartTheme palette)
```
`palette` <mark style="color:red;">*`IChartTheme`*</mark>  
 *===*  


***  

## `CheckNeedRedraw`<a href="method-checkneedredraw" id="method-checkneedredraw"></a>
===
```csharp
public virtual bool CheckNeedRedraw()
```

***  

## `CopyTemplate`<a href="method-copytemplate" id="method-copytemplate"></a>
===
```csharp
public virtual void CopyTemplate(IndicatorBase indicator, bool style)
```

`indicator` <mark style="color:red;">*`IndicatorBase`*</mark>  
 *===*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `Execute`<a href="method-execute" id="method-execute"></a>
===
```csharp
protected abstract void Execute()
```

***  

## `GetAlerts`<a href="method-getalerts" id="method-getalerts"></a>
===
```csharp
public List<ChartAlertInfo> GetAlerts()
```

***  

## `GetDistance`<a href="method-getdistance" id="method-getdistance"></a>
===
```csharp
public virtual double GetDistance(double x, double y)
```

`x` <mark style="color:red;">*`double`*</mark>  
 *===*  

`y` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `GetLabels`<a href="method-getlabels" id="method-getlabels"></a>
===
```csharp
public virtual void GetLabels(ref List<IndicatorLabelInfo> labels)
```
`List` <mark style="color:red;">*`ref`*</mark>  
 *===*  


***  

## `GetMinMax`<a href="method-getminmax" id="method-getminmax"></a>
===
```csharp
public virtual bool GetMinMax(out double min, out double max)
```
`double` <mark style="color:red;">*`out`*</mark>  
 *===*  

`double` <mark style="color:red;">*`out`*</mark>  
 *===*  


***  

## `GetPoints`<a href="method-getpoints" id="method-getpoints"></a>
===
```csharp
protected Point[] GetPoints(IndicatorSeriesData seriesData, string name = null)
```
`seriesData` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *===*  

`name` <mark style="color:red;">*`string`*</mark>  
 *===*  


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

## `GetTitle`<a href="method-gettitle" id="method-gettitle"></a>
===
```csharp
public virtual IndicatorTitleInfo GetTitle()
```

`IndicatorTitleInfo` <mark style="color:red;">*`new`*</mark>  
 *===*  


***  

## `GetValues`<a href="method-getvalues" id="method-getvalues"></a>
===
```csharp
public virtual List<IndicatorValueInfo> GetValues(int cursorPos)
```
`cursorPos` <mark style="color:red;">*`int`*</mark>  
 *===*  


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

## `GetY`<a href="method-gety" id="method-gety"></a>
===
```csharp
protected double GetY(double d)
protected double GetY(Decimal d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *===*  

`d` <mark style="color:red;">*`Decimal`*</mark>  
 *===*  


***  

## `IndicatorBase`<a href="method-indicatorbase" id="method-indicatorbase"></a>
===
```csharp
protected IndicatorBase()
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

## `PropChanged`<a href="method-propchanged" id="method-propchanged"></a>
===
```csharp
public void PropChanged()
```

***  

## `Render`<a href="method-render" id="method-render"></a>
===
```csharp
public virtual void Render(DxVisualQueue visual)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *===*  


***  

## `Run`<a href="method-run" id="method-run"></a>
===
```csharp
public void Run(IChartDataProvider dp, string longKey, string shortKey, string revision)
```
`dp` <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *===*  

`longKey` <mark style="color:red;">*`string`*</mark>  
 *===*  

`shortKey` <mark style="color:red;">*`string`*</mark>  
 *===*  

`revision` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `SetSettingsParam`<a href="method-setsettingsparam" id="method-setsettingsparam"></a>
===
```csharp
public virtual void SetSettingsParam(string name, object param)
```
`name` <mark style="color:red;">*`string`*</mark>  
 *===*  

`param` <mark style="color:red;">*`object`*</mark>  
 *===*  


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

## `Calculation`<a href="property-calculation" id="property-calculation"></a>
===
```csharp
public virtual IndicatorCalculation Calculation { get; set; }
```  
***

## `Canvas`<a href="property-canvas" id="property-canvas"></a>
===
```csharp
public IChartCanvas Canvas { get; set; }
```  
***

## `ChartDataType`<a href="property-chartdatatype" id="property-chartdatatype"></a>
===
```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

## `ClearData`<a href="property-cleardata" id="property-cleardata"></a>
===
```csharp
protected bool ClearData { get; private set; }
```  
***

## `DataProvider`<a href="property-dataprovider" id="property-dataprovider"></a>
===
```csharp
protected IChartDataProvider DataProvider { get; private set; }
```  
***

## `DefaultCalculation`<a href="property-defaultcalculation" id="property-defaultcalculation"></a>
===
```csharp
public virtual IndicatorCalculation DefaultCalculation { get; }
```  
***

## `DisableRender`<a href="property-disablerender" id="property-disablerender"></a>
===
```csharp
public bool DisableRender { get; protected set; }
```  
***

## `Helper`<a href="property-helper" id="property-helper"></a>
===
```csharp
protected IndicatorsHelper Helper { get; private set; }
```  
***

## `ID`<a href="property-id" id="property-id"></a>
===
```csharp
public string ID { get; }
```  
***

## `IntegerValues`<a href="property-integervalues" id="property-integervalues"></a>
===
```csharp
public virtual bool IntegerValues { get; }
```  
***

## `IsStock`<a href="property-isstock" id="property-isstock"></a>
===
```csharp
public virtual bool IsStock { get; }
```  
***

## `Levels`<a href="property-levels" id="property-levels"></a>
===
```csharp
public List<ChartLevel> Levels { get; set; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
===
```csharp
public string Name { get; }
```  
***

## `Panel`<a href="property-panel" id="property-panel"></a>
===
```csharp
public string Panel { get; set; }
```  
***

## `Panels`<a href="property-panels" id="property-panels"></a>
===
```csharp
public List<string> Panels { get; }
```  
***

## `Series`<a href="property-series" id="property-series"></a>
===
```csharp
public IndicatorSeries Series { get; }
```  
***

## `SettingsLongKey`<a href="property-settingslongkey" id="property-settingslongkey"></a>
===
```csharp
protected string SettingsLongKey { get; private set; }
```  
***

## `SettingsShortKey`<a href="property-settingsshortkey" id="property-settingsshortkey"></a>
===
```csharp
protected string SettingsShortKey { get; private set; }
```  
***

## `ShowIndicator`<a href="property-showindicator" id="property-showindicator"></a>
===
```csharp
public bool ShowIndicator { get; set; }
```  
***

## `ShowIndicatorLabels`<a href="property-showindicatorlabels" id="property-showindicatorlabels"></a>
===
```csharp
public virtual bool ShowIndicatorLabels { get; set; }
```  
***

## `ShowIndicatorLabelsParam`<a href="property-showindicatorlabelsparam" id="property-showindicatorlabelsparam"></a>
===
```csharp
public bool? ShowIndicatorLabelsParam { get; set; }
```  
***

## `ShowIndicatorParam`<a href="property-showindicatorparam" id="property-showindicatorparam"></a>
===
```csharp
public bool? ShowIndicatorParam { get; set; }
```  
***

## `ShowIndicatorTitle`<a href="property-showindicatortitle" id="property-showindicatortitle"></a>
===
```csharp
public virtual bool ShowIndicatorTitle { get; set; }
```  
***

## `ShowIndicatorTitleParam`<a href="property-showindicatortitleparam" id="property-showindicatortitleparam"></a>
===
```csharp
public bool? ShowIndicatorTitleParam { get; set; }
```  
***

## `ShowIndicatorValues`<a href="property-showindicatorvalues" id="property-showindicatorvalues"></a>
===
```csharp
public virtual bool ShowIndicatorValues { get; set; }
```  
***

## `ShowIndicatorValuesParam`<a href="property-showindicatorvaluesparam" id="property-showindicatorvaluesparam"></a>
===
```csharp
public bool? ShowIndicatorValuesParam { get; set; }
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

