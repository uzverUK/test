# BrushObject

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[List](./)

\===

#### Синтаксис

```csharp
public sealed class BrushObject : LineObjectBase
```

## Список методов

| Название                                                | Описание |
| ------------------------------------------------------- | -------- |
| [`AddPoint`](brushobject.cs.md#method-addpoint)         | _===_    |
| [`ApplyTheme`](brushobject.cs.md#method-applytheme)     | _===_    |
| [`BrushObject`](brushobject.cs.md#method-brushobject)   | _===_    |
| [`CopyTemplate`](brushobject.cs.md#method-copytemplate) | _===_    |
| [`Draw`](brushobject.cs.md#method-draw)                 | _===_    |
| [`GetMinDist`](brushobject.cs.md#method-getmindist)     | _===_    |
| [`InObject`](brushobject.cs.md#method-inobject)         | _===_    |

## Список свойств

| Название                                                                  | Описание |
| ------------------------------------------------------------------------- | -------- |
| [`Points`](brushobject.cs.md#property-points)                             | _===_    |
| [`xsuJlZ3bylFkXacpNF53`](brushobject.cs.md#property-xsujlz3bylfkxacpnf53) | _===_    |

***

***

## Методы

### `AddPoint` <a href="#method-addpoint" id="method-addpoint"></a>

\===

```csharp
public void AddPoint(ObjectPoint op)
```

`op` _<mark style="color:red;">`ObjectPoint`</mark>_\
_===_

***

### `ApplyTheme` <a href="#method-applytheme" id="method-applytheme"></a>

\===

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` _<mark style="color:red;">`IChartTheme`</mark>_\
_===_

***

### `BrushObject` <a href="#method-brushobject" id="method-brushobject"></a>

\===

```csharp
public BrushObject()
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

### `GetMinDist` <a href="#method-getmindist" id="method-getmindist"></a>

\===

```csharp
protected override int GetMinDist(int x, int y)
```

`x` _<mark style="color:red;">`int`</mark>_\
_===_

`y` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `InObject` <a href="#method-inobject" id="method-inobject"></a>

\===

```csharp
protected override bool InObject(int x, int y)
```

***

***

***

## Свойства

### `Points` <a href="#property-points" id="property-points"></a>

\===

```csharp
public System.Collections.Generic.List<ObjectPoint> Points { get; set; }
```

***

### `xsuJlZ3bylFkXacpNF53` <a href="#property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>

\===

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***
