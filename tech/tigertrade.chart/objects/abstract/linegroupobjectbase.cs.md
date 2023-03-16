# LineGroupObjectBase

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[Abstract](./)

\===

#### Синтаксис

```csharp
public abstract class LineGroupObjectBase : LineObjectBase
```

## Список методов

| Название                                                                      | Описание |
| ----------------------------------------------------------------------------- | -------- |
| [`CalcPoint`](linegroupobjectbase.cs.md#method-calcpoint)                     | _===_    |
| [`Draw`](linegroupobjectbase.cs.md#method-draw)                               | _===_    |
| [`InObject`](linegroupobjectbase.cs.md#method-inobject)                       | _===_    |
| [`LineGroupObjectBase`](linegroupobjectbase.cs.md#method-linegroupobjectbase) | _===_    |

## Список свойств

| Название                                                          | Описание |
| ----------------------------------------------------------------- | -------- |
| [`EndPoints;`](linegroupobjectbase.cs.md#property-endpoints;)     | _===_    |
| [`StartPoints;`](linegroupobjectbase.cs.md#property-startpoints;) | _===_    |

***

***

## Методы

### `CalcPoint` <a href="#method-calcpoint" id="method-calcpoint"></a>

\===

```csharp
protected virtual void CalcPoint()
```

***

### `Draw` <a href="#method-draw" id="method-draw"></a>

\===

```csharp
protected override void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```

`visual` _<mark style="color:red;">`DxVisualQueue`</mark>_\
_===_

`List` _<mark style="color:red;">`ref`</mark>_\
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

### `LineGroupObjectBase` <a href="#method-linegroupobjectbase" id="method-linegroupobjectbase"></a>

\===

```csharp
protected LineGroupObjectBase()
```

***

***

***

## Свойства

### `EndPoints;` <a href="#property-endpoints" id="property-endpoints"></a>

\===

```csharp
protected Point[] EndPoints; {}
```

***

### `StartPoints;` <a href="#property-startpoints" id="property-startpoints"></a>

\===

```csharp
protected Point[] StartPoints; {}
```

***
