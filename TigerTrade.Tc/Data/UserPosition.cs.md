
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class UserPosition
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetMoneyPnl`](#GetMoneyPnl-m) | *Описание* |
| [`GetPercentPnl`](#GetPercentPnl-m) | *Описание* |
| [`GetPointsPnl`](#GetPointsPnl-m) | *Описание* |
| [`InitStrategy`](#InitStrategy-m) | *Описание* |
| [`UserPosition`](#UserPosition-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AccountID`](#AccountID-p) | *Описание* |
| [`AccountName`](#AccountName-p) | *Описание* |
| [`Ask`](#Ask-p) | *Описание* |
| [`Bid`](#Bid-p) | *Описание* |
| [`Comission`](#Comission-p) | *Описание* |
| [`ConnectionID`](#ConnectionID-p) | *Описание* |
| [`ConnectionName`](#ConnectionName-p) | *Описание* |
| [`Hidden`](#Hidden-p) | *Описание* |
| [`IsMt5TimeValid`](#IsMt5TimeValid-p) | *Описание* |
| [`LastPrice`](#LastPrice-p) | *Описание* |
| [`LastTradeIDs`](#LastTradeIDs-p) | *Описание* |
| [`LastTradeTime`](#LastTradeTime-p) | *Описание* |
| [`MaxQuantity`](#MaxQuantity-p) | *Описание* |
| [`OpenPrice`](#OpenPrice-p) | *Описание* |
| [`OpenTime`](#OpenTime-p) | *Описание* |
| [`PositionID`](#PositionID-p) | *Описание* |
| [`PositionPnl`](#PositionPnl-p) | *Описание* |
| [`PositionTime`](#PositionTime-p) | *Описание* |
| [`Price`](#Price-p) | *Описание* |
| [`PriceSum`](#PriceSum-p) | *Описание* |
| [`PriceSumLong`](#PriceSumLong-p) | *Описание* |
| [`Size`](#Size-p) | *Описание* |
| [`SizeStep`](#SizeStep-p) | *Описание* |
| [`StartTime`](#StartTime-p) | *Описание* |
| [`Strategy`](#Strategy-p) | *Описание* |
| [`Symbol`](#Symbol-p) | *Описание* |
| [`SymbolID`](#SymbolID-p) | *Описание* |
| [`SymbolName`](#SymbolName-p) | *Описание* |
| [`TotalQuantity`](#TotalQuantity-p) | *Описание* |
| [`TotalValue`](#TotalValue-p) | *Описание* |
| [`TotalValueLong`](#TotalValueLong-p) | *Описание* |





***  
***  
# Методы

## `GetMoneyPnl`<a href="UserPosition-m" id="UserPosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetMoneyPnl()
```

***  

## `GetMoneyPnl`<a href="UserPosition-m" id="UserPosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetMoneyPnl()
public double GetMoneyPnl(long exitPrice)
```

`exitPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetMoneyPnl`<a href="UserPosition-m" id="UserPosition-m"></a>
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

## `GetPercentPnl`<a href="UserPosition-m" id="UserPosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPercentPnl()
```

***  

## `GetPercentPnl`<a href="UserPosition-m" id="UserPosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPercentPnl()
public double GetPercentPnl(long exitPrice)
```

`exitPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetPointsPnl`<a href="UserPosition-m" id="UserPosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPointsPnl()
```

***  

## `GetPointsPnl`<a href="UserPosition-m" id="UserPosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPointsPnl()
public double GetPointsPnl(long exitPrice)
```

`exitPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `InitStrategy`<a href="UserPosition-m" id="UserPosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InitStrategy(ExitStrategy strategy)
```
`strategy` <mark style="color:red;">*`ExitStrategy`*</mark>  
 *Описание*  


***  

## `UserPosition`<a href="UserPosition-m" id="UserPosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPosition()
```

***  

## `UserPosition`<a href="UserPosition-m" id="UserPosition-m"></a>
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

## `AccountID`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string AccountID { get; set; }
```  
***

## `AccountName`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string AccountName { get; set; }
```  
***

## `Ask`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Ask { get; private set; }
```  
***

## `Bid`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Bid { get; private set; }
```  
***

## `Comission`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Comission { get; set; }
```  
***

## `ConnectionID`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionID { get; set; }
```  
***

## `ConnectionName`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionName { get; set; }
```  
***

## `Hidden`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Hidden { get; set; }
```  
***

## `IsMt5TimeValid`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsMt5TimeValid { get; set; }
```  
***

## `LastPrice`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long LastPrice { get; private set; }
```  
***

## `LastTradeIDs`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public HashSet<string> LastTradeIDs { get; set; }
```  
***

## `LastTradeTime`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime LastTradeTime { get; set; }
```  
***

## `MaxQuantity`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long MaxQuantity { get; set; }
```  
***

## `OpenPrice`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPrice { get; set; }
```  
***

## `OpenTime`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime OpenTime { get; set; }
```  
***

## `PositionID`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PositionID { get; }
```  
***

## `PositionPnl`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long PositionPnl { get; private set; }
```  
***

## `PositionTime`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public TimeSpan PositionTime { get; private set; }
```  
***

## `Price`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Price { get; set; }
```  
***

## `PriceSum`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BigInteger PriceSum { get; set; }
```  
***

## `PriceSumLong`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long PriceSumLong { get; set; }
```  
***

## `Size`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Size { get; set; }
```  
***

## `SizeStep`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? SizeStep { get; set; }
```  
***

## `StartTime`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime StartTime { get; set; }
```  
***

## `Strategy`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ExitStrategy Strategy { get; set; }
```  
***

## `Symbol`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; internal set; }
```  
***

## `SymbolID`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SymbolID { get; set; }
```  
***

## `SymbolName`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SymbolName { get; set; }
```  
***

## `TotalQuantity`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long TotalQuantity { get; set; }
```  
***

## `TotalValue`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BigInteger TotalValue { get; set; }
```  
***

## `TotalValueLong`<a href="TotalValueLong-p" id="TotalValueLong-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long TotalValueLong { get; set; }
```  
***

