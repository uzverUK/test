
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public abstract class IndicatorBase : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddAlert`](#method-addalert) | *Описание* |
| [`ApplyColors`](#method-applycolors) | *Описание* |
| [`CheckNeedRedraw`](#method-checkneedredraw) | *Описание* |
| [`CopyTemplate`](#method-copytemplate) | *Описание* |
| [`Execute`](#method-execute) | *Описание* |
| [`GetAlerts`](#method-getalerts) | *Описание* |
| [`GetDistance`](#method-getdistance) | *Описание* |
| [`GetLabels`](#method-getlabels) | *Описание* |
| [`GetMinMax`](#method-getminmax) | *Описание* |
| [`GetPoints`](#method-getpoints) | *Описание* |
| [`GetPropertyHasStandardValues`](#method-getpropertyhasstandardvalues) | *Описание* |
| [`GetPropertyReadOnly`](#method-getpropertyreadonly) | *Описание* |
| [`GetPropertyStandardValues`](#method-getpropertystandardvalues) | *Описание* |
| [`GetPropertyVisibility`](#method-getpropertyvisibility) | *Описание* |
| [`GetTitle`](#method-gettitle) | *Описание* |
| [`GetValues`](#method-getvalues) | *Описание* |
| [`GetX`](#method-getx) | *Описание* |
| [`GetY`](#method-gety) | *Описание* |
| [`IndicatorBase`](#method-indicatorbase) | *Описание* |
| [`OnPropertyChanged`](#method-onpropertychanged) | *Описание* |
| [`PropChanged`](#method-propchanged) | *Описание* |
| [`Render`](#method-render) | *Описание* |
| [`Run`](#method-run) | *Описание* |
| [`SetSettingsParam`](#method-setsettingsparam) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Calculation`](#property-calculation) | *Описание* |
| [`Canvas`](#property-canvas) | *Описание* |
| [`ChartDataType`](#property-chartdatatype) | *Описание* |
| [`ClearData`](#property-cleardata) | *Описание* |
| [`DataProvider`](#property-dataprovider) | *Описание* |
| [`DefaultCalculation`](#property-defaultcalculation) | *Описание* |
| [`DisableRender`](#property-disablerender) | *Описание* |
| [`Helper`](#property-helper) | *Описание* |
| [`ID`](#property-id) | *Описание* |
| [`IntegerValues`](#property-integervalues) | *Описание* |
| [`IsStock`](#property-isstock) | *Описание* |
| [`Levels`](#property-levels) | *Описание* |
| [`Name`](#property-name) | *Описание* |
| [`Panel`](#property-panel) | *Описание* |
| [`Panels`](#property-panels) | *Описание* |
| [`Series`](#property-series) | *Описание* |
| [`SettingsLongKey`](#property-settingslongkey) | *Описание* |
| [`SettingsShortKey`](#property-settingsshortkey) | *Описание* |
| [`ShowIndicator`](#property-showindicator) | *Описание* |
| [`ShowIndicatorLabels`](#property-showindicatorlabels) | *Описание* |
| [`ShowIndicatorLabelsParam`](#property-showindicatorlabelsparam) | *Описание* |
| [`ShowIndicatorParam`](#property-showindicatorparam) | *Описание* |
| [`ShowIndicatorTitle`](#property-showindicatortitle) | *Описание* |
| [`ShowIndicatorTitleParam`](#property-showindicatortitleparam) | *Описание* |
| [`ShowIndicatorValues`](#property-showindicatorvalues) | *Описание* |
| [`ShowIndicatorValuesParam`](#property-showindicatorvaluesparam) | *Описание* |
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

## `ApplyColors`<a href="method-applycolors" id="method-applycolors"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ApplyColors(IChartTheme palette)
```
`palette` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `CheckNeedRedraw`<a href="method-checkneedredraw" id="method-checkneedredraw"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool CheckNeedRedraw()
```

***  

## `CopyTemplate`<a href="method-copytemplate" id="method-copytemplate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CopyTemplate(IndicatorBase indicator, bool style)
```

`indicator` <mark style="color:red;">*`IndicatorBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Execute`<a href="method-execute" id="method-execute"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract void Execute()
```

***  

## `GetAlerts`<a href="method-getalerts" id="method-getalerts"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartAlertInfo> GetAlerts()
```

***  

## `GetDistance`<a href="method-getdistance" id="method-getdistance"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual double GetDistance(double x, double y)
```

`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetLabels`<a href="method-getlabels" id="method-getlabels"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void GetLabels(ref List<IndicatorLabelInfo> labels)
```
`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `GetMinMax`<a href="method-getminmax" id="method-getminmax"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetMinMax(out double min, out double max)
```
`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  

`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  


***  

## `GetPoints`<a href="method-getpoints" id="method-getpoints"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] GetPoints(IndicatorSeriesData seriesData, string name = null)
```
`seriesData` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *Описание*  

`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


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

## `GetTitle`<a href="method-gettitle" id="method-gettitle"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorTitleInfo GetTitle()
```

`IndicatorTitleInfo` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `GetValues`<a href="method-getvalues" id="method-getvalues"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual List<IndicatorValueInfo> GetValues(int cursorPos)
```
`cursorPos` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


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

## `GetY`<a href="method-gety" id="method-gety"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetY(double d)
protected double GetY(Decimal d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`d` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  


***  

## `IndicatorBase`<a href="method-indicatorbase" id="method-indicatorbase"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorBase()
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

## `PropChanged`<a href="method-propchanged" id="method-propchanged"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void PropChanged()
```

***  

## `Render`<a href="method-render" id="method-render"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void Render(DxVisualQueue visual)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `Run`<a href="method-run" id="method-run"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Run(IChartDataProvider dp, string longKey, string shortKey, string revision)
```
`dp` <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *Описание*  

`longKey` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`shortKey` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`revision` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `SetSettingsParam`<a href="method-setsettingsparam" id="method-setsettingsparam"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void SetSettingsParam(string name, object param)
```
`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`param` <mark style="color:red;">*`object`*</mark>  
 *Описание*  


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

## `Calculation`<a href="property-calculation" id="property-calculation"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorCalculation Calculation { get; set; }
```  
***

## `Canvas`<a href="property-canvas" id="property-canvas"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IChartCanvas Canvas { get; set; }
```  
***

## `ChartDataType`<a href="property-chartdatatype" id="property-chartdatatype"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

## `ClearData`<a href="property-cleardata" id="property-cleardata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected bool ClearData { get; private set; }
```  
***

## `DataProvider`<a href="property-dataprovider" id="property-dataprovider"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```  
***

## `DefaultCalculation`<a href="property-defaultcalculation" id="property-defaultcalculation"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorCalculation DefaultCalculation { get; }
```  
***

## `DisableRender`<a href="property-disablerender" id="property-disablerender"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool DisableRender { get; protected set; }
```  
***

## `Helper`<a href="property-helper" id="property-helper"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorsHelper Helper { get; private set; }
```  
***

## `ID`<a href="property-id" id="property-id"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `IntegerValues`<a href="property-integervalues" id="property-integervalues"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool IntegerValues { get; }
```  
***

## `IsStock`<a href="property-isstock" id="property-isstock"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool IsStock { get; }
```  
***

## `Levels`<a href="property-levels" id="property-levels"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartLevel> Levels { get; set; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `Panel`<a href="property-panel" id="property-panel"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Panel { get; set; }
```  
***

## `Panels`<a href="property-panels" id="property-panels"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<string> Panels { get; }
```  
***

## `Series`<a href="property-series" id="property-series"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeries Series { get; }
```  
***

## `SettingsLongKey`<a href="property-settingslongkey" id="property-settingslongkey"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected string SettingsLongKey { get; private set; }
```  
***

## `SettingsShortKey`<a href="property-settingsshortkey" id="property-settingsshortkey"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected string SettingsShortKey { get; private set; }
```  
***

## `ShowIndicator`<a href="property-showindicator" id="property-showindicator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowIndicator { get; set; }
```  
***

## `ShowIndicatorLabels`<a href="property-showindicatorlabels" id="property-showindicatorlabels"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorLabels { get; set; }
```  
***

## `ShowIndicatorLabelsParam`<a href="property-showindicatorlabelsparam" id="property-showindicatorlabelsparam"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorLabelsParam { get; set; }
```  
***

## `ShowIndicatorParam`<a href="property-showindicatorparam" id="property-showindicatorparam"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorParam { get; set; }
```  
***

## `ShowIndicatorTitle`<a href="property-showindicatortitle" id="property-showindicatortitle"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorTitle { get; set; }
```  
***

## `ShowIndicatorTitleParam`<a href="property-showindicatortitleparam" id="property-showindicatortitleparam"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorTitleParam { get; set; }
```  
***

## `ShowIndicatorValues`<a href="property-showindicatorvalues" id="property-showindicatorvalues"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorValues { get; set; }
```  
***

## `ShowIndicatorValuesParam`<a href="property-showindicatorvaluesparam" id="property-showindicatorvaluesparam"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorValuesParam { get; set; }
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

