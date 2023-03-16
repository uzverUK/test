# TicksRequest

`namespace` [TigerTrade.Tc](../).[History](./)

\===

#### Синтаксис

```csharp
public sealed class TicksRequest
```

## Список методов

| Название                                                 | Описание |
| -------------------------------------------------------- | -------- |
| [`TicksRequest`](ticksrequest.cs.md#method-ticksrequest) | _===_    |

## Список свойств

| Название                                               | Описание |
| ------------------------------------------------------ | -------- |
| [`CustomData`](ticksrequest.cs.md#property-customdata) | _===_    |
| [`RequestID`](ticksrequest.cs.md#property-requestid)   | _===_    |
| [`Symbol`](ticksrequest.cs.md#property-symbol)         | _===_    |
| [`TargetID`](ticksrequest.cs.md#property-targetid)     | _===_    |

***

***

## Методы

### `TicksRequest` <a href="#method-ticksrequest" id="method-ticksrequest"></a>

\===

```csharp
public TicksRequest(Symbol symbol, string requestID, string targetID, bool customData)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`requestID` _<mark style="color:red;">`string`</mark>_\
_===_

`targetID` _<mark style="color:red;">`string`</mark>_\
_===_

`customData` _<mark style="color:red;">`bool`</mark>_\
_===_

***

***

***

## Свойства

### `CustomData` <a href="#property-customdata" id="property-customdata"></a>

\===

```csharp
public bool CustomData { get; set; }
```

***

### `RequestID` <a href="#property-requestid" id="property-requestid"></a>

\===

```csharp
public string RequestID { get; set; }
```

***

### `Symbol` <a href="#property-symbol" id="property-symbol"></a>

\===

```csharp
public Symbol Symbol { get; set; }
```

***

### `TargetID` <a href="#property-targetid" id="property-targetid"></a>

\===

```csharp
public string TargetID { get; }
```

***
