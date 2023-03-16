
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class UserPosition
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetMoneyPnl`](#method-getmoneypnl) | *Описание* |
| [`GetPercentPnl`](#method-getpercentpnl) | *Описание* |
| [`GetPointsPnl`](#method-getpointspnl) | *Описание* |
| [`InitStrategy`](#method-initstrategy) | *Описание* |
| [`UserPosition`](#method-userposition) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AccountID`](#property-accountid) | *Описание* |
| [`AccountName`](#property-accountname) | *Описание* |
| [`Ask`](#property-ask) | *Описание* |
| [`Bid`](#property-bid) | *Описание* |
| [`Comission`](#property-comission) | *Описание* |
| [`ConnectionID`](#property-connectionid) | *Описание* |
| [`ConnectionName`](#property-connectionname) | *Описание* |
| [`Hidden`](#property-hidden) | *Описание* |
| [`IsMt5TimeValid`](#property-ismt5timevalid) | *Описание* |
| [`LastPrice`](#property-lastprice) | *Описание* |
| [`LastTradeIDs`](#property-lasttradeids) | *Описание* |
| [`LastTradeTime`](#property-lasttradetime) | *Описание* |
| [`MaxQuantity`](#property-maxquantity) | *Описание* |
| [`OpenPrice`](#property-openprice) | *Описание* |
| [`OpenTime`](#property-opentime) | *Описание* |
| [`PositionID`](#property-positionid) | *Описание* |
| [`PositionPnl`](#property-positionpnl) | *Описание* |
| [`PositionTime`](#property-positiontime) | *Описание* |
| [`Price`](#property-price) | *Описание* |
| [`PriceSum`](#property-pricesum) | *Описание* |
| [`PriceSumLong`](#property-pricesumlong) | *Описание* |
| [`Size`](#property-size) | *Описание* |
| [`SizeStep`](#property-sizestep) | *Описание* |
| [`StartTime`](#property-starttime) | *Описание* |
| [`Strategy`](#property-strategy) | *Описание* |
| [`Symbol`](#property-symbol) | *Описание* |
| [`SymbolID`](#property-symbolid) | *Описание* |
| [`SymbolName`](#property-symbolname) | *Описание* |
| [`TotalQuantity`](#property-totalquantity) | *Описание* |
| [`TotalValue`](#property-totalvalue) | *Описание* |
| [`TotalValueLong`](#property-totalvaluelong) | *Описание* |





***  
***  
# Методы

## `GetMoneyPnl`<a href="method-getmoneypnl" id="method-getmoneypnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetMoneyPnl()
```

***  

## `GetMoneyPnl`<a href="method-getmoneypnl" id="method-getmoneypnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetMoneyPnl()
public double GetMoneyPnl(long exitPrice)
```

`exitPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetMoneyPnl`<a href="method-getmoneypnl" id="method-getmoneypnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetMoneyPnl()
public double GetMoneyPnl(long exitPrice)
public double GetMoneyPnl(long entryPrice, long exitPrice, long size)
```

`exitPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`entryPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetPercentPnl`<a href="method-getpercentpnl" id="method-getpercentpnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPercentPnl()
```

***  

## `GetPercentPnl`<a href="method-getpercentpnl" id="method-getpercentpnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPercentPnl()
public double GetPercentPnl(long exitPrice)
```

`exitPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetPointsPnl`<a href="method-getpointspnl" id="method-getpointspnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPointsPnl()
```

***  

## `GetPointsPnl`<a href="method-getpointspnl" id="method-getpointspnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPointsPnl()
public double GetPointsPnl(long exitPrice)
```

`exitPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `InitStrategy`<a href="method-initstrategy" id="method-initstrategy"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InitStrategy(ExitStrategy strategy)
```
`strategy` <mark style="color:red;">*`ExitStrategy`*</mark>  
 *Описание*  


***  

## `UserPosition`<a href="method-userposition" id="method-userposition"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPosition()
```

***  

## `UserPosition`<a href="method-userposition" id="method-userposition"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPosition()
public UserPosition(ConnectionInfo info, Symbol symbol, Account account)
```

`info` <mark style="color:red;">*`ConnectionInfo`*</mark>  
 *Описание*  

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `AccountID`<a href="property-accountid" id="property-accountid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string AccountID { get; set; }
```  
***

## `AccountName`<a href="property-accountname" id="property-accountname"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string AccountName { get; set; }
```  
***

## `Ask`<a href="property-ask" id="property-ask"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Ask { get; private set; }
```  
***

## `Bid`<a href="property-bid" id="property-bid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Bid { get; private set; }
```  
***

## `Comission`<a href="property-comission" id="property-comission"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Comission { get; set; }
```  
***

## `ConnectionID`<a href="property-connectionid" id="property-connectionid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionID { get; set; }
```  
***

## `ConnectionName`<a href="property-connectionname" id="property-connectionname"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionName { get; set; }
```  
***

## `Hidden`<a href="property-hidden" id="property-hidden"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Hidden { get; set; }
```  
***

## `IsMt5TimeValid`<a href="property-ismt5timevalid" id="property-ismt5timevalid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsMt5TimeValid { get; set; }
```  
***

## `LastPrice`<a href="property-lastprice" id="property-lastprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long LastPrice { get; private set; }
```  
***

## `LastTradeIDs`<a href="property-lasttradeids" id="property-lasttradeids"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public HashSet<string> LastTradeIDs { get; set; }
```  
***

## `LastTradeTime`<a href="property-lasttradetime" id="property-lasttradetime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime LastTradeTime { get; set; }
```  
***

## `MaxQuantity`<a href="property-maxquantity" id="property-maxquantity"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long MaxQuantity { get; set; }
```  
***

## `OpenPrice`<a href="property-openprice" id="property-openprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPrice { get; set; }
```  
***

## `OpenTime`<a href="property-opentime" id="property-opentime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime OpenTime { get; set; }
```  
***

## `PositionID`<a href="property-positionid" id="property-positionid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PositionID { get; }
```  
***

## `PositionPnl`<a href="property-positionpnl" id="property-positionpnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long PositionPnl { get; private set; }
```  
***

## `PositionTime`<a href="property-positiontime" id="property-positiontime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public TimeSpan PositionTime { get; private set; }
```  
***

## `Price`<a href="property-price" id="property-price"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Price { get; set; }
```  
***

## `PriceSum`<a href="property-pricesum" id="property-pricesum"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BigInteger PriceSum { get; set; }
```  
***

## `PriceSumLong`<a href="property-pricesumlong" id="property-pricesumlong"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long PriceSumLong { get; set; }
```  
***

## `Size`<a href="property-size" id="property-size"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Size { get; set; }
```  
***

## `SizeStep`<a href="property-sizestep" id="property-sizestep"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? SizeStep { get; set; }
```  
***

## `StartTime`<a href="property-starttime" id="property-starttime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime StartTime { get; set; }
```  
***

## `Strategy`<a href="property-strategy" id="property-strategy"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ExitStrategy Strategy { get; set; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; internal set; }
```  
***

## `SymbolID`<a href="property-symbolid" id="property-symbolid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SymbolID { get; set; }
```  
***

## `SymbolName`<a href="property-symbolname" id="property-symbolname"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SymbolName { get; set; }
```  
***

## `TotalQuantity`<a href="property-totalquantity" id="property-totalquantity"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long TotalQuantity { get; set; }
```  
***

## `TotalValue`<a href="property-totalvalue" id="property-totalvalue"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BigInteger TotalValue { get; set; }
```  
***

## `TotalValueLong`<a href="property-totalvaluelong" id="property-totalvaluelong"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long TotalValueLong { get; set; }
```  
***

