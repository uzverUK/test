# FibonacciRetracementObject

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[List](./)

\===

#### Синтаксис

```csharp
public sealed class FibonacciRetracementObject : LineObjectBase
```

## Список методов

| Название                                                                                           | Описание |
| -------------------------------------------------------------------------------------------------- | -------- |
| [`ApplyTheme`](fibonacciretracementobject.cs.md#method-applytheme)                                 | _===_    |
| [`CopyTemplate`](fibonacciretracementobject.cs.md#method-copytemplate)                             | _===_    |
| [`Draw`](fibonacciretracementobject.cs.md#method-draw)                                             | _===_    |
| [`FibonacciRetracementObject`](fibonacciretracementobject.cs.md#method-fibonacciretracementobject) | _===_    |
| [`InObject`](fibonacciretracementobject.cs.md#method-inobject)                                     | _===_    |

## Список свойств

| Название                                                                                 | Описание |
| ---------------------------------------------------------------------------------------- | -------- |
| [`CustomLevels`](fibonacciretracementobject.cs.md#property-customlevels)                 | _===_    |
| [`Levels`](fibonacciretracementobject.cs.md#property-levels)                             | _===_    |
| [`OpenEnd`](fibonacciretracementobject.cs.md#property-openend)                           | _===_    |
| [`OpenStart`](fibonacciretracementobject.cs.md#property-openstart)                       | _===_    |
| [`TextAlignment`](fibonacciretracementobject.cs.md#property-textalignment)               | _===_    |
| [`xsuJlZ3bylFkXacpNF53`](fibonacciretracementobject.cs.md#property-xsujlz3bylfkxacpnf53) | _===_    |

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

### `FibonacciRetracementObject` <a href="#method-fibonacciretracementobject" id="method-fibonacciretracementobject"></a>

\===

```csharp
public FibonacciRetracementObject()
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

### `CustomLevels` <a href="#property-customlevels" id="property-customlevels"></a>

\===

```csharp
public bool CustomLevels { get; set; }
```

***

### `Levels` <a href="#property-levels" id="property-levels"></a>

\===

```csharp
public System.Collections.Generic.List<ObjectLine> Levels { get; set; }
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
