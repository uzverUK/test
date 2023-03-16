# IndicatorSeries

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Collections](./)

\===

#### Синтаксис

```csharp
public sealed class IndicatorSeries : IEnumerable<IndicatorSeriesData>, IEnumerable
```

## Список методов

| Название                                                          | Описание |
| ----------------------------------------------------------------- | -------- |
| [`Add`](indicatorseries.cs.md#method-add)                         | _===_    |
| [`Clear`](indicatorseries.cs.md#method-clear)                     | _===_    |
| [`GetEnumerator`](indicatorseries.cs.md#method-getenumerator)     | _===_    |
| [`IndicatorSeries`](indicatorseries.cs.md#method-indicatorseries) | _===_    |

## Список свойств

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`Count`](indicatorseries.cs.md#property-count) | _===_    |

***

***

## Методы

### `Add` <a href="#method-add" id="method-add"></a>

\===

```csharp
public void Add(IndicatorSeriesData series)
```

`series` _<mark style="color:red;">`IndicatorSeriesData`</mark>_\
_===_

***

### `Add` <a href="#method-add" id="method-add"></a>

\===

```csharp
public void Add(IndicatorSeriesData series)
public void Add(IndicatorSeriesData series1, IndicatorSeriesData series2)
```

`series` _<mark style="color:red;">`IndicatorSeriesData`</mark>_\
_===_

`series1` _<mark style="color:red;">`IndicatorSeriesData`</mark>_\
_===_

`series2` _<mark style="color:red;">`IndicatorSeriesData`</mark>_\
_===_

***

### `Add` <a href="#method-add" id="method-add"></a>

\===

```csharp
public void Add(IndicatorSeriesData series)
public void Add(IndicatorSeriesData series1, IndicatorSeriesData series2)
public void Add(params IndicatorSeriesData[] series)
```

`series` _<mark style="color:red;">`IndicatorSeriesData`</mark>_\
_===_

`series1` _<mark style="color:red;">`IndicatorSeriesData`</mark>_\
_===_

`series2` _<mark style="color:red;">`IndicatorSeriesData`</mark>_\
_===_

`IndicatorSeriesData` _<mark style="color:red;">`params`</mark>_\
_===_

***

### `Clear` <a href="#method-clear" id="method-clear"></a>

\===

```csharp
public void Clear()
```

***

### `GetEnumerator` <a href="#method-getenumerator" id="method-getenumerator"></a>

\===

```csharp
public IEnumerator<IndicatorSeriesData> GetEnumerator()
```

***

### `IndicatorSeries` <a href="#method-indicatorseries" id="method-indicatorseries"></a>

\===

```csharp
public IndicatorSeries()
```

***

***

***

## Свойства

### `Count` <a href="#property-count" id="property-count"></a>

\===

```csharp
public int Count { get; }
```

***
