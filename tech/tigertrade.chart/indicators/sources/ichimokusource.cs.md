# IchimokuSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class IchimokuSource : IndicatorSourceBase
```

## Список методов

| Название                                                       | Описание |
| -------------------------------------------------------------- | -------- |
| [`CopySettings`](ichimokusource.cs.md#method-copysettings)     | _===_    |
| [`GetSeries`](ichimokusource.cs.md#method-getseries)           | _===_    |
| [`GetSeriesList`](ichimokusource.cs.md#method-getserieslist)   | _===_    |
| [`IchimokuSource`](ichimokusource.cs.md#method-ichimokusource) | _===_    |
| [`ToString`](ichimokusource.cs.md#method-tostring)             | _===_    |

## Список свойств

| Название                                           | Описание |
| -------------------------------------------------- | -------- |
| [`Period1`](ichimokusource.cs.md#property-period1) | _===_    |
| [`Period2`](ichimokusource.cs.md#property-period2) | _===_    |
| [`Period3`](ichimokusource.cs.md#property-period3) | _===_    |
| [`Period4`](ichimokusource.cs.md#property-period4) | _===_    |
| [`Period5`](ichimokusource.cs.md#property-period5) | _===_    |

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

### `IchimokuSource` <a href="#method-ichimokusource" id="method-ichimokusource"></a>

\===

```csharp
public IchimokuSource()
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

### `Period4` <a href="#property-period4" id="property-period4"></a>

\===

```csharp
public int Period4 { get; set; }
```

***

### `Period5` <a href="#property-period5" id="property-period5"></a>

\===

```csharp
public int Period5 { get; set; }
```

***
