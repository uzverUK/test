# BarsRequest

`namespace` [TigerTrade.Tc](../).[History](./)

\===

#### Синтаксис

```csharp
public sealed class BarsRequest
```

## Список методов

| Название                                              | Описание |
| ----------------------------------------------------- | -------- |
| [`BarsRequest`](barsrequest.cs.md#method-barsrequest) | _===_    |

## Список свойств

| Название                                            | Описание |
| --------------------------------------------------- | -------- |
| [`RequestID`](barsrequest.cs.md#property-requestid) | _===_    |
| [`Symbol`](barsrequest.cs.md#property-symbol)       | _===_    |
| [`TargetID`](barsrequest.cs.md#property-targetid)   | _===_    |

***

***

## Методы

### `BarsRequest` <a href="#method-barsrequest" id="method-barsrequest"></a>

\===

```csharp
public BarsRequest(Symbol symbol, string requestID, string targetID)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`requestID` _<mark style="color:red;">`string`</mark>_\
_===_

`targetID` _<mark style="color:red;">`string`</mark>_\
_===_

***

***

***

## Свойства

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
