# VerticalLineObject

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[List](./)

\===

#### Синтаксис

```csharp
public sealed class VerticalLineObject : LineObjectBase
```

## Список методов

| Название                                                                   | Описание |
| -------------------------------------------------------------------------- | -------- |
| [`CheckAlert`](verticallineobject.cs.md#method-checkalert)                 | _===_    |
| [`CopyTemplate`](verticallineobject.cs.md#method-copytemplate)             | _===_    |
| [`Draw`](verticallineobject.cs.md#method-draw)                             | _===_    |
| [`DrawControlPoints`](verticallineobject.cs.md#method-drawcontrolpoints)   | _===_    |
| [`InObject`](verticallineobject.cs.md#method-inobject)                     | _===_    |
| [`VerticalLineObject`](verticallineobject.cs.md#method-verticallineobject) | _===_    |

## Список свойств

| Название                                                                         | Описание |
| -------------------------------------------------------------------------------- | -------- |
| [`Alert`](verticallineobject.cs.md#property-alert)                               | _===_    |
| [`xsuJlZ3bylFkXacpNF53`](verticallineobject.cs.md#property-xsujlz3bylfkxacpnf53) | _===_    |

***

***

## Методы

### `CheckAlert` <a href="#method-checkalert" id="method-checkalert"></a>

\===

```csharp
public override void CheckAlert(System.Collections.Generic.List<IndicatorBase> indicators)
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

### `DrawControlPoints` <a href="#method-drawcontrolpoints" id="method-drawcontrolpoints"></a>

\===

```csharp
public override void DrawControlPoints(DxVisualQueue visual)
```

***

### `InObject` <a href="#method-inobject" id="method-inobject"></a>

\===

```csharp
protected override bool InObject(int x, int y)
```

`x` _<mark style="color:red;">`int`</mark>_\
_===_

`y` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `VerticalLineObject` <a href="#method-verticallineobject" id="method-verticallineobject"></a>

\===

```csharp
public VerticalLineObject()
```

***

***

***

## Свойства

### `Alert` <a href="#property-alert" id="property-alert"></a>

\===

```csharp
public ChartAlertSettings Alert { get; set; }
```

***

### `xsuJlZ3bylFkXacpNF53` <a href="#property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>

\===

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***
