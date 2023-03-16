# ObjectPointInfo

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[Common](./)

\===

#### Синтаксис

```csharp
public sealed class ObjectPointInfo : INotifyPropertyChanged
```

## Список методов

| Название                                                          | Описание |
| ----------------------------------------------------------------- | -------- |
| [`ObjectPointInfo`](objectpointinfo.cs.md#method-objectpointinfo) | _===_    |
| [`ToString`](objectpointinfo.cs.md#method-tostring)               | _===_    |

## Список свойств

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`Price`](objectpointinfo.cs.md#property-price) | _===_    |
| [`Time`](objectpointinfo.cs.md#property-time)   | _===_    |

## Список событий

| Название                                                         | Описание |
| ---------------------------------------------------------------- | -------- |
| [`PropertyChanged`](objectpointinfo.cs.md#event-propertychanged) | _===_    |

***

***

## Методы

### `ObjectPointInfo` <a href="#method-objectpointinfo" id="method-objectpointinfo"></a>

\===

```csharp
public ObjectPointInfo(ObjectPoint[] points, int index)
```

`index` _<mark style="color:red;">`int`</mark>_\
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

### `Price` <a href="#property-price" id="property-price"></a>

\===

```csharp
public double Price { get; set; }
```

***

### `Time` <a href="#property-time" id="property-time"></a>

\===

```csharp
public DateTime Time { get; set; }
```

***

***

***

## События

### `PropertyChanged` <a href="#event-propertychanged" id="event-propertychanged"></a>

\===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```
