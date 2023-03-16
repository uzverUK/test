# EldersForceIndexSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class EldersForceIndexSource : IndicatorSourceBase
```

## Список методов

| Название                                                                               | Описание |
| -------------------------------------------------------------------------------------- | -------- |
| [`CopySettings`](eldersforceindexsource.cs.md#method-copysettings)                     | _===_    |
| [`EldersForceIndexSource`](eldersforceindexsource.cs.md#method-eldersforceindexsource) | _===_    |
| [`GetSeries`](eldersforceindexsource.cs.md#method-getseries)                           | _===_    |
| [`GetSeriesList`](eldersforceindexsource.cs.md#method-getserieslist)                   | _===_    |
| [`ToString`](eldersforceindexsource.cs.md#method-tostring)                             | _===_    |

## Список свойств

| Название                                                 | Описание |
| -------------------------------------------------------- | -------- |
| [`MaType`](eldersforceindexsource.cs.md#property-matype) | _===_    |
| [`Period`](eldersforceindexsource.cs.md#property-period) | _===_    |
| [`Source`](eldersforceindexsource.cs.md#property-source) | _===_    |

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

### `EldersForceIndexSource` <a href="#method-eldersforceindexsource" id="method-eldersforceindexsource"></a>

\===

```csharp
public EldersForceIndexSource()
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
