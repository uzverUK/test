# KeltnerChannelSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class KeltnerChannelSource : IndicatorSourceBase
```

## Список методов

| Название                                                                         | Описание |
| -------------------------------------------------------------------------------- | -------- |
| [`CopySettings`](keltnerchannelsource.cs.md#method-copysettings)                 | _===_    |
| [`GetSeries`](keltnerchannelsource.cs.md#method-getseries)                       | _===_    |
| [`GetSeriesList`](keltnerchannelsource.cs.md#method-getserieslist)               | _===_    |
| [`KeltnerChannelSource`](keltnerchannelsource.cs.md#method-keltnerchannelsource) | _===_    |
| [`ToString`](keltnerchannelsource.cs.md#method-tostring)                         | _===_    |

## Список свойств

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`Factor`](keltnerchannelsource.cs.md#property-factor) | _===_    |
| [`MaType`](keltnerchannelsource.cs.md#property-matype) | _===_    |
| [`Period`](keltnerchannelsource.cs.md#property-period) | _===_    |
| [`Source`](keltnerchannelsource.cs.md#property-source) | _===_    |

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

### `KeltnerChannelSource` <a href="#method-keltnerchannelsource" id="method-keltnerchannelsource"></a>

\===

```csharp
public KeltnerChannelSource()
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
