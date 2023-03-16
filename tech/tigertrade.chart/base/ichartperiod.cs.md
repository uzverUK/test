# IChartPeriod

`namespace` [TigerTrade.Chart](../../../).[Base](./)

\===

#### Синтаксис

```csharp
public interface IChartPeriod
```

## Список методов

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`GetSequence`](ichartperiod.cs.md#method-getsequence) | _===_    |

## Список свойств

| Название                                           | Описание |
| -------------------------------------------------- | -------- |
| [`Interval`](ichartperiod.cs.md#property-interval) | _===_    |
| [`Type`](ichartperiod.cs.md#property-type)         | _===_    |

***

***

## Методы

### `GetSequence` <a href="#method-getsequence" id="method-getsequence"></a>

\===

```csharp
int GetSequence(ChartPeriodType type, int interval, DateTime dateTime, double timeOffset)
```

`type` _<mark style="color:red;">`ChartPeriodType`</mark>_\
_===_

`interval` _<mark style="color:red;">`int`</mark>_\
_===_

`dateTime` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`timeOffset` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `GetSequence` <a href="#method-getsequence" id="method-getsequence"></a>

\===

```csharp
int GetSequence(ChartPeriodType type, int interval, DateTime dateTime, double timeOffset)
int GetSequence(ChartPeriodType type, int interval, double dateTime, double timeOffset)
```

`type` _<mark style="color:red;">`ChartPeriodType`</mark>_\
_===_

`interval` _<mark style="color:red;">`int`</mark>_\
_===_

`dateTime` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`timeOffset` _<mark style="color:red;">`double`</mark>_\
_===_

`dateTime` _<mark style="color:red;">`double`</mark>_\
_===_

***

***

***

## Свойства

### `Interval` <a href="#property-interval" id="property-interval"></a>

\===

```csharp
int Interval { get; }
```

***

### `Type` <a href="#property-type" id="property-type"></a>

\===

```csharp
ChartPeriodType Type { get; }
```

***
