# ElliottWaveObject

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[List](./)

\===

#### Синтаксис

```csharp
public abstract class ElliottWaveObject : LineObjectBase
```

## Список методов

| Название                                                                | Описание |
| ----------------------------------------------------------------------- | -------- |
| [`CopyTemplate`](elliottwaveobject.cs.md#method-copytemplate)           | _===_    |
| [`Draw`](elliottwaveobject.cs.md#method-draw)                           | _===_    |
| [`ElliottWaveObject`](elliottwaveobject.cs.md#method-elliottwaveobject) | _===_    |
| [`GetDegreeText`](elliottwaveobject.cs.md#method-getdegreetext)         | _===_    |
| [`InObject`](elliottwaveobject.cs.md#method-inobject)                   | _===_    |

## Список свойств

| Название                                                                        | Описание |
| ------------------------------------------------------------------------------- | -------- |
| [`Degree`](elliottwaveobject.cs.md#property-degree)                             | _===_    |
| [`ShowWave`](elliottwaveobject.cs.md#property-showwave)                         | _===_    |
| [`xsuJlZ3bylFkXacpNF53`](elliottwaveobject.cs.md#property-xsujlz3bylfkxacpnf53) | _===_    |

***

***

## Методы

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

### `ElliottWaveObject` <a href="#method-elliottwaveobject" id="method-elliottwaveobject"></a>

\===

```csharp
protected ElliottWaveObject()
```

***

### `GetDegreeText` <a href="#method-getdegreetext" id="method-getdegreetext"></a>

\===

```csharp
protected abstract string GetDegreeText(int num)
```

`num` _<mark style="color:red;">`int`</mark>_\
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

***

***

## Свойства

### `Degree` <a href="#property-degree" id="property-degree"></a>

\===

```csharp
public ElliottWaveDegree Degree { get; set; }
```

***

### `ShowWave` <a href="#property-showwave" id="property-showwave"></a>

\===

```csharp
public bool ShowWave { get; set; }
```

***

### `xsuJlZ3bylFkXacpNF53` <a href="#property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>

\===

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

***
