# RulerObject

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[List](./)

\===

#### Синтаксис

```csharp
public sealed class RulerObject : LineObjectBase
```

## Список методов

| Название                                                                | Описание |
| ----------------------------------------------------------------------- | -------- |
| [`ApplyTheme`](rulerobject.cs.md#method-applytheme)                     | _===_    |
| [`CopyTemplate`](rulerobject.cs.md#method-copytemplate)                 | _===_    |
| [`Draw`](rulerobject.cs.md#method-draw)                                 | _===_    |
| [`InObject`](rulerobject.cs.md#method-inobject)                         | _===_    |
| [`PrettyFormatTimeSpan`](rulerobject.cs.md#method-prettyformattimespan) | _===_    |
| [`RulerObject`](rulerobject.cs.md#method-rulerobject)                   | _===_    |

## Список свойств

| Название                                                                  | Описание |
| ------------------------------------------------------------------------- | -------- |
| [`ShowInfoAsk`](rulerobject.cs.md#property-showinfoask)                   | _===_    |
| [`ShowInfoBars`](rulerobject.cs.md#property-showinfobars)                 | _===_    |
| [`ShowInfoBid`](rulerobject.cs.md#property-showinfobid)                   | _===_    |
| [`ShowInfoChange`](rulerobject.cs.md#property-showinfochange)             | _===_    |
| [`ShowInfoDelta`](rulerobject.cs.md#property-showinfodelta)               | _===_    |
| [`ShowInfoPrice`](rulerobject.cs.md#property-showinfoprice)               | _===_    |
| [`ShowInfoTicks`](rulerobject.cs.md#property-showinfoticks)               | _===_    |
| [`ShowInfoTime`](rulerobject.cs.md#property-showinfotime)                 | _===_    |
| [`ShowInfoTrades`](rulerobject.cs.md#property-showinfotrades)             | _===_    |
| [`ShowInfoVolume`](rulerobject.cs.md#property-showinfovolume)             | _===_    |
| [`TextColor`](rulerobject.cs.md#property-textcolor)                       | _===_    |
| [`xsuJlZ3bylFkXacpNF53`](rulerobject.cs.md#property-xsujlz3bylfkxacpnf53) | _===_    |

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

### `PrettyFormatTimeSpan` <a href="#method-prettyformattimespan" id="method-prettyformattimespan"></a>

\===

```csharp
public string PrettyFormatTimeSpan(TimeSpan span)
```

`span` _<mark style="color:red;">`TimeSpan`</mark>_\
_===_

***

### `RulerObject` <a href="#method-rulerobject" id="method-rulerobject"></a>

\===

```csharp
public RulerObject()
```

***

***

***

## Свойства

### `ShowInfoAsk` <a href="#property-showinfoask" id="property-showinfoask"></a>

\===

```csharp
public bool ShowInfoAsk { get; set; }
```

***

### `ShowInfoBars` <a href="#property-showinfobars" id="property-showinfobars"></a>

\===

```csharp
public bool ShowInfoBars { get; set; }
```

***

### `ShowInfoBid` <a href="#property-showinfobid" id="property-showinfobid"></a>

\===

```csharp
public bool ShowInfoBid { get; set; }
```

***

### `ShowInfoChange` <a href="#property-showinfochange" id="property-showinfochange"></a>

\===

```csharp
public bool ShowInfoChange { get; set; }
```

***

### `ShowInfoDelta` <a href="#property-showinfodelta" id="property-showinfodelta"></a>

\===

```csharp
public bool ShowInfoDelta { get; set; }
```

***

### `ShowInfoPrice` <a href="#property-showinfoprice" id="property-showinfoprice"></a>

\===

```csharp
public bool ShowInfoPrice { get; set; }
```

***

### `ShowInfoTicks` <a href="#property-showinfoticks" id="property-showinfoticks"></a>

\===

```csharp
public bool ShowInfoTicks { get; set; }
```

***

### `ShowInfoTime` <a href="#property-showinfotime" id="property-showinfotime"></a>

\===

```csharp
public bool ShowInfoTime { get; set; }
```

***

### `ShowInfoTrades` <a href="#property-showinfotrades" id="property-showinfotrades"></a>

\===

```csharp
public bool ShowInfoTrades { get; set; }
```

***

### `ShowInfoVolume` <a href="#property-showinfovolume" id="property-showinfovolume"></a>

\===

```csharp
public bool ShowInfoVolume { get; set; }
```

***

### `TextColor` <a href="#property-textcolor" id="property-textcolor"></a>

\===

```csharp
public XColor TextColor { get; set; }
```

***

### `xsuJlZ3bylFkXacpNF53` <a href="#property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>

\===

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***
