# MASource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class MASource : IndicatorSourceBase
```

## Список методов

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`CopySettings`](masource.cs.md#method-copysettings)   | _===_    |
| [`GetSeries`](masource.cs.md#method-getseries)         | _===_    |
| [`GetSeriesList`](masource.cs.md#method-getserieslist) | _===_    |
| [`MASource`](masource.cs.md#method-masource)           | _===_    |
| [`ToString`](masource.cs.md#method-tostring)           | _===_    |

## Список свойств

| Название                                   | Описание |
| ------------------------------------------ | -------- |
| [`MaType`](masource.cs.md#property-matype) | _===_    |
| [`Period`](masource.cs.md#property-period) | _===_    |
| [`Source`](masource.cs.md#property-source) | _===_    |

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

### `MASource` <a href="#method-masource" id="method-masource"></a>

\===

```csharp
public MASource()
```

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
