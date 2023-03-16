# BarsResponce

`namespace` [TigerTrade.Tc](../).[History](./)

\===

#### Синтаксис

```csharp
public sealed class BarsResponce
```

## Список методов

| Название                                                 | Описание |
| -------------------------------------------------------- | -------- |
| [`BarsResponce`](barsresponce.cs.md#method-barsresponce) | _===_    |

## Список свойств

| Название                                         | Описание |
| ------------------------------------------------ | -------- |
| [`Reader`](barsresponce.cs.md#property-reader)   | _===_    |
| [`Request`](barsresponce.cs.md#property-request) | _===_    |

***

***

## Методы

### `BarsResponce` <a href="#method-barsresponce" id="method-barsresponce"></a>

\===

```csharp
public BarsResponce(BarsRequest request, IDataReader<Bar> reader)
```

`request` _<mark style="color:red;">`BarsRequest`</mark>_\
_===_

***

***

***

## Свойства

### `Reader` <a href="#property-reader" id="property-reader"></a>

\===

```csharp
public IDataReader<Bar> Reader { get; }
```

***

### `Request` <a href="#property-request" id="property-request"></a>

\===

```csharp
public BarsRequest Request { get; }
```

***
