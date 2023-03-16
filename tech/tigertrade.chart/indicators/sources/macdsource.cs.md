# MACDSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class MACDSource : IndicatorSourceBase
```

## Список методов

| Название                                                 | Описание |
| -------------------------------------------------------- | -------- |
| [`CopySettings`](macdsource.cs.md#method-copysettings)   | _===_    |
| [`GetSeries`](macdsource.cs.md#method-getseries)         | _===_    |
| [`GetSeriesList`](macdsource.cs.md#method-getserieslist) | _===_    |
| [`MACDSource`](macdsource.cs.md#method-macdsource)       | _===_    |
| [`ToString`](macdsource.cs.md#method-tostring)           | _===_    |

## Список свойств

| Название                                     | Описание |
| -------------------------------------------- | -------- |
| [`Fast`](macdsource.cs.md#property-fast)     | _===_    |
| [`Signal`](macdsource.cs.md#property-signal) | _===_    |
| [`Slow`](macdsource.cs.md#property-slow)     | _===_    |
| [`Source`](macdsource.cs.md#property-source) | _===_    |

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

### `MACDSource` <a href="#method-macdsource" id="method-macdsource"></a>

\===

```csharp
public MACDSource()
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

### `Fast` <a href="#property-fast" id="property-fast"></a>

\===

```csharp
public int Fast { get; set; }
```

***

### `Signal` <a href="#property-signal" id="property-signal"></a>

\===

```csharp
public int Signal { get; set; }
```

***

### `Slow` <a href="#property-slow" id="property-slow"></a>

\===

```csharp
public int Slow { get; set; }
```

***

### `Source` <a href="#property-source" id="property-source"></a>

\===

```csharp
public IndicatorSourceBase Source { get; set; }
```

***
