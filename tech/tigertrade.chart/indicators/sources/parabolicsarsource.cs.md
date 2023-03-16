# ParabolicSARSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class ParabolicSARSource : IndicatorSourceBase
```

## Список методов

| Название                                                                   | Описание |
| -------------------------------------------------------------------------- | -------- |
| [`CopySettings`](parabolicsarsource.cs.md#method-copysettings)             | _===_    |
| [`GetSeries`](parabolicsarsource.cs.md#method-getseries)                   | _===_    |
| [`GetSeriesList`](parabolicsarsource.cs.md#method-getserieslist)           | _===_    |
| [`ParabolicSARSource`](parabolicsarsource.cs.md#method-parabolicsarsource) | _===_    |
| [`ToString`](parabolicsarsource.cs.md#method-tostring)                     | _===_    |

## Список свойств

| Название                                         | Описание |
| ------------------------------------------------ | -------- |
| [`Max`](parabolicsarsource.cs.md#property-max)   | _===_    |
| [`Step`](parabolicsarsource.cs.md#property-step) | _===_    |

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

### `ParabolicSARSource` <a href="#method-parabolicsarsource" id="method-parabolicsarsource"></a>

\===

```csharp
public ParabolicSARSource()
```

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

`string` _<mark style="color:red;">`new`</mark>_\
_===_

***

***

***

## Свойства

### `Max` <a href="#property-max" id="property-max"></a>

\===

```csharp
public Decimal Max { get; set; }
```

***

### `Step` <a href="#property-step" id="property-step"></a>

\===

```csharp
public Decimal Step { get; set; }
```

***
