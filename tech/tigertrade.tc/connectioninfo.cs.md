# ConnectionInfo

`namespace` [TigerTrade.Tc](./)

\===

#### Синтаксис

```csharp
public sealed class ConnectionInfo : INotifyPropertyChanged
```

## Список методов

| Название                                                 | Описание |
| -------------------------------------------------------- | -------- |
| [`SetLogsPath`](connectioninfo.cs.md#method-setlogspath) | _===_    |
| [`ToString`](connectioninfo.cs.md#method-tostring)       | _===_    |

## Список свойств

| Название                                                             | Описание |
| -------------------------------------------------------------------- | -------- |
| [`AllowConnect`](connectioninfo.cs.md#property-allowconnect)         | _===_    |
| [`AllowMarketData`](connectioninfo.cs.md#property-allowmarketdata)   | _===_    |
| [`AutoConnect`](connectioninfo.cs.md#property-autoconnect)           | _===_    |
| [`ConnectState`](connectioninfo.cs.md#property-connectstate)         | _===_    |
| [`ConnectionID`](connectioninfo.cs.md#property-connectionid)         | _===_    |
| [`ConnectionName`](connectioninfo.cs.md#property-connectionname)     | _===_    |
| [`HasProxy`](connectioninfo.cs.md#property-hasproxy)                 | _===_    |
| [`Indicator`](connectioninfo.cs.md#property-indicator)               | _===_    |
| [`IsConnected`](connectioninfo.cs.md#property-isconnected)           | _===_    |
| [`IsConnecting`](connectioninfo.cs.md#property-isconnecting)         | _===_    |
| [`LedBrush`](connectioninfo.cs.md#property-ledbrush)                 | _===_    |
| [`MarketData`](connectioninfo.cs.md#property-marketdata)             | _===_    |
| [`MarketType`](connectioninfo.cs.md#property-markettype)             | _===_    |
| [`Proxy`](connectioninfo.cs.md#property-proxy)                       | _===_    |
| [`Simulator`](connectioninfo.cs.md#property-simulator)               | _===_    |
| [`TradeClientExtra`](connectioninfo.cs.md#property-tradeclientextra) | _===_    |
| [`TradeClientID`](connectioninfo.cs.md#property-tradeclientid)       | _===_    |
| [`TradeClientName`](connectioninfo.cs.md#property-tradeclientname)   | _===_    |
| [`Trust`](connectioninfo.cs.md#property-trust)                       | _===_    |

## Список событий

| Название                                                        | Описание |
| --------------------------------------------------------------- | -------- |
| [`PropertyChanged`](connectioninfo.cs.md#event-propertychanged) | _===_    |

***

***

## Методы

### `SetLogsPath` <a href="#method-setlogspath" id="method-setlogspath"></a>

\===

```csharp
public void SetLogsPath(string path)
```

`path` _<mark style="color:red;">`string`</mark>_\
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

### `AllowConnect` <a href="#property-allowconnect" id="property-allowconnect"></a>

\===

```csharp
public bool AllowConnect { get; set; }
```

***

### `AllowMarketData` <a href="#property-allowmarketdata" id="property-allowmarketdata"></a>

\===

```csharp
public bool AllowMarketData { get; set; }
```

***

### `AutoConnect` <a href="#property-autoconnect" id="property-autoconnect"></a>

\===

```csharp
public bool AutoConnect { get; set; }
```

***

### `ConnectState` <a href="#property-connectstate" id="property-connectstate"></a>

\===

```csharp
public bool ConnectState { get; set; }
```

***

### `ConnectionID` <a href="#property-connectionid" id="property-connectionid"></a>

\===

```csharp
public string ConnectionID { get; }
```

***

### `ConnectionName` <a href="#property-connectionname" id="property-connectionname"></a>

\===

```csharp
public string ConnectionName { get; set; }
```

***

### `HasProxy` <a href="#property-hasproxy" id="property-hasproxy"></a>

\===

```csharp
public bool HasProxy { get; }
```

***

### `Indicator` <a href="#property-indicator" id="property-indicator"></a>

\===

```csharp
public int Indicator { get; set; }
```

***

### `IsConnected` <a href="#property-isconnected" id="property-isconnected"></a>

\===

```csharp
public bool IsConnected { get; set; }
```

***

### `IsConnecting` <a href="#property-isconnecting" id="property-isconnecting"></a>

\===

```csharp
public bool IsConnecting { get; set; }
```

***

### `LedBrush` <a href="#property-ledbrush" id="property-ledbrush"></a>

\===

```csharp
public Brush LedBrush { get; }
```

***

### `MarketData` <a href="#property-marketdata" id="property-marketdata"></a>

\===

```csharp
public bool MarketData { get; set; }
```

***

### `MarketType` <a href="#property-markettype" id="property-markettype"></a>

\===

```csharp
public string MarketType { get; set; }
```

***

### `Proxy` <a href="#property-proxy" id="property-proxy"></a>

\===

```csharp
public IfcHC6wbAs8uUIsvBmdJ Proxy { get; set; }
```

***

### `Simulator` <a href="#property-simulator" id="property-simulator"></a>

\===

```csharp
public bool Simulator { get; }
```

***

### `TradeClientExtra` <a href="#property-tradeclientextra" id="property-tradeclientextra"></a>

\===

```csharp
public string TradeClientExtra { get; }
```

***

### `TradeClientID` <a href="#property-tradeclientid" id="property-tradeclientid"></a>

\===

```csharp
public string TradeClientID { get; }
```

***

### `TradeClientName` <a href="#property-tradeclientname" id="property-tradeclientname"></a>

\===

```csharp
public string TradeClientName { get; }
```

***

### `Trust` <a href="#property-trust" id="property-trust"></a>

\===

```csharp
public bool Trust { get; }
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
