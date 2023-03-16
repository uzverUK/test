# LabelObject

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[List](./)

\===

#### Синтаксис

```csharp
public sealed class LabelObject : PolygonObjectBase
```

## Список методов

| Название                                                | Описание |
| ------------------------------------------------------- | -------- |
| [`ApplyTheme`](labelobject.cs.md#method-applytheme)     | _===_    |
| [`CopyTemplate`](labelobject.cs.md#method-copytemplate) | _===_    |
| [`Draw`](labelobject.cs.md#method-draw)                 | _===_    |
| [`InObject`](labelobject.cs.md#method-inobject)         | _===_    |
| [`LabelObject`](labelobject.cs.md#method-labelobject)   | _===_    |

## Список свойств

| Название                                                                  | Описание |
| ------------------------------------------------------------------------- | -------- |
| [`FontSize`](labelobject.cs.md#property-fontsize)                         | _===_    |
| [`LabelColor`](labelobject.cs.md#property-labelcolor)                     | _===_    |
| [`LabelText`](labelobject.cs.md#property-labeltext)                       | _===_    |
| [`xsuJlZ3bylFkXacpNF53`](labelobject.cs.md#property-xsujlz3bylfkxacpnf53) | _===_    |

***

***

## Методы

### `ApplyTheme` <a href="#method-applytheme" id="method-applytheme"></a>

\===

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` _<mark style="color:red;">`IChartTheme`</mark>_\
_===_

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

### `LabelObject` <a href="#method-labelobject" id="method-labelobject"></a>

\===

```csharp
public LabelObject()
```

***

***

***

## Свойства

### `FontSize` <a href="#property-fontsize" id="property-fontsize"></a>

\===

```csharp
public int FontSize { get; set; }
```

***

### `LabelColor` <a href="#property-labelcolor" id="property-labelcolor"></a>

\===

```csharp
public XColor LabelColor { get; set; }
```

***

### `LabelText` <a href="#property-labeltext" id="property-labeltext"></a>

\===

```csharp
public string LabelText { get; set; }
```

***

### `xsuJlZ3bylFkXacpNF53` <a href="#property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>

\===

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***
