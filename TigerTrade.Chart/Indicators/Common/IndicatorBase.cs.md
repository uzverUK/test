
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public abstract class IndicatorBase : INotifyPropertyChanged, IDynamicProperty
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`AddAlert`](./IndicatorBase.cs/Методы/AddAlert.md) | *Описание* |
| [`ApplyColors`](./IndicatorBase.cs/Методы/ApplyColors.md) | *Описание* |
| [`CheckNeedRedraw`](./IndicatorBase.cs/Методы/CheckNeedRedraw.md) | *Описание* |
| [`CopyTemplate`](./IndicatorBase.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Execute`](./IndicatorBase.cs/Методы/Execute.md) | *Описание* |
| [`GetAlerts`](./IndicatorBase.cs/Методы/GetAlerts.md) | *Описание* |
| [`GetDistance`](./IndicatorBase.cs/Методы/GetDistance.md) | *Описание* |
| [`GetLabels`](./IndicatorBase.cs/Методы/GetLabels.md) | *Описание* |
| [`GetMinMax`](./IndicatorBase.cs/Методы/GetMinMax.md) | *Описание* |
| [`GetPoints`](./IndicatorBase.cs/Методы/GetPoints.md) | *Описание* |
| [`GetPropertyHasStandardValues`](./IndicatorBase.cs/Методы/GetPropertyHasStandardValues.md) | *Описание* |
| [`GetPropertyReadOnly`](./IndicatorBase.cs/Методы/GetPropertyReadOnly.md) | *Описание* |
| [`GetPropertyStandardValues`](./IndicatorBase.cs/Методы/GetPropertyStandardValues.md) | *Описание* |
| [`GetPropertyVisibility`](./IndicatorBase.cs/Методы/GetPropertyVisibility.md) | *Описание* |
| [`GetTitle`](./IndicatorBase.cs/Методы/GetTitle.md) | *Описание* |
| [`GetValues`](./IndicatorBase.cs/Методы/GetValues.md) | *Описание* |
| [`GetX`](./IndicatorBase.cs/Методы/GetX.md) | *Описание* |
| [`GetY`](./IndicatorBase.cs/Методы/GetY.md) | *Описание* |
| [`IndicatorBase`](./IndicatorBase.cs/Методы/IndicatorBase.md) | *Описание* |
| [`OnPropertyChanged`](./IndicatorBase.cs/Методы/OnPropertyChanged.md) | *Описание* |
| [`PropChanged`](./IndicatorBase.cs/Методы/PropChanged.md) | *Описание* |
| [`Render`](./IndicatorBase.cs/Методы/Render.md) | *Описание* |
| [`Run`](./IndicatorBase.cs/Методы/Run.md) | *Описание* |
| [`SetSettingsParam`](./IndicatorBase.cs/Методы/SetSettingsParam.md) | *Описание* |
| [`ToString`](./IndicatorBase.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Calculation`](./IndicatorBase.cs/Свойства/Calculation.md) | *Описание* |
| [`Canvas`](./IndicatorBase.cs/Свойства/Canvas.md) | *Описание* |
| [`ChartDataType`](./IndicatorBase.cs/Свойства/ChartDataType.md) | *Описание* |
| [`ClearData`](./IndicatorBase.cs/Свойства/ClearData.md) | *Описание* |
| [`DataProvider`](./IndicatorBase.cs/Свойства/DataProvider.md) | *Описание* |
| [`DefaultCalculation`](./IndicatorBase.cs/Свойства/DefaultCalculation.md) | *Описание* |
| [`DisableRender`](./IndicatorBase.cs/Свойства/DisableRender.md) | *Описание* |
| [`Helper`](./IndicatorBase.cs/Свойства/Helper.md) | *Описание* |
| [`ID`](./IndicatorBase.cs/Свойства/ID.md) | *Описание* |
| [`IntegerValues`](./IndicatorBase.cs/Свойства/IntegerValues.md) | *Описание* |
| [`IsStock`](./IndicatorBase.cs/Свойства/IsStock.md) | *Описание* |
| [`Levels`](./IndicatorBase.cs/Свойства/Levels.md) | *Описание* |
| [`Name`](./IndicatorBase.cs/Свойства/Name.md) | *Описание* |
| [`Panel`](./IndicatorBase.cs/Свойства/Panel.md) | *Описание* |
| [`Panels`](./IndicatorBase.cs/Свойства/Panels.md) | *Описание* |
| [`Series`](./IndicatorBase.cs/Свойства/Series.md) | *Описание* |
| [`SettingsLongKey`](./IndicatorBase.cs/Свойства/SettingsLongKey.md) | *Описание* |
| [`SettingsShortKey`](./IndicatorBase.cs/Свойства/SettingsShortKey.md) | *Описание* |
| [`ShowIndicator`](./IndicatorBase.cs/Свойства/ShowIndicator.md) | *Описание* |
| [`ShowIndicatorLabels`](./IndicatorBase.cs/Свойства/ShowIndicatorLabels.md) | *Описание* |
| [`ShowIndicatorLabelsParam`](./IndicatorBase.cs/Свойства/ShowIndicatorLabelsParam.md) | *Описание* |
| [`ShowIndicatorParam`](./IndicatorBase.cs/Свойства/ShowIndicatorParam.md) | *Описание* |
| [`ShowIndicatorTitle`](./IndicatorBase.cs/Свойства/ShowIndicatorTitle.md) | *Описание* |
| [`ShowIndicatorTitleParam`](./IndicatorBase.cs/Свойства/ShowIndicatorTitleParam.md) | *Описание* |
| [`ShowIndicatorValues`](./IndicatorBase.cs/Свойства/ShowIndicatorValues.md) | *Описание* |
| [`ShowIndicatorValuesParam`](./IndicatorBase.cs/Свойства/ShowIndicatorValuesParam.md) | *Описание* |
| [`Title`](./IndicatorBase.cs/Свойства/Title.md) | *Описание* |

