# BearsPowerSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class BearsPowerSource : IndicatorSourceBase
```

## Список методов

| Название                                                             | Описание |
| -------------------------------------------------------------------- | -------- |
| [`BearsPowerSource`](bearspowersource.cs.md#method-bearspowersource) | _===_    |
| [`CopySettings`](bearspowersource.cs.md#method-copysettings)         | _===_    |
| [`GetSeries`](bearspowersource.cs.md#method-getseries)               | _===_    |
| [`GetSeriesList`](bearspowersource.cs.md#method-getserieslist)       | _===_    |
| [`ToString`](bearspowersource.cs.md#method-tostring)                 | _===_    |

## Список свойств

| Название                                           | Описание |
| -------------------------------------------------- | -------- |
| [`Period`](bearspowersource.cs.md#property-period) | _===_    |

***

***

## Методы

### `BearsPowerSource` <a href="#method-bearspowersource" id="method-bearspowersource"></a>

\===

```csharp
public BearsPowerSource()
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

### `Period` <a href="#property-period" id="property-period"></a>

\===

```csharp
public int Period { get; set; }
```

***
