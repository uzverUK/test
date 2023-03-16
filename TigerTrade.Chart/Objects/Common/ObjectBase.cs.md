
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public abstract class ObjectBase : INotifyPropertyChanged, IDynamicProperty
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddAlert`](#test) | *Описание* |
| [`ApplyTheme`](#test) | *Описание* |
| [`BeginDrag`](#test) | *Описание* |
| [`CheckAlert`](#test) | *Описание* |
| [`ControlPointEditing`](#test) | *Описание* |
| [`ControlPointsChanged`](#test) | *Описание* |
| [`CopyTemplate`](#test) | *Описание* |
| [`DragObject`](#test) | *Описание* |
| [`Draw`](#test) | *Описание* |
| [`DrawControlPoint`](#test) | *Описание* |
| [`DrawControlPoints`](#test) | *Описание* |
| [`DrawObject`](#test) | *Описание* |
| [`ExtraPointChanged`](#test) | *Описание* |
| [`GetAlerts`](#test) | *Описание* |
| [`GetControlPoint`](#test) | *Описание* |
| [`GetExtraPoint`](#test) | *Описание* |
| [`GetMinDist`](#test) | *Описание* |
| [`GetMinDistance`](#test) | *Описание* |
| [`GetPropertyHasStandardValues`](#test) | *Описание* |
| [`GetPropertyReadOnly`](#test) | *Описание* |
| [`GetPropertyStandardValues`](#test) | *Описание* |
| [`GetPropertyVisibility`](#test) | *Описание* |
| [`GetX`](#test) | *Описание* |
| [`GetY`](#test) | *Описание* |
| [`InObject`](#test) | *Описание* |
| [`IsObjectInArea`](#test) | *Описание* |
| [`IsObjectOnChart`](#test) | *Описание* |
| [`ObjectBase`](#test) | *Описание* |
| [`OnPropertyChanged`](#test) | *Описание* |
| [`Prepare`](#test) | *Описание* |
| [`SetCanvas`](#test) | *Описание* |
| [`SetDataProvider`](#test) | *Описание* |
| [`SetSettings`](#test) | *Описание* |
| [`ToPoint`](#test) | *Описание* |
| [`ToPoints`](#test) | *Описание* |
| [`ToString`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Canvas`](./ObjectBase.cs/Свойства/Canvas.md) | *Описание* |
| [`ChartDataType`](./ObjectBase.cs/Свойства/ChartDataType.md) | *Описание* |
| [`ControlPointNum`](./ObjectBase.cs/Свойства/ControlPointNum.md) | *Описание* |
| [`ControlPoints`](./ObjectBase.cs/Свойства/ControlPoints.md) | *Описание* |
| [`ControlPointsList`](./ObjectBase.cs/Свойства/ControlPointsList.md) | *Описание* |
| [`DataProvider`](./ObjectBase.cs/Свойства/DataProvider.md) | *Описание* |
| [`ID`](./ObjectBase.cs/Свойства/ID.md) | *Описание* |
| [`InMove;`](./ObjectBase.cs/Свойства/InMove;.md) | *Описание* |
| [`InSetup;`](./ObjectBase.cs/Свойства/InSetup;.md) | *Описание* |
| [`Lock`](./ObjectBase.cs/Свойства/Lock.md) | *Описание* |
| [`Name`](./ObjectBase.cs/Свойства/Name.md) | *Описание* |
| [`ObjectID`](./ObjectBase.cs/Свойства/ObjectID.md) | *Описание* |
| [`PenWidth`](./ObjectBase.cs/Свойства/PenWidth.md) | *Описание* |
| [`Periods`](./ObjectBase.cs/Свойства/Periods.md) | *Описание* |
| [`Position`](./ObjectBase.cs/Свойства/Position.md) | *Описание* |
| [`Settings`](./ObjectBase.cs/Свойства/Settings.md) | *Описание* |
| [`SnapGrid`](./ObjectBase.cs/Свойства/SnapGrid.md) | *Описание* |
| [`SymbolID`](./ObjectBase.cs/Свойства/SymbolID.md) | *Описание* |
| [`Theme`](./ObjectBase.cs/Свойства/Theme.md) | *Описание* |
| [`Title`](./ObjectBase.cs/Свойства/Title.md) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ObjectBase.cs/События/PropertyChanged.md) | *Описание* |





