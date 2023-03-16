# BollingerBandsSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class BollingerBandsSource : IndicatorSourceBase
```

## Список методов

| Название                                                                         | Описание |
| -------------------------------------------------------------------------------- | -------- |
| [`BollingerBandsSource`](bollingerbandssource.cs.md#method-bollingerbandssource) | _===_    |
| [`CopySettings`](bollingerbandssource.cs.md#method-copysettings)                 | _===_    |
| [`GetSeries`](bollingerbandssource.cs.md#method-getseries)                       | _===_    |
| [`GetSeriesList`](bollingerbandssource.cs.md#method-getserieslist)               | _===_    |
| [`ToString`](bollingerbandssource.cs.md#method-tostring)                         | _===_    |

## Список свойств

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`MaType`](bollingerbandssource.cs.md#property-matype) | _===_    |
| [`Period`](bollingerbandssource.cs.md#property-period) | _===_    |
| [`Source`](bollingerbandssource.cs.md#property-source) | _===_    |
| [`StdDev`](bollingerbandssource.cs.md#property-stddev) | _===_    |

***

***

## Методы

### `BollingerBandsSource` <a href="#method-bollingerbandssource" id="method-bollingerbandssource"></a>

\===

```csharp
public BollingerBandsSource()
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

### `StdDev` <a href="#property-stddev" id="property-stddev"></a>

\===

```csharp
public Decimal StdDev { get; set; }
```

***
