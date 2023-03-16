# StandardDeviationSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class StandardDeviationSource : IndicatorSourceBase
```

## Список методов

| Название                                                                                  | Описание |
| ----------------------------------------------------------------------------------------- | -------- |
| [`CopySettings`](standarddeviationsource.cs.md#method-copysettings)                       | _===_    |
| [`GetSeries`](standarddeviationsource.cs.md#method-getseries)                             | _===_    |
| [`GetSeriesList`](standarddeviationsource.cs.md#method-getserieslist)                     | _===_    |
| [`StandardDeviationSource`](standarddeviationsource.cs.md#method-standarddeviationsource) | _===_    |
| [`ToString`](standarddeviationsource.cs.md#method-tostring)                               | _===_    |

## Список свойств

| Название                                                  | Описание |
| --------------------------------------------------------- | -------- |
| [`Period`](standarddeviationsource.cs.md#property-period) | _===_    |
| [`Source`](standarddeviationsource.cs.md#property-source) | _===_    |

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

### `StandardDeviationSource` <a href="#method-standarddeviationsource" id="method-standarddeviationsource"></a>

\===

```csharp
public StandardDeviationSource()
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
