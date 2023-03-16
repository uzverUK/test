# ADSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class ADSource : IndicatorSourceBase
```

## Список методов

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`ADSource`](adsource.cs.md#method-adsource)           | _===_    |
| [`CopySettings`](adsource.cs.md#method-copysettings)   | _===_    |
| [`GetSeries`](adsource.cs.md#method-getseries)         | _===_    |
| [`GetSeriesList`](adsource.cs.md#method-getserieslist) | _===_    |
| [`ToString`](adsource.cs.md#method-tostring)           | _===_    |

***

***

## Методы

### `ADSource` <a href="#method-adsource" id="method-adsource"></a>

\===

```csharp
public ADSource()
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