***  
***  
# Методы

## `AddAlert`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void AddAlert(ChartAlertSettings settings, string message)
```

`settings` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

`message` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ApplyTheme`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ApplyTheme(IChartTheme theme)
```
`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `BeginDrag`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void BeginDrag()
```

***  

## `CheckAlert`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CheckAlert(List<IndicatorBase> indicators)
```

***  

## `ControlPointEditing`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ControlPointEditing(int index)
```

`index` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `ControlPointsChanged`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ControlPointsChanged()
```

***  

## `CopyTemplate`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `DragObject`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void DragObject(double dx, double dy)
```
`dx` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`dy` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `Draw`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `DrawControlPoint`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void DrawControlPoint(DxVisualQueue visual, Point point)
```
`point` <mark style="color:red;">*`Point`*</mark>  
 *Описание*  


***  

## `DrawControlPoints`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void DrawControlPoints(DxVisualQueue visual)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `DrawObject`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void DrawObject(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```
`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `ExtraPointChanged`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void ExtraPointChanged(int index, ObjectPoint op)
```
`index` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***  

## `GetAlerts`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ChartAlertInfo> GetAlerts()
```

***  

## `GetControlPoint`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual int GetControlPoint(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetExtraPoint`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual int GetExtraPoint(int x, int y)
```

***  

## `GetMinDist`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual int GetMinDist(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetMinDistance`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int GetMinDistance(int x, int y)
```

***  

## `GetPropertyHasStandardValues`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyHasStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyReadOnly`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyReadOnly(string propertyName)
```

***  

## `GetPropertyStandardValues`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual IEnumerable<object> GetPropertyStandardValues(string propertyName)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetPropertyVisibility`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool GetPropertyVisibility(string propertyName)
```

***  

## `GetX`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetX(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetY`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double GetY(double d)
```
`d` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `InObject`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool InObject(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `IsObjectInArea`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool IsObjectInArea()
```

***  

## `IsObjectOnChart`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual bool IsObjectOnChart()
```

***  

## `ObjectBase`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected ObjectBase()
```

***  

## `OnPropertyChanged`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void OnPropertyChanged([CallerMemberName] string propertyName = null)
```

`propertyName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Prepare`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void Prepare()
```

***  

## `SetCanvas`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetCanvas(IChartCanvas canvas)
```

`canvas` <mark style="color:red;">*`IChartCanvas`*</mark>  
 *Описание*  


***  

## `SetDataProvider`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetDataProvider(IChartDataProvider dp)
```
`dp` <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *Описание*  


***  

## `SetSettings`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetSettings(IChartSettings settings)
```
`settings` <mark style="color:red;">*`IChartSettings`*</mark>  
 *Описание*  


***  

## `ToPoint`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Point ToPoint(ObjectPoint op)
```
`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***  

## `ToPoints`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] ToPoints(ObjectPoint[] ops)
```

***  

## `ToString`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Canvas`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartCanvas Canvas { get; private set; }
```  
***

## `ChartDataType`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

## `ControlPointNum`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int ControlPointNum { get; }
```  
***

## `ControlPoints`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPoint[] ControlPoints { get; set; }
```  
***

## `ControlPointsList`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPointInfo[] ControlPointsList { get; }
```  
***

## `DataProvider`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartDataProvider DataProvider { get; private set; }
```  
***

## `ID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `InMove;`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool InMove; {}
```  
***

## `InSetup;`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool InSetup; {}
```  
***

## `Lock`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Lock { get; set; }
```  
***

## `Name`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `ObjectID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ObjectID { get; set; }
```  
***

## `PenWidth`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual int PenWidth { get; }
```  
***

## `Periods`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPeriods Periods { get; set; }
```  
***

## `Position`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPosition Position { get; set; }
```  
***

## `Settings`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartSettings Settings { get; private set; }
```  
***

## `SnapGrid`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual bool SnapGrid { get; }
```  
***

## `SymbolID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SymbolID { get; set; }
```  
***

## `Theme`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected IChartTheme Theme { get; private set; }
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

