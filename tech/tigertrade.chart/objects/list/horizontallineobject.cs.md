# HorizontalLineObject

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[List](./)

\===

#### Синтаксис

```csharp
public class HorizontalLineObject : LineObjectBase
```

## Список методов

| Название                                                                         | Описание |
| -------------------------------------------------------------------------------- | -------- |
| [`CheckAlert`](horizontallineobject.cs.md#method-checkalert)                     | _===_    |
| [`CopyTemplate`](horizontallineobject.cs.md#method-copytemplate)                 | _===_    |
| [`Draw`](horizontallineobject.cs.md#method-draw)                                 | _===_    |
| [`DrawControlPoints`](horizontallineobject.cs.md#method-drawcontrolpoints)       | _===_    |
| [`DrawText`](horizontallineobject.cs.md#method-drawtext)                         | _===_    |
| [`HorizontalLineObject`](horizontallineobject.cs.md#method-horizontallineobject) | _===_    |
| [`InObject`](horizontallineobject.cs.md#method-inobject)                         | _===_    |
| [`IsObjectOnChart`](horizontallineobject.cs.md#method-isobjectonchart)           | _===_    |

## Список свойств

| Название                                                                           | Описание |
| ---------------------------------------------------------------------------------- | -------- |
| [`Alert`](horizontallineobject.cs.md#property-alert)                               | _===_    |
| [`AlertMinDistance`](horizontallineobject.cs.md#property-alertmindistance)         | _===_    |
| [`FontSize`](horizontallineobject.cs.md#property-fontsize)                         | _===_    |
| [`LineRect;`](horizontallineobject.cs.md#property-linerect;)                       | _===_    |
| [`Price`](horizontallineobject.cs.md#property-price)                               | _===_    |
| [`Text`](horizontallineobject.cs.md#property-text)                                 | _===_    |
| [`TextAlignment`](horizontallineobject.cs.md#property-textalignment)               | _===_    |
| [`xsuJlZ3bylFkXacpNF53`](horizontallineobject.cs.md#property-xsujlz3bylfkxacpnf53) | _===_    |

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

### `DrawText` <a href="#method-drawtext" id="method-drawtext"></a>

\===

```csharp
protected void DrawText(DxVisualQueue visual)
```

`visual` _<mark style="color:red;">`DxVisualQueue`</mark>_\
_===_

***

### `HorizontalLineObject` <a href="#method-horizontallineobject" id="method-horizontallineobject"></a>

\===

```csharp
public HorizontalLineObject()
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

### `IsObjectOnChart` <a href="#method-isobjectonchart" id="method-isobjectonchart"></a>

\===

```csharp
protected override bool IsObjectOnChart()
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

### `FontSize` <a href="#property-fontsize" id="property-fontsize"></a>

\===

```csharp
public int FontSize { get; set; }
```

***

### `LineRect;` <a href="#property-linerect" id="property-linerect"></a>

\===

```csharp
protected Rect LineRect; {}
```

***

### `Price` <a href="#property-price" id="property-price"></a>

\===

```csharp
public Decimal Price { get; set; }
```

***

### `Text` <a href="#property-text" id="property-text"></a>

\===

```csharp
public string Text { get; set; }
```

***

### `TextAlignment` <a href="#property-textalignment" id="property-textalignment"></a>

\===

```csharp
public ObjectTextAlignment TextAlignment { get; set; }
```

***

### `xsuJlZ3bylFkXacpNF53` <a href="#property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>

\===

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***
