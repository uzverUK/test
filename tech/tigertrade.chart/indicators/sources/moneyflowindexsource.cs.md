# MoneyFlowIndexSource

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Sources](./)

\===

#### Синтаксис

```csharp
public sealed class MoneyFlowIndexSource : IndicatorSourceBase
```

## Список методов

| Название                                                                         | Описание |
| -------------------------------------------------------------------------------- | -------- |
| [`CopySettings`](moneyflowindexsource.cs.md#method-copysettings)                 | _===_    |
| [`GetSeries`](moneyflowindexsource.cs.md#method-getseries)                       | _===_    |
| [`GetSeriesList`](moneyflowindexsource.cs.md#method-getserieslist)               | _===_    |
| [`MoneyFlowIndexSource`](moneyflowindexsource.cs.md#method-moneyflowindexsource) | _===_    |
| [`ToString`](moneyflowindexsource.cs.md#method-tostring)                         | _===_    |

## Список свойств

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`Period`](moneyflowindexsource.cs.md#property-period) | _===_    |

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

### `MoneyFlowIndexSource` <a href="#method-moneyflowindexsource" id="method-moneyflowindexsource"></a>

\===

```csharp
public MoneyFlowIndexSource()
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

### `Period` <a href="#property-period" id="property-period"></a>

\===

```csharp
public int Period { get; set; }
```

***
