# VolumeOscillatorSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class VolumeOscillatorSource : IndicatorSourceBase
```

## Список методов

| Название                                                                               | Описание |
| -------------------------------------------------------------------------------------- | -------- |
| [`CopySettings`](volumeoscillatorsource.cs.md#method-copysettings)                     | _===_    |
| [`GetSeries`](volumeoscillatorsource.cs.md#method-getseries)                           | _===_    |
| [`GetSeriesList`](volumeoscillatorsource.cs.md#method-getserieslist)                   | _===_    |
| [`ToString`](volumeoscillatorsource.cs.md#method-tostring)                             | _===_    |
| [`VolumeOscillatorSource`](volumeoscillatorsource.cs.md#method-volumeoscillatorsource) | _===_    |

## Список свойств

| Название                                                           | Описание |
| ------------------------------------------------------------------ | -------- |
| [`LongPeriod`](volumeoscillatorsource.cs.md#property-longperiod)   | _===_    |
| [`MaType`](volumeoscillatorsource.cs.md#property-matype)           | _===_    |
| [`ShortPeriod`](volumeoscillatorsource.cs.md#property-shortperiod) | _===_    |

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

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

***

### `VolumeOscillatorSource` <a href="#method-volumeoscillatorsource" id="method-volumeoscillatorsource"></a>

\===

```csharp
public VolumeOscillatorSource()
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
