# ChaikinsVolatilitySource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class ChaikinsVolatilitySource : IndicatorSourceBase
```

## Список методов

| Название                                                                                     | Описание |
| -------------------------------------------------------------------------------------------- | -------- |
| [`ChaikinsVolatilitySource`](chaikinsvolatilitysource.cs.md#method-chaikinsvolatilitysource) | _===_    |
| [`CopySettings`](chaikinsvolatilitysource.cs.md#method-copysettings)                         | _===_    |
| [`GetSeries`](chaikinsvolatilitysource.cs.md#method-getseries)                               | _===_    |
| [`GetSeriesList`](chaikinsvolatilitysource.cs.md#method-getserieslist)                       | _===_    |
| [`ToString`](chaikinsvolatilitysource.cs.md#method-tostring)                                 | _===_    |

## Список свойств

| Название                                                   | Описание |
| ---------------------------------------------------------- | -------- |
| [`MaType`](chaikinsvolatilitysource.cs.md#property-matype) | _===_    |
| [`Period`](chaikinsvolatilitysource.cs.md#property-period) | _===_    |

***

***

## Методы

### `ChaikinsVolatilitySource` <a href="#method-chaikinsvolatilitysource" id="method-chaikinsvolatilitysource"></a>

\===

```csharp
public ChaikinsVolatilitySource()
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

### `MaType` <a href="#property-matype" id="property-matype"></a>

\===

```csharp
public IndicatorMaType MaType { get; set; }
```

***

### `Period` <a href="#property-period" id="property-period"></a>

\===

```csharp
public int Period { get; set; }
```

***
