# ACSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class ACSource : IndicatorSourceBase
```

## Список методов

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`ACSource`](acsource.cs.md#method-acsource)           | _===_    |
| [`CopySettings`](acsource.cs.md#method-copysettings)   | _===_    |
| [`GetSeries`](acsource.cs.md#method-getseries)         | _===_    |
| [`GetSeriesList`](acsource.cs.md#method-getserieslist) | _===_    |
| [`ToString`](acsource.cs.md#method-tostring)           | _===_    |

## Список свойств

| Название                                             | Описание |
| ---------------------------------------------------- | -------- |
| [`LongPeriod`](acsource.cs.md#property-longperiod)   | _===_    |
| [`MaType`](acsource.cs.md#property-matype)           | _===_    |
| [`ShortPeriod`](acsource.cs.md#property-shortperiod) | _===_    |

***

***

## Методы

### `ACSource` <a href="#method-acsource" id="method-acsource"></a>

\===

```csharp
public ACSource()
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
