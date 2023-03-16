# PriceOscillatorSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class PriceOscillatorSource : IndicatorSourceBase
```

## Список методов

| Название                                                                            | Описание |
| ----------------------------------------------------------------------------------- | -------- |
| [`CopySettings`](priceoscillatorsource.cs.md#method-copysettings)                   | _===_    |
| [`GetSeries`](priceoscillatorsource.cs.md#method-getseries)                         | _===_    |
| [`GetSeriesList`](priceoscillatorsource.cs.md#method-getserieslist)                 | _===_    |
| [`PriceOscillatorSource`](priceoscillatorsource.cs.md#method-priceoscillatorsource) | _===_    |
| [`ToString`](priceoscillatorsource.cs.md#method-tostring)                           | _===_    |

## Список свойств

| Название                                                          | Описание |
| ----------------------------------------------------------------- | -------- |
| [`LongPeriod`](priceoscillatorsource.cs.md#property-longperiod)   | _===_    |
| [`MaType`](priceoscillatorsource.cs.md#property-matype)           | _===_    |
| [`ShortPeriod`](priceoscillatorsource.cs.md#property-shortperiod) | _===_    |
| [`Source`](priceoscillatorsource.cs.md#property-source)           | _===_    |

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

### `PriceOscillatorSource` <a href="#method-priceoscillatorsource" id="method-priceoscillatorsource"></a>

\===

```csharp
public PriceOscillatorSource()
```

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

`object` _<mark style="color:red;">`new`</mark>_\
_===_

***

***

***

## Свойства

### `LongPeriod` <a href="#property-longperiod" id="property-longperiod"></a>

\===

```csharp
public int LongPeriod { get; set; }
```

***

### `MaType` <a href="#property-matype" id="property-matype"></a>

\===

```csharp
public IndicatorMaType MaType { get; set; }
```

***

### `ShortPeriod` <a href="#property-shortperiod" id="property-shortperiod"></a>

\===

```csharp
public int ShortPeriod { get; set; }
```

***

### `Source` <a href="#property-source" id="property-source"></a>

\===

```csharp
public IndicatorSourceBase Source { get; set; }
```

***
