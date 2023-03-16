# RateOfChangeSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class RateOfChangeSource : IndicatorSourceBase
```

## Список методов

| Название                                                                   | Описание |
| -------------------------------------------------------------------------- | -------- |
| [`CopySettings`](rateofchangesource.cs.md#method-copysettings)             | _===_    |
| [`GetSeries`](rateofchangesource.cs.md#method-getseries)                   | _===_    |
| [`GetSeriesList`](rateofchangesource.cs.md#method-getserieslist)           | _===_    |
| [`RateOfChangeSource`](rateofchangesource.cs.md#method-rateofchangesource) | _===_    |
| [`ToString`](rateofchangesource.cs.md#method-tostring)                     | _===_    |

## Список свойств

| Название                                             | Описание |
| ---------------------------------------------------- | -------- |
| [`Period`](rateofchangesource.cs.md#property-period) | _===_    |
| [`Source`](rateofchangesource.cs.md#property-source) | _===_    |

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

### `RateOfChangeSource` <a href="#method-rateofchangesource" id="method-rateofchangesource"></a>

\===

```csharp
public RateOfChangeSource()
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
