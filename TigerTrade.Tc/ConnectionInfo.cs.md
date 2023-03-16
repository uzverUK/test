
`namespace` [TigerTrade.Tc](../TigerTrade.Tc.md)


Описание

### Синтаксис
```csharp
public sealed class ConnectionInfo : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`SetLogsPath`](#method-setlogspath) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AllowConnect`](#property-allowconnect) | *Описание* |
| [`AllowMarketData`](#property-allowmarketdata) | *Описание* |
| [`AutoConnect`](#property-autoconnect) | *Описание* |
| [`ConnectState`](#property-connectstate) | *Описание* |
| [`ConnectionID`](#property-connectionid) | *Описание* |
| [`ConnectionName`](#property-connectionname) | *Описание* |
| [`HasProxy`](#property-hasproxy) | *Описание* |
| [`Indicator`](#property-indicator) | *Описание* |
| [`IsConnected`](#property-isconnected) | *Описание* |
| [`IsConnecting`](#property-isconnecting) | *Описание* |
| [`LedBrush`](#property-ledbrush) | *Описание* |
| [`MarketData`](#property-marketdata) | *Описание* |
| [`MarketType`](#property-markettype) | *Описание* |
| [`Proxy`](#property-proxy) | *Описание* |
| [`Simulator`](#property-simulator) | *Описание* |
| [`TradeClientExtra`](#property-tradeclientextra) | *Описание* |
| [`TradeClientID`](#property-tradeclientid) | *Описание* |
| [`TradeClientName`](#property-tradeclientname) | *Описание* |
| [`Trust`](#property-trust) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *Описание* |





***  
***  
# Методы

## `SetLogsPath`<a href="method-setlogspath" id="method-setlogspath"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetLogsPath(string path)
```

`path` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `AllowConnect`<a href="property-allowconnect" id="property-allowconnect"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool AllowConnect { get; set; }
```  
***

## `AllowMarketData`<a href="property-allowmarketdata" id="property-allowmarketdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool AllowMarketData { get; set; }
```  
***

## `AutoConnect`<a href="property-autoconnect" id="property-autoconnect"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool AutoConnect { get; set; }
```  
***

## `ConnectState`<a href="property-connectstate" id="property-connectstate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ConnectState { get; set; }
```  
***

## `ConnectionID`<a href="property-connectionid" id="property-connectionid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionID { get; }
```  
***

## `ConnectionName`<a href="property-connectionname" id="property-connectionname"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionName { get; set; }
```  
***

## `HasProxy`<a href="property-hasproxy" id="property-hasproxy"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool HasProxy { get; }
```  
***

## `Indicator`<a href="property-indicator" id="property-indicator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Indicator { get; set; }
```  
***

## `IsConnected`<a href="property-isconnected" id="property-isconnected"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsConnected { get; set; }
```  
***

## `IsConnecting`<a href="property-isconnecting" id="property-isconnecting"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsConnecting { get; set; }
```  
***

## `LedBrush`<a href="property-ledbrush" id="property-ledbrush"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Brush LedBrush { get; }
```  
***

## `MarketData`<a href="property-marketdata" id="property-marketdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool MarketData { get; set; }
```  
***

## `MarketType`<a href="property-markettype" id="property-markettype"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string MarketType { get; set; }
```  
***

## `Proxy`<a href="property-proxy" id="property-proxy"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IfcHC6wbAs8uUIsvBmdJ Proxy { get; set; }
```  
***

## `Simulator`<a href="property-simulator" id="property-simulator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Simulator { get; }
```  
***

## `TradeClientExtra`<a href="property-tradeclientextra" id="property-tradeclientextra"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TradeClientExtra { get; }
```  
***

## `TradeClientID`<a href="property-tradeclientid" id="property-tradeclientid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TradeClientID { get; }
```  
***

## `TradeClientName`<a href="property-tradeclientname" id="property-tradeclientname"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TradeClientName { get; }
```  
***

## `Trust`<a href="property-trust" id="property-trust"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Trust { get; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

