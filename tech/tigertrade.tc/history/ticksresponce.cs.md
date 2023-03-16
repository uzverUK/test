# TicksResponce

`namespace` [TigerTrade.Tc](../).[History](./)

\===

#### Синтаксис

```csharp
public sealed class TicksResponce
```

## Список методов

| Название                                                    | Описание |
| ----------------------------------------------------------- | -------- |
| [`TicksResponce`](ticksresponce.cs.md#method-ticksresponce) | _===_    |

## Список свойств

| Название                                          | Описание |
| ------------------------------------------------- | -------- |
| [`Reader`](ticksresponce.cs.md#property-reader)   | _===_    |
| [`Request`](ticksresponce.cs.md#property-request) | _===_    |

***

***

## Методы

### `TicksResponce` <a href="#method-ticksresponce" id="method-ticksresponce"></a>

\===

```csharp
public TicksResponce(TicksRequest request, IDataReader<Tick> reader)
```

`request` _<mark style="color:red;">`TicksRequest`</mark>_\
_===_

***

***

***

## Свойства

### `Reader` <a href="#property-reader" id="property-reader"></a>

\===

```csharp
public IDataReader<Tick> Reader { get; }
```

***

### `Request` <a href="#property-request" id="property-request"></a>

\===

```csharp
public TicksRequest Request { get; }
```

***