# Таблица событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./IndicatorBase.cs/События/PropertyChanged.md) | *Описание* |





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



## *ApplyColors*
Описание

```csharp
public virtual void ApplyColors(IChartTheme palette)
```
<mark style="color:yellow;">`palette`</mark> <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  



## *CheckNeedRedraw*
Описание

```csharp
public virtual bool CheckNeedRedraw()
```


## *CopyTemplate*
Описание

```csharp
public virtual void CopyTemplate(IndicatorBase indicator, bool style)
```

<mark style="color:yellow;">`indicator`</mark> <mark style="color:red;">*`IndicatorBase`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *Execute*
Описание

```csharp
protected abstract void Execute()
```


## *GetAlerts*
Описание

```csharp
public List<ChartAlertInfo> GetAlerts()
```


## *GetDistance*
Описание

```csharp
public virtual double GetDistance(double x, double y)
```

<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *GetLabels*
Описание

```csharp
public virtual void GetLabels(ref List<IndicatorLabelInfo> labels)
```
<mark style="color:yellow;">`List`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  



## *GetMinMax*
Описание

```csharp
public virtual bool GetMinMax(out double min, out double max)
```
<mark style="color:yellow;">`double`</mark> <mark style="color:red;">*`out`*</mark>  
 *Описание*  

<mark style="color:yellow;">`double`</mark> <mark style="color:red;">*`out`*</mark>  
 *Описание*  



## *GetPoints*
Описание

```csharp
protected Point[] GetPoints(IndicatorSeriesData seriesData, string name = null)
```
<mark style="color:yellow;">`seriesData`</mark> <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *Описание*  

<mark style="color:yellow;">`name`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



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


## *GetTitle*
Описание

```csharp
public virtual IndicatorTitleInfo GetTitle()
```

<mark style="color:yellow;">`IndicatorTitleInfo`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  



## *GetValues*
Описание

```csharp
public virtual List<IndicatorValueInfo> GetValues(int cursorPos)
```
<mark style="color:yellow;">`cursorPos`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



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



