# IChartDataProvider

`namespace` [TigerTrade.Chart](../../../).[Data](./)

\===

#### Синтаксис

```csharp
public interface IChartDataProvider
```

## Список методов

| Название                                                                 | Описание |
| ------------------------------------------------------------------------ | -------- |
| [`GetCluster`](ichartdataprovider.cs.md#method-getcluster)               | _===_    |
| [`GetMarketDepth`](ichartdataprovider.cs.md#method-getmarketdepth)       | _===_    |
| [`GetRawCluster`](ichartdataprovider.cs.md#method-getrawcluster)         | _===_    |
| [`GetRawMarketDepth`](ichartdataprovider.cs.md#method-getrawmarketdepth) | _===_    |
| [`GetRawSecurity`](ichartdataprovider.cs.md#method-getrawsecurity)       | _===_    |
| [`GetSecurity`](ichartdataprovider.cs.md#method-getsecurity)             | _===_    |

## Список свойств

| Название                                             | Описание |
| ---------------------------------------------------- | -------- |
| [`Count`](ichartdataprovider.cs.md#property-count)   | _===_    |
| [`Period`](ichartdataprovider.cs.md#property-period) | _===_    |
| [`Scale`](ichartdataprovider.cs.md#property-scale)   | _===_    |
| [`Step`](ichartdataprovider.cs.md#property-step)     | _===_    |
| [`Symbol`](ichartdataprovider.cs.md#property-symbol) | _===_    |

***

***

## Методы

### `GetCluster` <a href="#method-getcluster" id="method-getcluster"></a>

\===

```csharp
IChartCluster GetCluster(int i)
```

`i` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `GetMarketDepth` <a href="#method-getmarketdepth" id="method-getmarketdepth"></a>

\===

```csharp
IChartMarketDepth GetMarketDepth()
```

***

### `GetRawCluster` <a href="#method-getrawcluster" id="method-getrawcluster"></a>

\===

```csharp
IRawCluster GetRawCluster(int i)
```

`i` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `GetRawMarketDepth` <a href="#method-getrawmarketdepth" id="method-getrawmarketdepth"></a>

\===

```csharp
IRawMarketDepth GetRawMarketDepth()
```

***

### `GetRawSecurity` <a href="#method-getrawsecurity" id="method-getrawsecurity"></a>

\===

```csharp
IRawSecurity GetRawSecurity()
```

***

### `GetSecurity` <a href="#method-getsecurity" id="method-getsecurity"></a>

\===

```csharp
IChartSecurity GetSecurity()
```

***

***

***

## Свойства

### `Count` <a href="#property-count" id="property-count"></a>

\===

```csharp
int Count { get; }
```

***

### `Period` <a href="#property-period" id="property-period"></a>

\===

```csharp
IChartPeriod Period { get; }
```

***

### `Scale` <a href="#property-scale" id="property-scale"></a>

\===

```csharp
int Scale { get; }
```

***

### `Step` <a href="#property-step" id="property-step"></a>

\===

```csharp
double Step { get; }
```

***

### `Symbol` <a href="#property-symbol" id="property-symbol"></a>

\===

```csharp
IChartSymbol Symbol { get; }
```

***
