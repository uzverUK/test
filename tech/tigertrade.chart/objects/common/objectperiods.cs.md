# ObjectPeriods

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[Common](./)

\===

#### Синтаксис

```csharp
public sealed class ObjectPeriods
```

## Список методов

| Название                                                    | Описание |
| ----------------------------------------------------------- | -------- |
| [`CheckPeriod`](objectperiods.cs.md#method-checkperiod)     | _===_    |
| [`Copy`](objectperiods.cs.md#method-copy)                   | _===_    |
| [`Equals`](objectperiods.cs.md#method-equals)               | _===_    |
| [`ObjectPeriods`](objectperiods.cs.md#method-objectperiods) | _===_    |
| [`Update`](objectperiods.cs.md#method-update)               | _===_    |

## Список свойств

| Название                                          | Описание |
| ------------------------------------------------- | -------- |
| [`Periods`](objectperiods.cs.md#property-periods) | _===_    |

***

***

## Методы

### `CheckPeriod` <a href="#method-checkperiod" id="method-checkperiod"></a>

\===

```csharp
public bool CheckPeriod(IChartPeriod dc)
```

`dc` _<mark style="color:red;">`IChartPeriod`</mark>_\
_===_

***

### `Copy` <a href="#method-copy" id="method-copy"></a>

\===

```csharp
public ObjectPeriods Copy()
```

***

### `Equals` <a href="#method-equals" id="method-equals"></a>

\===

```csharp
public override bool Equals(object obj)
```

`obj` _<mark style="color:red;">`object`</mark>_\
_===_

***

### `ObjectPeriods` <a href="#method-objectperiods" id="method-objectperiods"></a>

\===

```csharp
public ObjectPeriods()
```

***

### `Update` <a href="#method-update" id="method-update"></a>

\===

```csharp
public void Update(string type, bool isChecked, bool checkRange, int min, int max)
```

`type` _<mark style="color:red;">`string`</mark>_\
_===_

`isChecked` _<mark style="color:red;">`bool`</mark>_\
_===_

`checkRange` _<mark style="color:red;">`bool`</mark>_\
_===_

`min` _<mark style="color:red;">`int`</mark>_\
_===_

`max` _<mark style="color:red;">`int`</mark>_\
_===_

***

***

***

## Свойства

### `Periods` <a href="#property-periods" id="property-periods"></a>

\===

```csharp
public Dictionary<string, ObjectPeriodItem> Periods { get; set; }
```

***