## *GetY*
Описание

```csharp
protected double GetY(double d)
protected double GetY(Decimal d)
```
<mark style="color:yellow;">`d`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:yellow;">`d`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  



## *IndicatorBase*
Описание

```csharp
protected IndicatorBase()
```


## *OnPropertyChanged*
Описание

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

<mark style="color:yellow;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *PropChanged*
Описание

```csharp
public void PropChanged()
```


## *Render*
Описание

```csharp
public virtual void Render(DxVisualQueue visual)
```

<mark style="color:yellow;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  



## *Run*
Описание

```csharp
public void Run(IChartDataProvider dp, string longKey, string shortKey, string revision)
```
<mark style="color:yellow;">`dp`</mark> <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *Описание*  

<mark style="color:yellow;">`longKey`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:yellow;">`shortKey`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:yellow;">`revision`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *SetSettingsParam*
Описание

```csharp
public virtual void SetSettingsParam(string name, object param)
```
<mark style="color:yellow;">`name`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:yellow;">`param`</mark> <mark style="color:red;">*`object`*</mark>  
 *Описание*  



## *ToString*
Описание

```csharp
public override string ToString()
```

# Свойства

## *Calculation*
> Описание

```csharp
public virtual IndicatorCalculation Calculation { get; set; }
```

## *Canvas*
> Описание

```csharp
public IChartCanvas Canvas { get; set; }
```

## *ChartDataType*
> Описание

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

## *ClearData*
> Описание

```csharp
protected bool ClearData { get; private set; }
```

## *DataProvider*
> Описание

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```

## *DefaultCalculation*
> Описание

```csharp
public virtual IndicatorCalculation DefaultCalculation { get; }
```

## *DisableRender*
> Описание

```csharp
public bool DisableRender { get; protected set; }
```

## *Helper*
> Описание

```csharp
protected IndicatorsHelper Helper { get; private set; }
```

## *ID*
> Описание

```csharp
public string ID { get; }
```

## *IntegerValues*
> Описание

```csharp
public virtual bool IntegerValues { get; }
```

## *IsStock*
> Описание

```csharp
public virtual bool IsStock { get; }
```

## *Levels*
> Описание

```csharp
public List<ChartLevel> Levels { get; set; }
```

## *Name*
> Описание

```csharp
public string Name { get; }
```

## *Panel*
> Описание

```csharp
public string Panel { get; set; }
```

## *Panels*
> Описание

```csharp
public List<string> Panels { get; }
```

## *Series*
> Описание

```csharp
public IndicatorSeries Series { get; }
```

## *SettingsLongKey*
> Описание

```csharp
protected string SettingsLongKey { get; private set; }
```

## *SettingsShortKey*
> Описание

```csharp
protected string SettingsShortKey { get; private set; }
```

## *ShowIndicator*
> Описание

```csharp
public bool ShowIndicator { get; set; }
```

## *ShowIndicatorLabels*
> Описание

```csharp
public virtual bool ShowIndicatorLabels { get; set; }
```

## *ShowIndicatorLabelsParam*
> Описание

```csharp
public bool? ShowIndicatorLabelsParam { get; set; }
```

## *ShowIndicatorParam*
> Описание

```csharp
public bool? ShowIndicatorParam { get; set; }
```

## *ShowIndicatorTitle*
> Описание

```csharp
public virtual bool ShowIndicatorTitle { get; set; }
```

## *ShowIndicatorTitleParam*
> Описание

```csharp
public bool? ShowIndicatorTitleParam { get; set; }
```

## *ShowIndicatorValues*
> Описание

```csharp
public virtual bool ShowIndicatorValues { get; set; }
```

## *ShowIndicatorValuesParam*
> Описание

```csharp
public bool? ShowIndicatorValuesParam { get; set; }
```

## *Title*
> Описание

```csharp
public string Title { get; }
```
# <font color="Purple">Событияs</font>

## *PropertyChanged*
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

