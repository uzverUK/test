
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class UserPosition
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetMoneyPnl`](#test) | *Описание* |
| [`GetPercentPnl`](#test) | *Описание* |
| [`GetPointsPnl`](#test) | *Описание* |
| [`InitStrategy`](#test) | *Описание* |
| [`UserPosition`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AccountID`](./UserPosition.cs/Свойства/AccountID.md) | *Описание* |
| [`AccountName`](./UserPosition.cs/Свойства/AccountName.md) | *Описание* |
| [`Ask`](./UserPosition.cs/Свойства/Ask.md) | *Описание* |
| [`Bid`](./UserPosition.cs/Свойства/Bid.md) | *Описание* |
| [`Comission`](./UserPosition.cs/Свойства/Comission.md) | *Описание* |
| [`ConnectionID`](./UserPosition.cs/Свойства/ConnectionID.md) | *Описание* |
| [`ConnectionName`](./UserPosition.cs/Свойства/ConnectionName.md) | *Описание* |
| [`Hidden`](./UserPosition.cs/Свойства/Hidden.md) | *Описание* |
| [`IsMt5TimeValid`](./UserPosition.cs/Свойства/IsMt5TimeValid.md) | *Описание* |
| [`LastPrice`](./UserPosition.cs/Свойства/LastPrice.md) | *Описание* |
| [`LastTradeIDs`](./UserPosition.cs/Свойства/LastTradeIDs.md) | *Описание* |
| [`LastTradeTime`](./UserPosition.cs/Свойства/LastTradeTime.md) | *Описание* |
| [`MaxQuantity`](./UserPosition.cs/Свойства/MaxQuantity.md) | *Описание* |
| [`OpenPrice`](./UserPosition.cs/Свойства/OpenPrice.md) | *Описание* |
| [`OpenTime`](./UserPosition.cs/Свойства/OpenTime.md) | *Описание* |
| [`PositionID`](./UserPosition.cs/Свойства/PositionID.md) | *Описание* |
| [`PositionPnl`](./UserPosition.cs/Свойства/PositionPnl.md) | *Описание* |
| [`PositionTime`](./UserPosition.cs/Свойства/PositionTime.md) | *Описание* |
| [`Price`](./UserPosition.cs/Свойства/Price.md) | *Описание* |
| [`PriceSum`](./UserPosition.cs/Свойства/PriceSum.md) | *Описание* |
| [`PriceSumLong`](./UserPosition.cs/Свойства/PriceSumLong.md) | *Описание* |
| [`Size`](./UserPosition.cs/Свойства/Size.md) | *Описание* |
| [`SizeStep`](./UserPosition.cs/Свойства/SizeStep.md) | *Описание* |
| [`StartTime`](./UserPosition.cs/Свойства/StartTime.md) | *Описание* |
| [`Strategy`](./UserPosition.cs/Свойства/Strategy.md) | *Описание* |
| [`Symbol`](./UserPosition.cs/Свойства/Symbol.md) | *Описание* |
| [`SymbolID`](./UserPosition.cs/Свойства/SymbolID.md) | *Описание* |
| [`SymbolName`](./UserPosition.cs/Свойства/SymbolName.md) | *Описание* |
| [`TotalQuantity`](./UserPosition.cs/Свойства/TotalQuantity.md) | *Описание* |
| [`TotalValue`](./UserPosition.cs/Свойства/TotalValue.md) | *Описание* |
| [`TotalValueLong`](./UserPosition.cs/Свойства/TotalValueLong.md) | *Описание* |





***  
***  
# Методы

## `GetMoneyPnl`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetMoneyPnl()
```

***  

## `GetMoneyPnl`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetMoneyPnl()
public double GetMoneyPnl(long exitPrice)
```

`exitPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetMoneyPnl`<a href="test" id="test"></a>
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

## `GetPercentPnl`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPercentPnl()
```

***  

## `GetPercentPnl`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPercentPnl()
public double GetPercentPnl(long exitPrice)
```

`exitPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetPointsPnl`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPointsPnl()
```

***  

## `GetPointsPnl`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetPointsPnl()
public double GetPointsPnl(long exitPrice)
```

`exitPrice` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `InitStrategy`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InitStrategy(ExitStrategy strategy)
```
`strategy` <mark style="color:red;">*`ExitStrategy`*</mark>  
 *Описание*  


***  

## `UserPosition`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public UserPosition()
```

***  

## `UserPosition`<a href="test" id="test"></a>
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

## `AccountID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string AccountID { get; set; }
```  
***

## `AccountName`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string AccountName { get; set; }
```  
***

## `Ask`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Ask { get; private set; }
```  
***

## `Bid`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Bid { get; private set; }
```  
***

## `Comission`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Comission { get; set; }
```  
***

## `ConnectionID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionID { get; set; }
```  
***

## `ConnectionName`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ConnectionName { get; set; }
```  
***

## `Hidden`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Hidden { get; set; }
```  
***

## `IsMt5TimeValid`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsMt5TimeValid { get; set; }
```  
***

## `LastPrice`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long LastPrice { get; private set; }
```  
***

## `LastTradeIDs`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public HashSet<string> LastTradeIDs { get; set; }
```  
***

## `LastTradeTime`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime LastTradeTime { get; set; }
```  
***

## `MaxQuantity`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long MaxQuantity { get; set; }
```  
***

## `OpenPrice`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPrice { get; set; }
```  
***

## `OpenTime`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime OpenTime { get; set; }
```  
***

## `PositionID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PositionID { get; }
```  
***

## `PositionPnl`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long PositionPnl { get; private set; }
```  
***

## `PositionTime`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public TimeSpan PositionTime { get; private set; }
```  
***

## `Price`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Price { get; set; }
```  
***

## `PriceSum`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BigInteger PriceSum { get; set; }
```  
***

## `PriceSumLong`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long PriceSumLong { get; set; }
```  
***

## `Size`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Size { get; set; }
```  
***

## `SizeStep`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? SizeStep { get; set; }
```  
***

## `StartTime`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime StartTime { get; set; }
```  
***

## `Strategy`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ExitStrategy Strategy { get; set; }
```  
***

## `Symbol`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; internal set; }
```  
***

## `SymbolID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SymbolID { get; set; }
```  
***

## `SymbolName`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string SymbolName { get; set; }
```  
***

## `TotalQuantity`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long TotalQuantity { get; set; }
```  
***

## `TotalValue`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BigInteger TotalValue { get; set; }
```  
***

## `TotalValueLong`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long TotalValueLong { get; set; }
```  
***

