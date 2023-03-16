# IconObject

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[List](./)

\===

#### Синтаксис

```csharp
public class IconObject : ObjectBase
```

## Список методов

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`ApplyTheme`](iconobject.cs.md#method-applytheme)     | _===_    |
| [`CopyTemplate`](iconobject.cs.md#method-copytemplate) | _===_    |
| [`Draw`](iconobject.cs.md#method-draw)                 | _===_    |
| [`IconObject`](iconobject.cs.md#method-iconobject)     | _===_    |
| [`InObject`](iconobject.cs.md#method-inobject)         | _===_    |

## Список свойств

| Название                                                                 | Описание |
| ------------------------------------------------------------------------ | -------- |
| [`Brush`](iconobject.cs.md#property-brush)                               | _===_    |
| [`Color`](iconobject.cs.md#property-color)                               | _===_    |
| [`Icon`](iconobject.cs.md#property-icon)                                 | _===_    |
| [`Size`](iconobject.cs.md#property-size)                                 | _===_    |
| [`xsuJlZ3bylFkXacpNF53`](iconobject.cs.md#property-xsujlz3bylfkxacpnf53) | _===_    |

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

### `IconObject` <a href="#method-iconobject" id="method-iconobject"></a>

\===

```csharp
public IconObject()
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

***

***

## Свойства

### `Brush` <a href="#property-brush" id="property-brush"></a>

\===

```csharp
protected XBrush Brush { get; private set; }
```

***

### `Color` <a href="#property-color" id="property-color"></a>

\===

```csharp
public XColor Color { get; set; }
```

***

### `Icon` <a href="#property-icon" id="property-icon"></a>

\===

```csharp
public string Icon { get; set; }
```

***

### `Size` <a href="#property-size" id="property-size"></a>

\===

```csharp
public int Size { get; set; }
```

***

### `xsuJlZ3bylFkXacpNF53` <a href="#property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>

\===

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***
