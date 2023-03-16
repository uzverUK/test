# AOSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class AOSource : IndicatorSourceBase
```

## Список методов

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`AOSource`](aosource.cs.md#method-aosource)           | _===_    |
| [`CopySettings`](aosource.cs.md#method-copysettings)   | _===_    |
| [`GetSeries`](aosource.cs.md#method-getseries)         | _===_    |
| [`GetSeriesList`](aosource.cs.md#method-getserieslist) | _===_    |
| [`ToString`](aosource.cs.md#method-tostring)           | _===_    |

## Список свойств

| Название                                             | Описание |
| ---------------------------------------------------- | -------- |
| [`LongPeriod`](aosource.cs.md#property-longperiod)   | _===_    |
| [`MaType`](aosource.cs.md#property-matype)           | _===_    |
| [`ShortPeriod`](aosource.cs.md#property-shortperiod) | _===_    |

***

***

## Методы

### `AOSource` <a href="#method-aosource" id="method-aosource"></a>

\===

```csharp
public AOSource()
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
