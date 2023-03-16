
`namespace` [TigerTrade.Tc](../TigerTrade.Tc.md)


Описание

### Синтаксис
```csharp
public sealed class ConnectionInfo : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`SetLogsPath`](#SetLogsPath-m) | *Описание* |
| [`ToString`](#ToString-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AllowConnect`](#AllowConnect-p) | *Описание* |
| [`AllowMarketData`](#AllowMarketData-p) | *Описание* |
| [`AutoConnect`](#AutoConnect-p) | *Описание* |
| [`ConnectState`](#ConnectState-p) | *Описание* |
| [`ConnectionID`](#ConnectionID-p) | *Описание* |
| [`ConnectionName`](#ConnectionName-p) | *Описание* |
| [`HasProxy`](#HasProxy-p) | *Описание* |
| [`Indicator`](#Indicator-p) | *Описание* |
| [`IsConnected`](#IsConnected-p) | *Описание* |
| [`IsConnecting`](#IsConnecting-p) | *Описание* |
| [`LedBrush`](#LedBrush-p) | *Описание* |
| [`MarketData`](#MarketData-p) | *Описание* |
| [`MarketType`](#MarketType-p) | *Описание* |
| [`Proxy`](#Proxy-p) | *Описание* |
| [`Simulator`](#Simulator-p) | *Описание* |
| [`TradeClientExtra`](#TradeClientExtra-p) | *Описание* |
| [`TradeClientID`](#TradeClientID-p) | *Описание* |
| [`TradeClientName`](#TradeClientName-p) | *Описание* |
| [`Trust`](#Trust-p) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#PropertyChanged-p) | *Описание* |





***  
***  
# Методы

## `SetLogsPath`<a href="SetLogsPath-m" id="SetLogsPath-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetLogsPath(string path)
```

`path` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ToString`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `AllowConnect`<a href="AllowConnect-p" id="AllowConnect-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool AllowConnect { get; set; }
```  
***

## `AllowMarketData`<a href="AllowMarketData-p" id="AllowMarketData-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool AllowMarketData { get; set; }
```  
***

## `AutoConnect`<a href="AutoConnect-p" id="AutoConnect-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool AutoConnect { get; set; }
```  
***

## `ConnectState`<a href="ConnectState-p" id="ConnectState-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ConnectState { get; set; }
```  
***

## `ConnectionID`<a href="ConnectionID-p" id="ConnectionID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionID { get; }
```  
***

## `ConnectionName`<a href="ConnectionName-p" id="ConnectionName-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionName { get; set; }
```  
***

## `HasProxy`<a href="HasProxy-p" id="HasProxy-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool HasProxy { get; }
```  
***

## `Indicator`<a href="Indicator-p" id="Indicator-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Indicator { get; set; }
```  
***

## `IsConnected`<a href="IsConnected-p" id="IsConnected-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsConnected { get; set; }
```  
***

## `IsConnecting`<a href="IsConnecting-p" id="IsConnecting-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsConnecting { get; set; }
```  
***

## `LedBrush`<a href="LedBrush-p" id="LedBrush-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Brush LedBrush { get; }
```  
***

## `MarketData`<a href="MarketData-p" id="MarketData-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool MarketData { get; set; }
```  
***

## `MarketType`<a href="MarketType-p" id="MarketType-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string MarketType { get; set; }
```  
***

## `Proxy`<a href="Proxy-p" id="Proxy-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IfcHC6wbAs8uUIsvBmdJ Proxy { get; set; }
```  
***

## `Simulator`<a href="Simulator-p" id="Simulator-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Simulator { get; }
```  
***

## `TradeClientExtra`<a href="TradeClientExtra-p" id="TradeClientExtra-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TradeClientExtra { get; }
```  
***

## `TradeClientID`<a href="TradeClientID-p" id="TradeClientID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TradeClientID { get; }
```  
***

## `TradeClientName`<a href="TradeClientName-p" id="TradeClientName-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TradeClientName { get; }
```  
***

## `Trust`<a href="Trust-p" id="Trust-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Trust { get; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="PropertyChanged-p" id="PropertyChanged-p"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

