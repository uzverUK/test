# StochasticSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class StochasticSource : IndicatorSourceBase
```

## Список методов

| Название                                                             | Описание |
| -------------------------------------------------------------------- | -------- |
| [`CopySettings`](stochasticsource.cs.md#method-copysettings)         | _===_    |
| [`GetSeries`](stochasticsource.cs.md#method-getseries)               | _===_    |
| [`GetSeriesList`](stochasticsource.cs.md#method-getserieslist)       | _===_    |
| [`StochasticSource`](stochasticsource.cs.md#method-stochasticsource) | _===_    |
| [`ToString`](stochasticsource.cs.md#method-tostring)                 | _===_    |

## Список свойств

| Название                                                     | Описание |
| ------------------------------------------------------------ | -------- |
| [`FastK`](stochasticsource.cs.md#property-fastk)             | _===_    |
| [`SlowD`](stochasticsource.cs.md#property-slowd)             | _===_    |
| [`SlowDMaType`](stochasticsource.cs.md#property-slowdmatype) | _===_    |
| [`Smooth`](stochasticsource.cs.md#property-smooth)           | _===_    |

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

### `StochasticSource` <a href="#method-stochasticsource" id="method-stochasticsource"></a>

\===

```csharp
public StochasticSource()
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

### `FastK` <a href="#property-fastk" id="property-fastk"></a>

\===

```csharp
public int FastK { get; set; }
```

***

### `SlowD` <a href="#property-slowd" id="property-slowd"></a>

\===

```csharp
public int SlowD { get; set; }
```

***

### `SlowDMaType` <a href="#property-slowdmatype" id="property-slowdmatype"></a>

\===

```csharp
public IndicatorMaType SlowDMaType { get; set; }
```

***

### `Smooth` <a href="#property-smooth" id="property-smooth"></a>

\===

```csharp
public int Smooth { get; set; }
```

***
