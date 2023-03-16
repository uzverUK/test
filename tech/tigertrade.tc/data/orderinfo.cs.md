# OrderInfo

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class OrderInfo
```

## Список методов

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`OrderInfo`](orderinfo.cs.md#method-orderinfo) | _===_    |

## Список свойств

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`ErrorMsg`](orderinfo.cs.md#property-errormsg) | _===_    |
| [`Order`](orderinfo.cs.md#property-order)       | _===_    |
| [`Silent`](orderinfo.cs.md#property-silent)     | _===_    |
| [`Status`](orderinfo.cs.md#property-status)     | _===_    |

***

***

## Методы

### `OrderInfo` <a href="#method-orderinfo" id="method-orderinfo"></a>

\===

```csharp
public OrderInfo(Order order, OrderStatus status, string errorMsg = "")
```

`order` _<mark style="color:red;">`Order`</mark>_\
_===_

`status` _<mark style="color:red;">`OrderStatus`</mark>_\
_===_

`errorMsg` _<mark style="color:red;">`string`</mark>_\
_===_

***

***

***

## Свойства

### `ErrorMsg` <a href="#property-errormsg" id="property-errormsg"></a>

\===

```csharp
public string ErrorMsg { get; set; }
```

***

### `Order` <a href="#property-order" id="property-order"></a>

\===

```csharp
public Order Order { get; }
```

***

### `Silent` <a href="#property-silent" id="property-silent"></a>

\===

```csharp
public bool Silent { get; }
```

***

### `Status` <a href="#property-status" id="property-status"></a>

\===

```csharp
public OrderStatus Status { get; }
```

***
