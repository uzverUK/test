# EnvelopesSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class EnvelopesSource : IndicatorSourceBase
```

## Список методов

| Название                                                          | Описание |
| ----------------------------------------------------------------- | -------- |
| [`CopySettings`](envelopessource.cs.md#method-copysettings)       | _===_    |
| [`EnvelopesSource`](envelopessource.cs.md#method-envelopessource) | _===_    |
| [`GetSeries`](envelopessource.cs.md#method-getseries)             | _===_    |
| [`GetSeriesList`](envelopessource.cs.md#method-getserieslist)     | _===_    |
| [`ToString`](envelopessource.cs.md#method-tostring)               | _===_    |

## Список свойств

| Название                                          | Описание |
| ------------------------------------------------- | -------- |
| [`Factor`](envelopessource.cs.md#property-factor) | _===_    |
| [`MaType`](envelopessource.cs.md#property-matype) | _===_    |
| [`Period`](envelopessource.cs.md#property-period) | _===_    |
| [`Source`](envelopessource.cs.md#property-source) | _===_    |

***

***

## Методы

### `CopySettings` <a href="#method-copysettings" id="method-copysettings"></a>

\===

```csharp
public override void CopySettings(IndicatorSourceBase source)
```

`source` _<mark style="color:red;">`IndicatorSourceBase`</mark>_\
_===_

***

### `EnvelopesSource` <a href="#method-envelopessource" id="method-envelopessource"></a>

\===

```csharp
public EnvelopesSource()
```

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

### `Factor` <a href="#property-factor" id="property-factor"></a>

\===

```csharp
public int Factor { get; set; }
```

***

### `MaType` <a href="#property-matype" id="property-matype"></a>

\===

```csharp
public IndicatorMaType MaType { get; set; }
```

***

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
