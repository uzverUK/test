# ObjectLabelInfo

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[Common](./)

\===

#### Синтаксис

```csharp
public sealed class ObjectLabelInfo
```

## Список методов

| Название                                                          | Описание |
| ----------------------------------------------------------------- | -------- |
| [`ObjectLabelInfo`](objectlabelinfo.cs.md#method-objectlabelinfo) | _===_    |

## Список свойств

| Название                                              | Описание |
| ----------------------------------------------------- | -------- |
| [`Color`](objectlabelinfo.cs.md#property-color)       | _===_    |
| [`Extanded`](objectlabelinfo.cs.md#property-extanded) | _===_    |
| [`Position`](objectlabelinfo.cs.md#property-position) | _===_    |
| [`Value`](objectlabelinfo.cs.md#property-value)       | _===_    |
| [`Y1`](objectlabelinfo.cs.md#property-y1)             | _===_    |
| [`Y2`](objectlabelinfo.cs.md#property-y2)             | _===_    |

***

***

## Методы

### `ObjectLabelInfo` <a href="#method-objectlabelinfo" id="method-objectlabelinfo"></a>

\===

```csharp
public ObjectLabelInfo(double value, XColor color, double? position = null)
```

`value` _<mark style="color:red;">`double`</mark>_\
_===_

`color` _<mark style="color:red;">`XColor`</mark>_\
_===_

***

### `ObjectLabelInfo` <a href="#method-objectlabelinfo" id="method-objectlabelinfo"></a>

\===

```csharp
public ObjectLabelInfo(double value, XColor color, double? position = null)
public ObjectLabelInfo(double value, double y1, double y2, XColor color)
```

`value` _<mark style="color:red;">`double`</mark>_\
_===_

`color` _<mark style="color:red;">`XColor`</mark>_\
_===_

`y1` _<mark style="color:red;">`double`</mark>_\
_===_

`y2` _<mark style="color:red;">`double`</mark>_\
_===_

***

***

***

## Свойства

### `Color` <a href="#property-color" id="property-color"></a>

\===

```csharp
public XColor Color { get; }
```

***

### `Extanded` <a href="#property-extanded" id="property-extanded"></a>

\===

```csharp
public bool Extanded { get; }
```

***

### `Position` <a href="#property-position" id="property-position"></a>

\===

```csharp
public double? Position { get; }
```

***

### `Value` <a href="#property-value" id="property-value"></a>

\===

```csharp
public double Value { get; }
```

***

### `Y1` <a href="#property-y1" id="property-y1"></a>

\===

```csharp
public double Y1 { get; }
```

***

### `Y2` <a href="#property-y2" id="property-y2"></a>

\===

```csharp
public double Y2 { get; }
```

***
