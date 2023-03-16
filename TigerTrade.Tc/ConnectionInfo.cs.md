
`namespace` [TigerTrade.Tc](../TigerTrade.Tc.md)


===

### Синтаксис
```csharp
public sealed class ConnectionInfo : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`SetLogsPath`](#method-setlogspath) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AllowConnect`](#property-allowconnect) | *===* |
| [`AllowMarketData`](#property-allowmarketdata) | *===* |
| [`AutoConnect`](#property-autoconnect) | *===* |
| [`ConnectState`](#property-connectstate) | *===* |
| [`ConnectionID`](#property-connectionid) | *===* |
| [`ConnectionName`](#property-connectionname) | *===* |
| [`HasProxy`](#property-hasproxy) | *===* |
| [`Indicator`](#property-indicator) | *===* |
| [`IsConnected`](#property-isconnected) | *===* |
| [`IsConnecting`](#property-isconnecting) | *===* |
| [`LedBrush`](#property-ledbrush) | *===* |
| [`MarketData`](#property-marketdata) | *===* |
| [`MarketType`](#property-markettype) | *===* |
| [`Proxy`](#property-proxy) | *===* |
| [`Simulator`](#property-simulator) | *===* |
| [`TradeClientExtra`](#property-tradeclientextra) | *===* |
| [`TradeClientID`](#property-tradeclientid) | *===* |
| [`TradeClientName`](#property-tradeclientname) | *===* |
| [`Trust`](#property-trust) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *===* |





***  
***  
# Методы

## `SetLogsPath`<a href="method-setlogspath" id="method-setlogspath"></a>
===
```csharp
public void SetLogsPath(string path)
```

`path` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
===
```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `AllowConnect`<a href="property-allowconnect" id="property-allowconnect"></a>
===
```csharp
public bool AllowConnect { get; set; }
```  
***

## `AllowMarketData`<a href="property-allowmarketdata" id="property-allowmarketdata"></a>
===
```csharp
public bool AllowMarketData { get; set; }
```  
***

## `AutoConnect`<a href="property-autoconnect" id="property-autoconnect"></a>
===
```csharp
public bool AutoConnect { get; set; }
```  
***

## `ConnectState`<a href="property-connectstate" id="property-connectstate"></a>
===
```csharp
public bool ConnectState { get; set; }
```  
***

## `ConnectionID`<a href="property-connectionid" id="property-connectionid"></a>
===
```csharp
public string ConnectionID { get; }
```  
***

## `ConnectionName`<a href="property-connectionname" id="property-connectionname"></a>
===
```csharp
public string ConnectionName { get; set; }
```  
***

## `HasProxy`<a href="property-hasproxy" id="property-hasproxy"></a>
===
```csharp
public bool HasProxy { get; }
```  
***

## `Indicator`<a href="property-indicator" id="property-indicator"></a>
===
```csharp
public int Indicator { get; set; }
```  
***

## `IsConnected`<a href="property-isconnected" id="property-isconnected"></a>
===
```csharp
public bool IsConnected { get; set; }
```  
***

## `IsConnecting`<a href="property-isconnecting" id="property-isconnecting"></a>
===
```csharp
public bool IsConnecting { get; set; }
```  
***

## `LedBrush`<a href="property-ledbrush" id="property-ledbrush"></a>
===
```csharp
public Brush LedBrush { get; }
```  
***

## `MarketData`<a href="property-marketdata" id="property-marketdata"></a>
===
```csharp
public bool MarketData { get; set; }
```  
***

## `MarketType`<a href="property-markettype" id="property-markettype"></a>
===
```csharp
public string MarketType { get; set; }
```  
***

## `Proxy`<a href="property-proxy" id="property-proxy"></a>
===
```csharp
public IfcHC6wbAs8uUIsvBmdJ Proxy { get; set; }
```  
***

## `Simulator`<a href="property-simulator" id="property-simulator"></a>
===
```csharp
public bool Simulator { get; }
```  
***

## `TradeClientExtra`<a href="property-tradeclientextra" id="property-tradeclientextra"></a>
===
```csharp
public string TradeClientExtra { get; }
```  
***

## `TradeClientID`<a href="property-tradeclientid" id="property-tradeclientid"></a>
===
```csharp
public string TradeClientID { get; }
```  
***

## `TradeClientName`<a href="property-tradeclientname" id="property-tradeclientname"></a>
===
```csharp
public string TradeClientName { get; }
```  
***

## `Trust`<a href="property-trust" id="property-trust"></a>
===
```csharp
public bool Trust { get; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

