
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Symbol
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckContract`](#CheckContract-m) | *Описание* |
| [`ConvertTimeFromLocal`](#ConvertTimeFromLocal-m) | *Описание* |
| [`ConvertTimeToLocal`](#ConvertTimeToLocal-m) | *Описание* |
| [`CurrentSymbolID`](#CurrentSymbolID-m) | *Описание* |
| [`FormatAvgSize`](#FormatAvgSize-m) | *Описание* |
| [`FormatFullSize`](#FormatFullSize-m) | *Описание* |
| [`FormatPnl`](#FormatPnl-m) | *Описание* |
| [`FormatPrice`](#FormatPrice-m) | *Описание* |
| [`FormatSize`](#FormatSize-m) | *Описание* |
| [`FormatTime`](#FormatTime-m) | *Описание* |
| [`GetBaseCurrency`](#GetBaseCurrency-m) | *Описание* |
| [`GetContracts`](#GetContracts-m) | *Описание* |
| [`GetRealPrice`](#GetRealPrice-m) | *Описание* |
| [`GetRealSize`](#GetRealSize-m) | *Описание* |
| [`GetShortPrice`](#GetShortPrice-m) | *Описание* |
| [`GetShortSize`](#GetShortSize-m) | *Описание* |
| [`GetStepPrice`](#GetStepPrice-m) | *Описание* |
| [`GetSymbol`](#GetSymbol-m) | *Описание* |
| [`ToString`](#ToString-m) | *Описание* |
| [`UpdateFields`](#UpdateFields-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AdditionalData`](#AdditionalData-p) | *Описание* |
| [`ContactValue`](#ContactValue-p) | *Описание* |
| [`Currency`](#Currency-p) | *Описание* |
| [`Description`](#Description-p) | *Описание* |
| [`Exchange`](#Exchange-p) | *Описание* |
| [`Expiration`](#Expiration-p) | *Описание* |
| [`ID`](#ID-p) | *Описание* |
| [`IsBinance`](#IsBinance-p) | *Описание* |
| [`IsBitFinex`](#IsBitFinex-p) | *Описание* |
| [`IsBitMEX`](#IsBitMEX-p) | *Описание* |
| [`IsBybit`](#IsBybit-p) | *Описание* |
| [`IsCrypto`](#IsCrypto-p) | *Описание* |
| [`IsCryptoFuture`](#IsCryptoFuture-p) | *Описание* |
| [`IsDeleted`](#IsDeleted-p) | *Описание* |
| [`IsDeribit`](#IsDeribit-p) | *Описание* |
| [`IsFTX`](#IsFTX-p) | *Описание* |
| [`IsHitBTC`](#IsHitBTC-p) | *Описание* |
| [`IsLinkable`](#IsLinkable-p) | *Описание* |
| [`IsMaster`](#IsMaster-p) | *Описание* |
| [`IsOKX`](#IsOKX-p) | *Описание* |
| [`IsSplicedFutures`](#IsSplicedFutures-p) | *Описание* |
| [`LongCode`](#LongCode-p) | *Описание* |
| [`LotSize`](#LotSize-p) | *Описание* |
| [`LotStep`](#LotStep-p) | *Описание* |
| [`Mapping`](#Mapping-p) | *Описание* |
| [`Master`](#Master-p) | *Описание* |
| [`MinNotional`](#MinNotional-p) | *Описание* |
| [`MinQty`](#MinQty-p) | *Описание* |
| [`Name`](#Name-p) | *Описание* |
| [`OptAsset`](#OptAsset-p) | *Описание* |
| [`OptStrike`](#OptStrike-p) | *Описание* |
| [`OptType`](#OptType-p) | *Описание* |
| [`PnlPrecision`](#PnlPrecision-p) | *Описание* |
| [`Precision`](#Precision-p) | *Описание* |
| [`SizePrecision`](#SizePrecision-p) | *Описание* |
| [`SizeStep`](#SizeStep-p) | *Описание* |
| [`SpecChangeUtcDate`](#SpecChangeUtcDate-p) | *Описание* |
| [`Step`](#Step-p) | *Описание* |
| [`Type`](#Type-p) | *Описание* |





***  
***  
# Методы

## `CheckContract`<a href="CheckContract-m" id="CheckContract-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CheckContract(string symbolID)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `CheckContract`<a href="CheckContract-m" id="CheckContract-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CheckContract(string symbolID)
public bool CheckContract(Symbol symbol)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  


***  

## `ConvertTimeFromLocal`<a href="ConvertTimeFromLocal-m" id="ConvertTimeFromLocal-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime ConvertTimeFromLocal(DateTime dt)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ConvertTimeToLocal`<a href="ConvertTimeToLocal-m" id="ConvertTimeToLocal-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `CurrentSymbolID`<a href="CurrentSymbolID-m" id="CurrentSymbolID-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string CurrentSymbolID()
```

***  

## `FormatAvgSize`<a href="FormatAvgSize-m" id="FormatAvgSize-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatAvgSize(double size, bool f = false)
```

`size` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatFullSize`<a href="FormatFullSize-m" id="FormatFullSize-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatFullSize(long size, bool f = false)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatFullSize`<a href="FormatFullSize-m" id="FormatFullSize-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatFullSize(long size, bool f = false)
public string FormatFullSize(long size, IFormatProvider provider, bool f = false)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`provider` <mark style="color:red;">*`IFormatProvider`*</mark>  
 *Описание*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatFullSize`<a href="FormatFullSize-m" id="FormatFullSize-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatFullSize(long size, bool f = false)
public string FormatFullSize(long size, IFormatProvider provider, bool f = false)
public string FormatFullSize(long? size, bool f = false)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`provider` <mark style="color:red;">*`IFormatProvider`*</mark>  
 *Описание*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatPnl`<a href="FormatPnl-m" id="FormatPnl-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatPnl(double pnl, bool f = false)
```
`pnl` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `FormatPnl`<a href="FormatPnl-m" id="FormatPnl-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatPnl(double pnl, bool f = false)
public string FormatPnl(double? pnl, bool f = false)
```
`pnl` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatPrice`<a href="FormatPrice-m" id="FormatPrice-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatPrice(long price, bool f = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatPrice`<a href="FormatPrice-m" id="FormatPrice-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatPrice(long price, bool f = false)
public string FormatPrice(long price, IFormatProvider provider, bool f = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`provider` <mark style="color:red;">*`IFormatProvider`*</mark>  
 *Описание*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatPrice`<a href="FormatPrice-m" id="FormatPrice-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatPrice(long price, bool f = false)
public string FormatPrice(long price, IFormatProvider provider, bool f = false)
public string FormatPrice(double price, bool f = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`provider` <mark style="color:red;">*`IFormatProvider`*</mark>  
 *Описание*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`price` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `FormatPrice`<a href="FormatPrice-m" id="FormatPrice-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatPrice(long price, bool f = false)
public string FormatPrice(long price, IFormatProvider provider, bool f = false)
public string FormatPrice(double price, bool f = false)
public string FormatPrice(double? price, bool f = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`provider` <mark style="color:red;">*`IFormatProvider`*</mark>  
 *Описание*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`price` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `FormatSize`<a href="FormatSize-m" id="FormatSize-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatSize(long size)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatSize`<a href="FormatSize-m" id="FormatSize-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatSize(long size)
public string FormatSize(double size, bool f = false)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`size` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatTime`<a href="FormatTime-m" id="FormatTime-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatTime(DateTime dt, string format)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatTime`<a href="FormatTime-m" id="FormatTime-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatTime(DateTime dt, string format)
public string FormatTime(DateTime dt, string dateFormat, string timeFormat)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`dateFormat` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`timeFormat` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetBaseCurrency`<a href="GetBaseCurrency-m" id="GetBaseCurrency-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string GetBaseCurrency()
```

***  

## `GetContracts`<a href="GetContracts-m" id="GetContracts-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<Symbol> GetContracts()
```

***  

## `GetRealPrice`<a href="GetRealPrice-m" id="GetRealPrice-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetRealPrice(long price)
```

`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetRealSize`<a href="GetRealSize-m" id="GetRealSize-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetRealSize(long size)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetShortPrice`<a href="GetShortPrice-m" id="GetShortPrice-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long GetShortPrice(double price)
```
`price` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetShortSize`<a href="GetShortSize-m" id="GetShortSize-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long GetShortSize(double size)
```
`size` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetStepPrice`<a href="GetStepPrice-m" id="GetStepPrice-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetStepPrice()
```

***  

## `GetSymbol`<a href="GetSymbol-m" id="GetSymbol-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol GetSymbol()
```

***  

## `GetSymbol`<a href="GetSymbol-m" id="GetSymbol-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol GetSymbol()
public Symbol GetSymbol(DateTime date)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ToString`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  

## `UpdateFields`<a href="UpdateFields-m" id="UpdateFields-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void UpdateFields(Symbol symbol)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `AdditionalData`<a href="AdditionalData-p" id="AdditionalData-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Hashtable AdditionalData { get; set; }
```  
***

## `ContactValue`<a href="ContactValue-p" id="ContactValue-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double ContactValue { get; set; }
```  
***

## `Currency`<a href="Currency-p" id="Currency-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Currency { get; internal set; }
```  
***

## `Description`<a href="Description-p" id="Description-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Description { get; internal set; }
```  
***

## `Exchange`<a href="Exchange-p" id="Exchange-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Exchange { get; internal set; }
```  
***

## `Expiration`<a href="Expiration-p" id="Expiration-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Expiration { get; private set; }
```  
***

## `ID`<a href="ID-p" id="ID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `IsBinance`<a href="IsBinance-p" id="IsBinance-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBinance { get; }
```  
***

## `IsBitFinex`<a href="IsBitFinex-p" id="IsBitFinex-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBitFinex { get; }
```  
***

## `IsBitMEX`<a href="IsBitMEX-p" id="IsBitMEX-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBitMEX { get; }
```  
***

## `IsBybit`<a href="IsBybit-p" id="IsBybit-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBybit { get; }
```  
***

## `IsCrypto`<a href="IsCrypto-p" id="IsCrypto-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsCrypto { get; }
```  
***

## `IsCryptoFuture`<a href="IsCryptoFuture-p" id="IsCryptoFuture-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsCryptoFuture { get; }
```  
***

## `IsDeleted`<a href="IsDeleted-p" id="IsDeleted-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsDeleted { get; set; }
```  
***

## `IsDeribit`<a href="IsDeribit-p" id="IsDeribit-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsDeribit { get; }
```  
***

## `IsFTX`<a href="IsFTX-p" id="IsFTX-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsFTX { get; }
```  
***

## `IsHitBTC`<a href="IsHitBTC-p" id="IsHitBTC-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsHitBTC { get; }
```  
***

## `IsLinkable`<a href="IsLinkable-p" id="IsLinkable-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsLinkable { get; }
```  
***

## `IsMaster`<a href="IsMaster-p" id="IsMaster-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsMaster { get; }
```  
***

## `IsOKX`<a href="IsOKX-p" id="IsOKX-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsOKX { get; }
```  
***

## `IsSplicedFutures`<a href="IsSplicedFutures-p" id="IsSplicedFutures-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSplicedFutures { get; private set; }
```  
***

## `LongCode`<a href="LongCode-p" id="LongCode-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string LongCode { get; set; }
```  
***

## `LotSize`<a href="LotSize-p" id="LotSize-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LotSize { get; internal set; }
```  
***

## `LotStep`<a href="LotStep-p" id="LotStep-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double LotStep { get; internal set; }
```  
***

## `Mapping`<a href="Mapping-p" id="Mapping-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Mapping { get; internal set; }
```  
***

## `Master`<a href="Master-p" id="Master-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Master { get; }
```  
***

## `MinNotional`<a href="MinNotional-p" id="MinNotional-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinNotional { get; internal set; }
```  
***

## `MinQty`<a href="MinQty-p" id="MinQty-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinQty { get; internal set; }
```  
***

## `Name`<a href="Name-p" id="Name-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; internal set; }
```  
***

## `OptAsset`<a href="OptAsset-p" id="OptAsset-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string OptAsset { get; set; }
```  
***

## `OptStrike`<a href="OptStrike-p" id="OptStrike-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double OptStrike { get; set; }
```  
***

## `OptType`<a href="OptType-p" id="OptType-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public SymbolOptType OptType { get; set; }
```  
***

## `PnlPrecision`<a href="PnlPrecision-p" id="PnlPrecision-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int PnlPrecision { get; internal set; }
```  
***

## `Precision`<a href="Precision-p" id="Precision-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Precision { get; internal set; }
```  
***

## `SizePrecision`<a href="SizePrecision-p" id="SizePrecision-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int SizePrecision { get; set; }
```  
***

## `SizeStep`<a href="SizeStep-p" id="SizeStep-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double SizeStep { get; internal set; }
```  
***

## `SpecChangeUtcDate`<a href="SpecChangeUtcDate-p" id="SpecChangeUtcDate-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime SpecChangeUtcDate { get; set; }
```  
***

## `Step`<a href="Step-p" id="Step-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Step { get; internal set; }
```  
***

## `Type`<a href="Type-p" id="Type-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public SymbolType Type { get; }
```  
***

