# MomentumSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class MomentumSource : IndicatorSourceBase
```

## Список методов

| Название                                                       | Описание |
| -------------------------------------------------------------- | -------- |
| [`CopySettings`](momentumsource.cs.md#method-copysettings)     | _===_    |
| [`GetSeries`](momentumsource.cs.md#method-getseries)           | _===_    |
| [`GetSeriesList`](momentumsource.cs.md#method-getserieslist)   | _===_    |
| [`MomentumSource`](momentumsource.cs.md#method-momentumsource) | _===_    |
| [`ToString`](momentumsource.cs.md#method-tostring)             | _===_    |

## Список свойств

| Название                                         | Описание |
| ------------------------------------------------ | -------- |
| [`Period`](momentumsource.cs.md#property-period) | _===_    |
| [`Source`](momentumsource.cs.md#property-source) | _===_    |

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

### `MomentumSource` <a href="#method-momentumsource" id="method-momentumsource"></a>

\===

```csharp
public MomentumSource()
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
