# RSISource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class RSISource : IndicatorSourceBase
```

## Список методов

| Название                                                | Описание |
| ------------------------------------------------------- | -------- |
| [`CopySettings`](rsisource.cs.md#method-copysettings)   | _===_    |
| [`GetSeries`](rsisource.cs.md#method-getseries)         | _===_    |
| [`GetSeriesList`](rsisource.cs.md#method-getserieslist) | _===_    |
| [`RSISource`](rsisource.cs.md#method-rsisource)         | _===_    |
| [`ToString`](rsisource.cs.md#method-tostring)           | _===_    |

## Список свойств

| Название                                    | Описание |
| ------------------------------------------- | -------- |
| [`Period`](rsisource.cs.md#property-period) | _===_    |
| [`Source`](rsisource.cs.md#property-source) | _===_    |

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

### `RSISource` <a href="#method-rsisource" id="method-rsisource"></a>

\===

```csharp
public RSISource()
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
