# CumulativeDeltaSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class CumulativeDeltaSource : IndicatorSourceBase
```

## Список методов

| Название                                                                            | Описание |
| ----------------------------------------------------------------------------------- | -------- |
| [`CopySettings`](cumulativedeltasource.cs.md#method-copysettings)                   | _===_    |
| [`CumulativeDeltaSource`](cumulativedeltasource.cs.md#method-cumulativedeltasource) | _===_    |
| [`GetSeries`](cumulativedeltasource.cs.md#method-getseries)                         | _===_    |
| [`GetSeriesList`](cumulativedeltasource.cs.md#method-getserieslist)                 | _===_    |
| [`ToString`](cumulativedeltasource.cs.md#method-tostring)                           | _===_    |

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

### `CumulativeDeltaSource` <a href="#method-cumulativedeltasource" id="method-cumulativedeltasource"></a>

\===

```csharp
public CumulativeDeltaSource()
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
