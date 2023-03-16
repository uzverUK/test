
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public abstract class IndicatorBase : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
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

# Список свойств
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

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./IndicatorBase.cs/События/PropertyChanged.md) | *Описание* |





***  
***  
# Методы

## `AddAlert<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void AddAlert(ChartAlertSettings settings, string message)
```

`settings` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

`message` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ApplyColors<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ApplyColors(IChartTheme palette)
```
`palette` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `CheckNeedRedraw<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool CheckNeedRedraw()
```

***  

## `CopyTemplate<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CopyTemplate(IndicatorBase indicator, bool style)
```

`indicator` <mark style="color:red;">*`IndicatorBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Execute<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract void Execute()
```

***  

## `GetAlerts<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartAlertInfo> GetAlerts()
```

***  

## `GetDistance<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual double GetDistance(double x, double y)
```

`x` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetLabels<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void GetLabels(ref List<IndicatorLabelInfo> labels)
```
`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `GetMinMax<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetMinMax(out double min, out double max)
```
`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  

`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  


***  

## `GetPoints<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] GetPoints(IndicatorSeriesData seriesData, string name = null)
```
`seriesData` <mark style="color:red;">*`IndicatorSeriesData`*</mark>  
 *Описание*  

`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyHasStandardValues<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyHasStandardValues(string propertyName)
```
`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyReadOnly<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyReadOnly(string propertyName)
```

***  

## `GetPropertyStandardValues<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyVisibility<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyVisibility(string propertyName)
```

***  

## `GetTitle<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorTitleInfo GetTitle()
```

`IndicatorTitleInfo` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `GetValues<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual List<IndicatorValueInfo> GetValues(int cursorPos)
```
`cursorPos` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetX<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetX(int i)
```
`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetY<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetY(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetY<a href="test" id="test"></a>`
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

## `IndicatorBase<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorBase()
```

***  

## `OnPropertyChanged<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `PropChanged<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void PropChanged()
```

***  

## `Render<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void Render(DxVisualQueue visual)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `Run<a href="test" id="test"></a>`
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

## `SetSettingsParam<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void SetSettingsParam(string name, object param)
```
`name` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`param` <mark style="color:red;">*`object`*</mark>  
 *Описание*  


***  

## `ToString<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Calculation`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorCalculation Calculation { get; set; }
```  
***

## `Canvas`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IChartCanvas Canvas { get; set; }
```  
***

## `ChartDataType`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

## `ClearData`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected bool ClearData { get; private set; }
```  
***

## `DataProvider`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```  
***

## `DefaultCalculation`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IndicatorCalculation DefaultCalculation { get; }
```  
***

## `DisableRender`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool DisableRender { get; protected set; }
```  
***

## `Helper`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IndicatorsHelper Helper { get; private set; }
```  
***

## `ID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `IntegerValues`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool IntegerValues { get; }
```  
***

## `IsStock`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool IsStock { get; }
```  
***

## `Levels`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartLevel> Levels { get; set; }
```  
***

## `Name`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `Panel`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Panel { get; set; }
```  
***

## `Panels`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<string> Panels { get; }
```  
***

## `Series`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorSeries Series { get; }
```  
***

## `SettingsLongKey`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected string SettingsLongKey { get; private set; }
```  
***

## `SettingsShortKey`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected string SettingsShortKey { get; private set; }
```  
***

## `ShowIndicator`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowIndicator { get; set; }
```  
***

## `ShowIndicatorLabels`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorLabels { get; set; }
```  
***

## `ShowIndicatorLabelsParam`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorLabelsParam { get; set; }
```  
***

## `ShowIndicatorParam`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorParam { get; set; }
```  
***

## `ShowIndicatorTitle`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorTitle { get; set; }
```  
***

## `ShowIndicatorTitleParam`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorTitleParam { get; set; }
```  
***

## `ShowIndicatorValues`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool ShowIndicatorValues { get; set; }
```  
***

## `ShowIndicatorValuesParam`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool? ShowIndicatorValuesParam { get; set; }
```  
***

## `Title`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Title { get; }
```  
***
***  
 ***  
# События

## `PropertyChanged`
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

