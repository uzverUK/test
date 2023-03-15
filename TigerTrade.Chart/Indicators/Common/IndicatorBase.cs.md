
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
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void AddAlert(ChartAlertSettings settings, string message)
```

<mark style="color:purple;">`settings`</mark> <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

<mark style="color:purple;">`message`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *ApplyColors*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ApplyColors(IChartTheme palette)
```
<mark style="color:purple;">`palette`</mark> <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  



## *CheckNeedRedraw*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool CheckNeedRedraw()
```


## *CopyTemplate*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CopyTemplate(IndicatorBase indicator, bool style)
```

<mark style="color:purple;">`indicator`</mark> <mark style="color:red;">*`IndicatorBase`*</mark>  
 *Описание*  

<mark style="color:purple;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *Execute*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract void Execute()
```


## *GetAlerts*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartAlertInfo> GetAlerts()
```


## *GetDistance*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual double GetDistance(double x, double y)
```

<mark style="color:purple;">`x`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:purple;">`y`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *GetLabels*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void GetLabels(ref List<IndicatorLabelInfo> labels)
```
<mark style="color:purple;">`List`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  



## *GetMinMax*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetMinMax(out double min, out double max)
```
<mark style="color:purple;">`double`</mark> <mark style="color:red;">*`out`*</mark>  
 *Описание*  

<mark style="color:purple;">`double`</mark> <mark style="color:red;">*`out`*</mark>  
 *Описание*  



## *GetPoints*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] GetPoints(IndicatorSeriesData seriesData, string name = null)
```
<mark style="color:purple;">`seriesData`</mark> <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *Описание*  

<mark style="color:purple;">`name`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *GetPropertyHasStandardValues*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyHasStandardValues(string propertyName)
```
<mark style="color:purple;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *GetPropertyReadOnly*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyReadOnly(string propertyName)
```


## *GetPropertyStandardValues*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

<mark style="color:purple;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *GetPropertyVisibility*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyVisibility(string propertyName)
```


## *GetTitle*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorTitleInfo GetTitle()
```

<mark style="color:purple;">`IndicatorTitleInfo`</mark> <mark style="color:red;">*`new`*</mark>  
 *Описание*  



## *GetValues*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual List<IndicatorValueInfo> GetValues(int cursorPos)
```
<mark style="color:purple;">`cursorPos`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *GetX*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetX(int i)
```
<mark style="color:purple;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *GetY*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetY(double d)
```
<mark style="color:purple;">`d`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  



## *GetY*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetY(double d)
protected double GetY(Decimal d)
```
<mark style="color:purple;">`d`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:purple;">`d`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  



## *IndicatorBase*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorBase()
```


## *OnPropertyChanged*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

<mark style="color:purple;">`propertyName`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *PropChanged*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void PropChanged()
```


## *Render*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void Render(DxVisualQueue visual)
```

<mark style="color:purple;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  



## *Run*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Run(IChartDataProvider dp, string longKey, string shortKey, string revision)
```
<mark style="color:purple;">`dp`</mark> <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *Описание*  

<mark style="color:purple;">`longKey`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:purple;">`shortKey`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:purple;">`revision`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  



## *SetSettingsParam*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void SetSettingsParam(string name, object param)
```
<mark style="color:purple;">`name`</mark> <mark style="color:red;">*`string`*</mark>  
 *Описание*  

<mark style="color:purple;">`param`</mark> <mark style="color:red;">*`object`*</mark>  
 *Описание*  



## *ToString*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

# Свойства

## *Calculation*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorCalculation Calculation { get; set; }
```

## *Canvas*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IChartCanvas Canvas { get; set; }
```

## *ChartDataType*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

## *ClearData*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected bool ClearData { get; private set; }
```

## *DataProvider*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```

## *DefaultCalculation*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorCalculation DefaultCalculation { get; }
```

## *DisableRender*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool DisableRender { get; protected set; }
```

## *Helper*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorsHelper Helper { get; private set; }
```

## *ID*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```

## *IntegerValues*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool IntegerValues { get; }
```

## *IsStock*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool IsStock { get; }
```

## *Levels*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartLevel> Levels { get; set; }
```

## *Name*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```

## *Panel*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Panel { get; set; }
```

## *Panels*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<string> Panels { get; }
```

## *Series*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeries Series { get; }
```

## *SettingsLongKey*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected string SettingsLongKey { get; private set; }
```

## *SettingsShortKey*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected string SettingsShortKey { get; private set; }
```

## *ShowIndicator*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowIndicator { get; set; }
```

## *ShowIndicatorLabels*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorLabels { get; set; }
```

## *ShowIndicatorLabelsParam*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorLabelsParam { get; set; }
```

## *ShowIndicatorParam*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorParam { get; set; }
```

## *ShowIndicatorTitle*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorTitle { get; set; }
```

## *ShowIndicatorTitleParam*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorTitleParam { get; set; }
```

## *ShowIndicatorValues*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorValues { get; set; }
```

## *ShowIndicatorValuesParam*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorValuesParam { get; set; }
```

## *Title*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Title { get; }
```
# События

## *PropertyChanged*
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

