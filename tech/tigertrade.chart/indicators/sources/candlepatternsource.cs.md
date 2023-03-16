# CandlePatternSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class CandlePatternSource : IndicatorSourceBase
```

## Список методов

| Название                                                                      | Описание |
| ----------------------------------------------------------------------------- | -------- |
| [`CandlePatternSource`](candlepatternsource.cs.md#method-candlepatternsource) | _===_    |
| [`CopySettings`](candlepatternsource.cs.md#method-copysettings)               | _===_    |
| [`GetSeries`](candlepatternsource.cs.md#method-getseries)                     | _===_    |
| [`GetSeriesList`](candlepatternsource.cs.md#method-getserieslist)             | _===_    |
| [`SearchPattern`](candlepatternsource.cs.md#method-searchpattern)             | _===_    |
| [`ToString`](candlepatternsource.cs.md#method-tostring)                       | _===_    |

## Список свойств

| Название                                                        | Описание |
| --------------------------------------------------------------- | -------- |
| [`PatternType`](candlepatternsource.cs.md#property-patterntype) | _===_    |
| [`Penetration`](candlepatternsource.cs.md#property-penetration) | _===_    |

***

***

## Методы

### `CandlePatternSource` <a href="#method-candlepatternsource" id="method-candlepatternsource"></a>

\===

```csharp
public CandlePatternSource()
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

### `SearchPattern` <a href="#method-searchpattern" id="method-searchpattern"></a>

\===

```csharp
public double[] SearchPattern(IndicatorsHelper helper, CandlePatternSourcePatternType type)
```

`helper` _<mark style="color:red;">`IndicatorsHelper`</mark>_\
_===_

`type` _<mark style="color:red;">`CandlePatternSourcePatternType`</mark>_\
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

### `PatternType` <a href="#property-patterntype" id="property-patterntype"></a>

\===

```csharp
public CandlePatternSourcePatternType PatternType { get; set; }
```

***

### `Penetration` <a href="#property-penetration" id="property-penetration"></a>

\===

```csharp
public double Penetration { get; set; }
```

***
