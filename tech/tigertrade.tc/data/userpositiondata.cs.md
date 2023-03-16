# UserPositionData

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class UserPositionData
```

## Список методов

| Название                                                       | Описание |
| -------------------------------------------------------------- | -------- |
| [`ClearPosition`](userpositiondata.cs.md#method-clearposition) | _===_    |
| [`ClosePosition`](userpositiondata.cs.md#method-closeposition) | _===_    |
| [`HidePosition`](userpositiondata.cs.md#method-hideposition)   | _===_    |

## Список свойств

| Название                                                     | Описание |
| ------------------------------------------------------------ | -------- |
| [`IsLive`](userpositiondata.cs.md#property-islive)           | _===_    |
| [`IsPlayer`](userpositiondata.cs.md#property-isplayer)       | _===_    |
| [`IsSimulator`](userpositiondata.cs.md#property-issimulator) | _===_    |

***

***

## Методы

### `ClearPosition` <a href="#method-clearposition" id="method-clearposition"></a>

\===

```csharp
public static UserPositionData ClearPosition(string connectionID, string positionID)
```

`connectionID` _<mark style="color:red;">`string`</mark>_\
_===_

`positionID` _<mark style="color:red;">`string`</mark>_\
_===_

`UserPositionData` _<mark style="color:red;">`new`</mark>_\
_===_

***

### `ClosePosition` <a href="#method-closeposition" id="method-closeposition"></a>

\===

```csharp
public static UserPositionData ClosePosition(string connectionID, string positionID)
```

***

### `HidePosition` <a href="#method-hideposition" id="method-hideposition"></a>

\===

```csharp
public static UserPositionData HidePosition(string connectionID, string positionID)
```

`connectionID` _<mark style="color:red;">`string`</mark>_\
_===_

`positionID` _<mark style="color:red;">`string`</mark>_\
_===_

`UserPositionData` _<mark style="color:red;">`new`</mark>_\
_===_

***

***

***

## Свойства

### `IsLive` <a href="#property-islive" id="property-islive"></a>

\===

```csharp
public bool IsLive { get; }
```

***

### `IsPlayer` <a href="#property-isplayer" id="property-isplayer"></a>

\===

```csharp
public bool IsPlayer { get; }
```

***

### `IsSimulator` <a href="#property-issimulator" id="property-issimulator"></a>

\===

```csharp
public bool IsSimulator { get; }
```

***
