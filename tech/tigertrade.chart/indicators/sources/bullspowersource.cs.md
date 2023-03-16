# BullsPowerSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class BullsPowerSource : IndicatorSourceBase
```

## Список методов

| Название                                                             | Описание |
| -------------------------------------------------------------------- | -------- |
| [`BullsPowerSource`](bullspowersource.cs.md#method-bullspowersource) | _===_    |
| [`CopySettings`](bullspowersource.cs.md#method-copysettings)         | _===_    |
| [`GetSeries`](bullspowersource.cs.md#method-getseries)               | _===_    |
| [`GetSeriesList`](bullspowersource.cs.md#method-getserieslist)       | _===_    |
| [`ToString`](bullspowersource.cs.md#method-tostring)                 | _===_    |

## Список свойств

| Название                                           | Описание |
| -------------------------------------------------- | -------- |
| [`Period`](bullspowersource.cs.md#property-period) | _===_    |

***

***

## Методы

### `BullsPowerSource` <a href="#method-bullspowersource" id="method-bullspowersource"></a>

\===

```csharp
public BullsPowerSource()
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
