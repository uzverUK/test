# CMOSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class CMOSource : IndicatorSourceBase
```

## Список методов

| Название                                                | Описание |
| ------------------------------------------------------- | -------- |
| [`CMOSource`](cmosource.cs.md#method-cmosource)         | _===_    |
| [`CopySettings`](cmosource.cs.md#method-copysettings)   | _===_    |
| [`GetSeries`](cmosource.cs.md#method-getseries)         | _===_    |
| [`GetSeriesList`](cmosource.cs.md#method-getserieslist) | _===_    |
| [`ToString`](cmosource.cs.md#method-tostring)           | _===_    |

## Список свойств

| Название                                    | Описание |
| ------------------------------------------- | -------- |
| [`Period`](cmosource.cs.md#property-period) | _===_    |
| [`Source`](cmosource.cs.md#property-source) | _===_    |

***

***

## Методы

### `CMOSource` <a href="#method-cmosource" id="method-cmosource"></a>

\===

```csharp
public CMOSource()
```

***

### `CopySettings` <a href="#method-copysettings" id="method-copysettings"></a>

\===

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

`source` _<mark style="color:red;">`IndicatorSourceBase`</mark>_\
_===_

***

### `GetSeries` <a href="#method-getseries" id="method-getseries"></a>

\===

```csharp
public override double[] GetSeries(IndicatorsHelper helper)
```

`helper` _<mark style="color:red;">`IndicatorsHelper`</mark>_\
_===_

***

### `GetSeriesList` <a href="#method-getserieslist" id="method-getserieslist"></a>

\===

```csharp
public override IEnumerable<string> GetSeriesList()
```

`List` _<mark style="color:red;">`new`</mark>_\
_===_

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

***

***

***

## Свойства

### `Period` <a href="#property-period" id="property-period"></a>

\===

```csharp
public int Period { get; set; }
```

***

### `Source` <a href="#property-source" id="property-source"></a>

\===

```csharp
public IndicatorSourceBase Source { get; set; }
```

***
