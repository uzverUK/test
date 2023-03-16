# ChaikinOscillatorSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class ChaikinOscillatorSource : IndicatorSourceBase
```

## Список методов

| Название                                                                                  | Описание |
| ----------------------------------------------------------------------------------------- | -------- |
| [`ChaikinOscillatorSource`](chaikinoscillatorsource.cs.md#method-chaikinoscillatorsource) | _===_    |
| [`CopySettings`](chaikinoscillatorsource.cs.md#method-copysettings)                       | _===_    |
| [`GetSeries`](chaikinoscillatorsource.cs.md#method-getseries)                             | _===_    |
| [`GetSeriesList`](chaikinoscillatorsource.cs.md#method-getserieslist)                     | _===_    |
| [`ToString`](chaikinoscillatorsource.cs.md#method-tostring)                               | _===_    |

## Список свойств

| Название                                                            | Описание |
| ------------------------------------------------------------------- | -------- |
| [`LongPeriod`](chaikinoscillatorsource.cs.md#property-longperiod)   | _===_    |
| [`MaType`](chaikinoscillatorsource.cs.md#property-matype)           | _===_    |
| [`ShortPeriod`](chaikinoscillatorsource.cs.md#property-shortperiod) | _===_    |

***

***

## Методы

### `ChaikinOscillatorSource` <a href="#method-chaikinoscillatorsource" id="method-chaikinoscillatorsource"></a>

\===

```csharp
public ChaikinOscillatorSource()
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
