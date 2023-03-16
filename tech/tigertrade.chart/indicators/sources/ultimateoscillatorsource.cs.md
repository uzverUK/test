# UltimateOscillatorSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class UltimateOscillatorSource : IndicatorSourceBase
```

## Список методов

| Название                                                                                     | Описание |
| -------------------------------------------------------------------------------------------- | -------- |
| [`CopySettings`](ultimateoscillatorsource.cs.md#method-copysettings)                         | _===_    |
| [`GetSeries`](ultimateoscillatorsource.cs.md#method-getseries)                               | _===_    |
| [`GetSeriesList`](ultimateoscillatorsource.cs.md#method-getserieslist)                       | _===_    |
| [`ToString`](ultimateoscillatorsource.cs.md#method-tostring)                                 | _===_    |
| [`UltimateOscillatorSource`](ultimateoscillatorsource.cs.md#method-ultimateoscillatorsource) | _===_    |

## Список свойств

| Название                                                     | Описание |
| ------------------------------------------------------------ | -------- |
| [`Period1`](ultimateoscillatorsource.cs.md#property-period1) | _===_    |
| [`Period2`](ultimateoscillatorsource.cs.md#property-period2) | _===_    |
| [`Period3`](ultimateoscillatorsource.cs.md#property-period3) | _===_    |

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

### `UltimateOscillatorSource` <a href="#method-ultimateoscillatorsource" id="method-ultimateoscillatorsource"></a>

\===

```csharp
public UltimateOscillatorSource()
```

***

***

***

## Свойства

### `Period1` <a href="#property-period1" id="property-period1"></a>

\===

```csharp
public int Period1 { get; set; }
```

***

### `Period2` <a href="#property-period2" id="property-period2"></a>

\===

```csharp
public int Period2 { get; set; }
```

***

### `Period3` <a href="#property-period3" id="property-period3"></a>

\===

```csharp
public int Period3 { get; set; }
```

***
