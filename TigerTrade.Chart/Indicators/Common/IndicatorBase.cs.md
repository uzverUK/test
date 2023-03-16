
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public abstract class IndicatorBase : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddAlert`](#AddAlert-m) | *Описание* |
| [`ApplyColors`](#ApplyColors-m) | *Описание* |
| [`CheckNeedRedraw`](#CheckNeedRedraw-m) | *Описание* |
| [`CopyTemplate`](#CopyTemplate-m) | *Описание* |
| [`Execute`](#Execute-m) | *Описание* |
| [`GetAlerts`](#GetAlerts-m) | *Описание* |
| [`GetDistance`](#GetDistance-m) | *Описание* |
| [`GetLabels`](#GetLabels-m) | *Описание* |
| [`GetMinMax`](#GetMinMax-m) | *Описание* |
| [`GetPoints`](#GetPoints-m) | *Описание* |
| [`GetPropertyHasStandardValues`](#GetPropertyHasStandardValues-m) | *Описание* |
| [`GetPropertyReadOnly`](#GetPropertyReadOnly-m) | *Описание* |
| [`GetPropertyStandardValues`](#GetPropertyStandardValues-m) | *Описание* |
| [`GetPropertyVisibility`](#GetPropertyVisibility-m) | *Описание* |
| [`GetTitle`](#GetTitle-m) | *Описание* |
| [`GetValues`](#GetValues-m) | *Описание* |
| [`GetX`](#GetX-m) | *Описание* |
| [`GetY`](#GetY-m) | *Описание* |
| [`IndicatorBase`](#IndicatorBase-m) | *Описание* |
| [`OnPropertyChanged`](#OnPropertyChanged-m) | *Описание* |
| [`PropChanged`](#PropChanged-m) | *Описание* |
| [`Render`](#Render-m) | *Описание* |
| [`Run`](#Run-m) | *Описание* |
| [`SetSettingsParam`](#SetSettingsParam-m) | *Описание* |
| [`ToString`](#ToString-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Calculation`](#Calculation-p) | *Описание* |
| [`Canvas`](#Canvas-p) | *Описание* |
| [`ChartDataType`](#ChartDataType-p) | *Описание* |
| [`ClearData`](#ClearData-p) | *Описание* |
| [`DataProvider`](#DataProvider-p) | *Описание* |
| [`DefaultCalculation`](#DefaultCalculation-p) | *Описание* |
| [`DisableRender`](#DisableRender-p) | *Описание* |
| [`Helper`](#Helper-p) | *Описание* |
| [`ID`](#ID-p) | *Описание* |
| [`IntegerValues`](#IntegerValues-p) | *Описание* |
| [`IsStock`](#IsStock-p) | *Описание* |
| [`Levels`](#Levels-p) | *Описание* |
| [`Name`](#Name-p) | *Описание* |
| [`Panel`](#Panel-p) | *Описание* |
| [`Panels`](#Panels-p) | *Описание* |
| [`Series`](#Series-p) | *Описание* |
| [`SettingsLongKey`](#SettingsLongKey-p) | *Описание* |
| [`SettingsShortKey`](#SettingsShortKey-p) | *Описание* |
| [`ShowIndicator`](#ShowIndicator-p) | *Описание* |
| [`ShowIndicatorLabels`](#ShowIndicatorLabels-p) | *Описание* |
| [`ShowIndicatorLabelsParam`](#ShowIndicatorLabelsParam-p) | *Описание* |
| [`ShowIndicatorParam`](#ShowIndicatorParam-p) | *Описание* |
| [`ShowIndicatorTitle`](#ShowIndicatorTitle-p) | *Описание* |
| [`ShowIndicatorTitleParam`](#ShowIndicatorTitleParam-p) | *Описание* |
| [`ShowIndicatorValues`](#ShowIndicatorValues-p) | *Описание* |
| [`ShowIndicatorValuesParam`](#ShowIndicatorValuesParam-p) | *Описание* |
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

## `ApplyColors`<a href="ApplyColors-m" id="ApplyColors-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ApplyColors(IChartTheme palette)
```
`palette` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `CheckNeedRedraw`<a href="CheckNeedRedraw-m" id="CheckNeedRedraw-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool CheckNeedRedraw()
```

***  

## `CopyTemplate`<a href="CopyTemplate-m" id="CopyTemplate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CopyTemplate(IndicatorBase indicator, bool style)
```

`indicator` <mark style="color:red;">*`IndicatorBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Execute`<a href="Execute-m" id="Execute-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract void Execute()
```

***  

## `GetAlerts`<a href="GetAlerts-m" id="GetAlerts-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartAlertInfo> GetAlerts()
```

***  

## `GetDistance`<a href="GetDistance-m" id="GetDistance-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual double GetDistance(double x, double y)
```

`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetLabels`<a href="GetLabels-m" id="GetLabels-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void GetLabels(ref List<IndicatorLabelInfo> labels)
```
`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `GetMinMax`<a href="GetMinMax-m" id="GetMinMax-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetMinMax(out double min, out double max)
```
`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  

`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  


***  

## `GetPoints`<a href="GetPoints-m" id="GetPoints-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] GetPoints(IndicatorSeriesData seriesData, string name = null)
```
`seriesData` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *Описание*  

`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


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

## `GetTitle`<a href="GetTitle-m" id="GetTitle-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorTitleInfo GetTitle()
```

`IndicatorTitleInfo` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `GetValues`<a href="GetValues-m" id="GetValues-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual List<IndicatorValueInfo> GetValues(int cursorPos)
```
`cursorPos` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


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

## `GetY`<a href="GetY-m" id="GetY-m"></a>
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

## `IndicatorBase`<a href="IndicatorBase-m" id="IndicatorBase-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorBase()
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

## `PropChanged`<a href="PropChanged-m" id="PropChanged-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void PropChanged()
```

***  

## `Render`<a href="Render-m" id="Render-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void Render(DxVisualQueue visual)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `Run`<a href="Run-m" id="Run-m"></a>
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

## `SetSettingsParam`<a href="SetSettingsParam-m" id="SetSettingsParam-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void SetSettingsParam(string name, object param)
```
`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`param` <mark style="color:red;">*`object`*</mark>  
 *Описание*  


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

## `Calculation`<a href="Calculation-p" id="Calculation-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorCalculation Calculation { get; set; }
```  
***

## `Canvas`<a href="Canvas-p" id="Canvas-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IChartCanvas Canvas { get; set; }
```  
***

## `ChartDataType`<a href="ChartDataType-p" id="ChartDataType-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

## `ClearData`<a href="ClearData-p" id="ClearData-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected bool ClearData { get; private set; }
```  
***

## `DataProvider`<a href="DataProvider-p" id="DataProvider-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```  
***

## `DefaultCalculation`<a href="DefaultCalculation-p" id="DefaultCalculation-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorCalculation DefaultCalculation { get; }
```  
***

## `DisableRender`<a href="DisableRender-p" id="DisableRender-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool DisableRender { get; protected set; }
```  
***

## `Helper`<a href="Helper-p" id="Helper-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorsHelper Helper { get; private set; }
```  
***

## `ID`<a href="ID-p" id="ID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `IntegerValues`<a href="IntegerValues-p" id="IntegerValues-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool IntegerValues { get; }
```  
***

## `IsStock`<a href="IsStock-p" id="IsStock-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool IsStock { get; }
```  
***

## `Levels`<a href="Levels-p" id="Levels-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartLevel> Levels { get; set; }
```  
***

## `Name`<a href="Name-p" id="Name-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `Panel`<a href="Panel-p" id="Panel-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Panel { get; set; }
```  
***

## `Panels`<a href="Panels-p" id="Panels-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<string> Panels { get; }
```  
***

## `Series`<a href="Series-p" id="Series-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeries Series { get; }
```  
***

## `SettingsLongKey`<a href="SettingsLongKey-p" id="SettingsLongKey-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected string SettingsLongKey { get; private set; }
```  
***

## `SettingsShortKey`<a href="SettingsShortKey-p" id="SettingsShortKey-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected string SettingsShortKey { get; private set; }
```  
***

## `ShowIndicator`<a href="ShowIndicator-p" id="ShowIndicator-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowIndicator { get; set; }
```  
***

## `ShowIndicatorLabels`<a href="ShowIndicatorLabels-p" id="ShowIndicatorLabels-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorLabels { get; set; }
```  
***

## `ShowIndicatorLabelsParam`<a href="ShowIndicatorLabelsParam-p" id="ShowIndicatorLabelsParam-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorLabelsParam { get; set; }
```  
***

## `ShowIndicatorParam`<a href="ShowIndicatorParam-p" id="ShowIndicatorParam-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorParam { get; set; }
```  
***

## `ShowIndicatorTitle`<a href="ShowIndicatorTitle-p" id="ShowIndicatorTitle-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorTitle { get; set; }
```  
***

## `ShowIndicatorTitleParam`<a href="ShowIndicatorTitleParam-p" id="ShowIndicatorTitleParam-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorTitleParam { get; set; }
```  
***

## `ShowIndicatorValues`<a href="ShowIndicatorValues-p" id="ShowIndicatorValues-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorValues { get; set; }
```  
***

## `ShowIndicatorValuesParam`<a href="ShowIndicatorValuesParam-p" id="ShowIndicatorValuesParam-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorValuesParam { get; set; }
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

