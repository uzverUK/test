# LinearRegressionObject

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[List](./)

\===

#### Синтаксис

```csharp
public sealed class LinearRegressionObject : LineGroupObjectBaseEx
```

## Список методов

| Название                                                                               | Описание |
| -------------------------------------------------------------------------------------- | -------- |
| [`CalcPoint`](linearregressionobject.cs.md#method-calcpoint)                           | _===_    |
| [`CopyTemplate`](linearregressionobject.cs.md#method-copytemplate)                     | _===_    |
| [`Draw`](linearregressionobject.cs.md#method-draw)                                     | _===_    |
| [`LinearRegressionObject`](linearregressionobject.cs.md#method-linearregressionobject) | _===_    |

## Список свойств

| Название                                                                             | Описание |
| ------------------------------------------------------------------------------------ | -------- |
| [`CenterLine`](linearregressionobject.cs.md#property-centerline)                     | _===_    |
| [`DownLine`](linearregressionobject.cs.md#property-downline)                         | _===_    |
| [`Percentage`](linearregressionobject.cs.md#property-percentage)                     | _===_    |
| [`RegressionType`](linearregressionobject.cs.md#property-regressiontype)             | _===_    |
| [`ShowAuxLine`](linearregressionobject.cs.md#property-showauxline)                   | _===_    |
| [`UpLine`](linearregressionobject.cs.md#property-upline)                             | _===_    |
| [`xsuJlZ3bylFkXacpNF53`](linearregressionobject.cs.md#property-xsujlz3bylfkxacpnf53) | _===_    |

***

***

## Методы

### `CalcPoint` <a href="#method-calcpoint" id="method-calcpoint"></a>

\===

```csharp
protected override void CalcPoint()
```

***

### `CopyTemplate` <a href="#method-copytemplate" id="method-copytemplate"></a>

\===

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` _<mark style="color:red;">`ObjectBase`</mark>_\
_===_

`style` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `Draw` <a href="#method-draw" id="method-draw"></a>

\===

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```

`visual` _<mark style="color:red;">`DxVisualQueue`</mark>_\
_===_

`System` _<mark style="color:red;">`ref`</mark>_\
_===_

***

### `LinearRegressionObject` <a href="#method-linearregressionobject" id="method-linearregressionobject"></a>

\===

```csharp
public LinearRegressionObject()
```

***

***

***

## Свойства

### `CenterLine` <a href="#property-centerline" id="property-centerline"></a>

\===

```csharp
public bool CenterLine { get; set; }
```

***

### `DownLine` <a href="#property-downline" id="property-downline"></a>

\===

```csharp
public bool DownLine { get; set; }
```

***

### `Percentage` <a href="#property-percentage" id="property-percentage"></a>

\===

```csharp
public double Percentage { get; set; }
```

***

### `RegressionType` <a href="#property-regressiontype" id="property-regressiontype"></a>

\===

```csharp
public RegressionType RegressionType { get; set; }
```

***

### `ShowAuxLine` <a href="#property-showauxline" id="property-showauxline"></a>

\===

```csharp
public bool ShowAuxLine { get; set; }
```

***

### `UpLine` <a href="#property-upline" id="property-upline"></a>

\===

```csharp
public bool UpLine { get; set; }
```

***

### `xsuJlZ3bylFkXacpNF53` <a href="#property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>

\===

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***
