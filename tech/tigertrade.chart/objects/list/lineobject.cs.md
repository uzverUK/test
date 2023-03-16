# LineObject

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[List](./)

\===

#### Синтаксис

```csharp
public sealed class LineObject : LineObjectBase
```

## Список методов

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`CheckAlert`](lineobject.cs.md#method-checkalert)     | _===_    |
| [`CopyTemplate`](lineobject.cs.md#method-copytemplate) | _===_    |
| [`Draw`](lineobject.cs.md#method-draw)                 | _===_    |
| [`InObject`](lineobject.cs.md#method-inobject)         | _===_    |
| [`LineObject`](lineobject.cs.md#method-lineobject)     | _===_    |

## Список свойств

| Название                                                                 | Описание |
| ------------------------------------------------------------------------ | -------- |
| [`Alert`](lineobject.cs.md#property-alert)                               | _===_    |
| [`AlertMinDistance`](lineobject.cs.md#property-alertmindistance)         | _===_    |
| [`OpenEnd`](lineobject.cs.md#property-openend)                           | _===_    |
| [`OpenStart`](lineobject.cs.md#property-openstart)                       | _===_    |
| [`RefPoint`](lineobject.cs.md#property-refpoint)                         | _===_    |
| [`xsuJlZ3bylFkXacpNF53`](lineobject.cs.md#property-xsujlz3bylfkxacpnf53) | _===_    |

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

### `LineObject` <a href="#method-lineobject" id="method-lineobject"></a>

\===

```csharp
public LineObject()
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

### `AlertMinDistance` <a href="#property-alertmindistance" id="property-alertmindistance"></a>

\===

```csharp
public int AlertMinDistance { get; set; }
```

***

### `OpenEnd` <a href="#property-openend" id="property-openend"></a>

\===

```csharp
public bool OpenEnd { get; set; }
```

***

### `OpenStart` <a href="#property-openstart" id="property-openstart"></a>

\===

```csharp
public bool OpenStart { get; set; }
```

***

### `RefPoint` <a href="#property-refpoint" id="property-refpoint"></a>

\===

```csharp
public ObjectPoint? RefPoint { get; set; }
```

***

### `xsuJlZ3bylFkXacpNF53` <a href="#property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>

\===

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***
