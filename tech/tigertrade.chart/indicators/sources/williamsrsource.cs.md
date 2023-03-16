# WilliamsRSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class WilliamsRSource : IndicatorSourceBase
```

## Список методов

| Название                                                          | Описание |
| ----------------------------------------------------------------- | -------- |
| [`CopySettings`](williamsrsource.cs.md#method-copysettings)       | _===_    |
| [`GetSeries`](williamsrsource.cs.md#method-getseries)             | _===_    |
| [`GetSeriesList`](williamsrsource.cs.md#method-getserieslist)     | _===_    |
| [`ToString`](williamsrsource.cs.md#method-tostring)               | _===_    |
| [`WilliamsRSource`](williamsrsource.cs.md#method-williamsrsource) | _===_    |

## Список свойств

| Название                                          | Описание |
| ------------------------------------------------- | -------- |
| [`Period`](williamsrsource.cs.md#property-period) | _===_    |

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

### `WilliamsRSource` <a href="#method-williamsrsource" id="method-williamsrsource"></a>

\===

```csharp
public WilliamsRSource()
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
