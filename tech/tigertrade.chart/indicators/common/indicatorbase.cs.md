# IndicatorBase

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Common](./)

\===

#### Синтаксис

```csharp
public abstract class IndicatorBase : INotifyPropertyChanged, IDynamicProperty
```

## Список методов

| Название                                                                                  | Описание |
| ----------------------------------------------------------------------------------------- | -------- |
| [`AddAlert`](indicatorbase.cs.md#method-addalert)                                         | _===_    |
| [`ApplyColors`](indicatorbase.cs.md#method-applycolors)                                   | _===_    |
| [`CheckNeedRedraw`](indicatorbase.cs.md#method-checkneedredraw)                           | _===_    |
| [`CopyTemplate`](indicatorbase.cs.md#method-copytemplate)                                 | _===_    |
| [`Execute`](indicatorbase.cs.md#method-execute)                                           | _===_    |
| [`GetAlerts`](indicatorbase.cs.md#method-getalerts)                                       | _===_    |
| [`GetDistance`](indicatorbase.cs.md#method-getdistance)                                   | _===_    |
| [`GetLabels`](indicatorbase.cs.md#method-getlabels)                                       | _===_    |
| [`GetMinMax`](indicatorbase.cs.md#method-getminmax)                                       | _===_    |
| [`GetPoints`](indicatorbase.cs.md#method-getpoints)                                       | _===_    |
| [`GetPropertyHasStandardValues`](indicatorbase.cs.md#method-getpropertyhasstandardvalues) | _===_    |
| [`GetPropertyReadOnly`](indicatorbase.cs.md#method-getpropertyreadonly)                   | _===_    |
| [`GetPropertyStandardValues`](indicatorbase.cs.md#method-getpropertystandardvalues)       | _===_    |
| [`GetPropertyVisibility`](indicatorbase.cs.md#method-getpropertyvisibility)               | _===_    |
| [`GetTitle`](indicatorbase.cs.md#method-gettitle)                                         | _===_    |
| [`GetValues`](indicatorbase.cs.md#method-getvalues)                                       | _===_    |
| [`GetX`](indicatorbase.cs.md#method-getx)                                                 | _===_    |
| [`GetY`](indicatorbase.cs.md#method-gety)                                                 | _===_    |
| [`IndicatorBase`](indicatorbase.cs.md#method-indicatorbase)                               | _===_    |
| [`OnPropertyChanged`](indicatorbase.cs.md#method-onpropertychanged)                       | _===_    |
| [`PropChanged`](indicatorbase.cs.md#method-propchanged)                                   | _===_    |
| [`Render`](indicatorbase.cs.md#method-render)                                             | _===_    |
| [`Run`](indicatorbase.cs.md#method-run)                                                   | _===_    |
| [`SetSettingsParam`](indicatorbase.cs.md#method-setsettingsparam)                         | _===_    |
| [`ToString`](indicatorbase.cs.md#method-tostring)                                         | _===_    |

## Список свойств

| Название                                                                            | Описание |
| ----------------------------------------------------------------------------------- | -------- |
| [`Calculation`](indicatorbase.cs.md#property-calculation)                           | _===_    |
| [`Canvas`](indicatorbase.cs.md#property-canvas)                                     | _===_    |
| [`ChartDataType`](indicatorbase.cs.md#property-chartdatatype)                       | _===_    |
| [`ClearData`](indicatorbase.cs.md#property-cleardata)                               | _===_    |
| [`DataProvider`](indicatorbase.cs.md#property-dataprovider)                         | _===_    |
| [`DefaultCalculation`](indicatorbase.cs.md#property-defaultcalculation)             | _===_    |
| [`DisableRender`](indicatorbase.cs.md#property-disablerender)                       | _===_    |
| [`Helper`](indicatorbase.cs.md#property-helper)                                     | _===_    |
| [`ID`](indicatorbase.cs.md#property-id)                                             | _===_    |
| [`IntegerValues`](indicatorbase.cs.md#property-integervalues)                       | _===_    |
| [`IsStock`](indicatorbase.cs.md#property-isstock)                                   | _===_    |
| [`Levels`](indicatorbase.cs.md#property-levels)                                     | _===_    |
| [`Name`](indicatorbase.cs.md#property-name)                                         | _===_    |
| [`Panel`](indicatorbase.cs.md#property-panel)                                       | _===_    |
| [`Panels`](indicatorbase.cs.md#property-panels)                                     | _===_    |
| [`Series`](indicatorbase.cs.md#property-series)                                     | _===_    |
| [`SettingsLongKey`](indicatorbase.cs.md#property-settingslongkey)                   | _===_    |
| [`SettingsShortKey`](indicatorbase.cs.md#property-settingsshortkey)                 | _===_    |
| [`ShowIndicator`](indicatorbase.cs.md#property-showindicator)                       | _===_    |
| [`ShowIndicatorLabels`](indicatorbase.cs.md#property-showindicatorlabels)           | _===_    |
| [`ShowIndicatorLabelsParam`](indicatorbase.cs.md#property-showindicatorlabelsparam) | _===_    |
| [`ShowIndicatorParam`](indicatorbase.cs.md#property-showindicatorparam)             | _===_    |
| [`ShowIndicatorTitle`](indicatorbase.cs.md#property-showindicatortitle)             | _===_    |
| [`ShowIndicatorTitleParam`](indicatorbase.cs.md#property-showindicatortitleparam)   | _===_    |
| [`ShowIndicatorValues`](indicatorbase.cs.md#property-showindicatorvalues)           | _===_    |
| [`ShowIndicatorValuesParam`](indicatorbase.cs.md#property-showindicatorvaluesparam) | _===_    |
| [`Title`](indicatorbase.cs.md#property-title)                                       | _===_    |

## Список событий

| Название                                                       | Описание |
| -------------------------------------------------------------- | -------- |
| [`PropertyChanged`](indicatorbase.cs.md#event-propertychanged) | _===_    |

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

### `ApplyColors` <a href="#method-applycolors" id="method-applycolors"></a>

\===

```csharp
public virtual void ApplyColors(IChartTheme palette)
```

`palette` _<mark style="color:red;">`IChartTheme`</mark>_\
_===_

***

### `CheckNeedRedraw` <a href="#method-checkneedredraw" id="method-checkneedredraw"></a>

\===

```csharp
public virtual bool CheckNeedRedraw()
```

***

### `CopyTemplate` <a href="#method-copytemplate" id="method-copytemplate"></a>

\===

```csharp
public virtual void CopyTemplate(IndicatorBase indicator, bool style)
```

`indicator` _<mark style="color:red;">`IndicatorBase`</mark>_\
_===_

`style` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `Execute` <a href="#method-execute" id="method-execute"></a>

\===

```csharp
protected abstract void Execute()
```

***

### `GetAlerts` <a href="#method-getalerts" id="method-getalerts"></a>

\===

```csharp
public List<ChartAlertInfo> GetAlerts()
```

***

### `GetDistance` <a href="#method-getdistance" id="method-getdistance"></a>

\===

```csharp
public virtual double GetDistance(double x, double y)
```

`x` _<mark style="color:red;">`double`</mark>_\
_===_

`y` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `GetLabels` <a href="#method-getlabels" id="method-getlabels"></a>

\===

```csharp
public virtual void GetLabels(ref List<IndicatorLabelInfo> labels)
```

`List` _<mark style="color:red;">`ref`</mark>_\
_===_

***

### `GetMinMax` <a href="#method-getminmax" id="method-getminmax"></a>

\===

```csharp
public virtual bool GetMinMax(out double min, out double max)
```

`double` _<mark style="color:red;">`out`</mark>_\
_===_

`double` _<mark style="color:red;">`out`</mark>_\
_===_

***

### `GetPoints` <a href="#method-getpoints" id="method-getpoints"></a>

\===

```csharp
protected Point[] GetPoints(IndicatorSeriesData seriesData, string name = null)
```

`seriesData` _<mark style="color:red;">`IndicatorSeriesData`</mark>_\
_===_

`name` _<mark style="color:red;">`string`</mark>_\
_===_

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

### `GetTitle` <a href="#method-gettitle" id="method-gettitle"></a>

\===

```csharp
public virtual IndicatorTitleInfo GetTitle()
```

`IndicatorTitleInfo` _<mark style="color:red;">`new`</mark>_\
_===_

***

### `GetValues` <a href="#method-getvalues" id="method-getvalues"></a>

\===

```csharp
public virtual List<IndicatorValueInfo> GetValues(int cursorPos)
```

`cursorPos` _<mark style="color:red;">`int`</mark>_\
_===_

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

### `GetY` <a href="#method-gety" id="method-gety"></a>

\===

```csharp
protected double GetY(double d)
protected double GetY(Decimal d)
```

`d` _<mark style="color:red;">`double`</mark>_\
_===_

`d` _<mark style="color:red;">`Decimal`</mark>_\
_===_

***

### `IndicatorBase` <a href="#method-indicatorbase" id="method-indicatorbase"></a>

\===

```csharp
protected IndicatorBase()
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

### `PropChanged` <a href="#method-propchanged" id="method-propchanged"></a>

\===

```csharp
public void PropChanged()
```

***

### `Render` <a href="#method-render" id="method-render"></a>

\===

```csharp
public virtual void Render(DxVisualQueue visual)
```

`visual` _<mark style="color:red;">`DxVisualQueue`</mark>_\
_===_

***

### `Run` <a href="#method-run" id="method-run"></a>

\===

```csharp
public void Run(IChartDataProvider dp, string longKey, string shortKey, string revision)
```

`dp` _<mark style="color:red;">`IChartDataProvider`</mark>_\
_===_

`longKey` _<mark style="color:red;">`string`</mark>_\
_===_

`shortKey` _<mark style="color:red;">`string`</mark>_\
_===_

`revision` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `SetSettingsParam` <a href="#method-setsettingsparam" id="method-setsettingsparam"></a>

\===

```csharp
public virtual void SetSettingsParam(string name, object param)
```

`name` _<mark style="color:red;">`string`</mark>_\
_===_

`param` _<mark style="color:red;">`object`</mark>_\
_===_

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

### `Calculation` <a href="#property-calculation" id="property-calculation"></a>

\===

```csharp
public virtual IndicatorCalculation Calculation { get; set; }
```

***

### `Canvas` <a href="#property-canvas" id="property-canvas"></a>

\===

```csharp
public IChartCanvas Canvas { get; set; }
```

***

### `ChartDataType` <a href="#property-chartdatatype" id="property-chartdatatype"></a>

\===

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***

### `ClearData` <a href="#property-cleardata" id="property-cleardata"></a>

\===

```csharp
protected bool ClearData { get; private set; }
```

***

### `DataProvider` <a href="#property-dataprovider" id="property-dataprovider"></a>

\===

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```

***

### `DefaultCalculation` <a href="#property-defaultcalculation" id="property-defaultcalculation"></a>

\===

```csharp
public virtual IndicatorCalculation DefaultCalculation { get; }
```

***

### `DisableRender` <a href="#property-disablerender" id="property-disablerender"></a>

\===

```csharp
public bool DisableRender { get; protected set; }
```

***

### `Helper` <a href="#property-helper" id="property-helper"></a>

\===

```csharp
protected IndicatorsHelper Helper { get; private set; }
```

***

### `ID` <a href="#property-id" id="property-id"></a>

\===

```csharp
public string ID { get; }
```

***

### `IntegerValues` <a href="#property-integervalues" id="property-integervalues"></a>

\===

```csharp
public virtual bool IntegerValues { get; }
```

***

### `IsStock` <a href="#property-isstock" id="property-isstock"></a>

\===

```csharp
public virtual bool IsStock { get; }
```

***

### `Levels` <a href="#property-levels" id="property-levels"></a>

\===

```csharp
public List<ChartLevel> Levels { get; set; }
```

***

### `Name` <a href="#property-name" id="property-name"></a>

\===

```csharp
public string Name { get; }
```

***

### `Panel` <a href="#property-panel" id="property-panel"></a>

\===

```csharp
public string Panel { get; set; }
```

***

### `Panels` <a href="#property-panels" id="property-panels"></a>

\===

```csharp
public List<string> Panels { get; }
```

***

### `Series` <a href="#property-series" id="property-series"></a>

\===

```csharp
public IndicatorSeries Series { get; }
```

***

### `SettingsLongKey` <a href="#property-settingslongkey" id="property-settingslongkey"></a>

\===

```csharp
protected string SettingsLongKey { get; private set; }
```

***

### `SettingsShortKey` <a href="#property-settingsshortkey" id="property-settingsshortkey"></a>

\===

```csharp
protected string SettingsShortKey { get; private set; }
```

***

### `ShowIndicator` <a href="#property-showindicator" id="property-showindicator"></a>

\===

```csharp
public bool ShowIndicator { get; set; }
```

***

### `ShowIndicatorLabels` <a href="#property-showindicatorlabels" id="property-showindicatorlabels"></a>

\===

```csharp
public virtual bool ShowIndicatorLabels { get; set; }
```

***

### `ShowIndicatorLabelsParam` <a href="#property-showindicatorlabelsparam" id="property-showindicatorlabelsparam"></a>

\===

```csharp
public bool? ShowIndicatorLabelsParam { get; set; }
```

***

### `ShowIndicatorParam` <a href="#property-showindicatorparam" id="property-showindicatorparam"></a>

\===

```csharp
public bool? ShowIndicatorParam { get; set; }
```

***

### `ShowIndicatorTitle` <a href="#property-showindicatortitle" id="property-showindicatortitle"></a>

\===

```csharp
public virtual bool ShowIndicatorTitle { get; set; }
```

***

### `ShowIndicatorTitleParam` <a href="#property-showindicatortitleparam" id="property-showindicatortitleparam"></a>

\===

```csharp
public bool? ShowIndicatorTitleParam { get; set; }
```

***

### `ShowIndicatorValues` <a href="#property-showindicatorvalues" id="property-showindicatorvalues"></a>

\===

```csharp
public virtual bool ShowIndicatorValues { get; set; }
```

***

### `ShowIndicatorValuesParam` <a href="#property-showindicatorvaluesparam" id="property-showindicatorvaluesparam"></a>

\===

```csharp
public bool? ShowIndicatorValuesParam { get; set; }
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
