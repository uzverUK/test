
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Symbol
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckContract`](#method-checkcontract) | *Описание* |
| [`ConvertTimeFromLocal`](#method-converttimefromlocal) | *Описание* |
| [`ConvertTimeToLocal`](#method-converttimetolocal) | *Описание* |
| [`CurrentSymbolID`](#method-currentsymbolid) | *Описание* |
| [`FormatAvgSize`](#method-formatavgsize) | *Описание* |
| [`FormatFullSize`](#method-formatfullsize) | *Описание* |
| [`FormatPnl`](#method-formatpnl) | *Описание* |
| [`FormatPrice`](#method-formatprice) | *Описание* |
| [`FormatSize`](#method-formatsize) | *Описание* |
| [`FormatTime`](#method-formattime) | *Описание* |
| [`GetBaseCurrency`](#method-getbasecurrency) | *Описание* |
| [`GetContracts`](#method-getcontracts) | *Описание* |
| [`GetRealPrice`](#method-getrealprice) | *Описание* |
| [`GetRealSize`](#method-getrealsize) | *Описание* |
| [`GetShortPrice`](#method-getshortprice) | *Описание* |
| [`GetShortSize`](#method-getshortsize) | *Описание* |
| [`GetStepPrice`](#method-getstepprice) | *Описание* |
| [`GetSymbol`](#method-getsymbol) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |
| [`UpdateFields`](#method-updatefields) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AdditionalData`](#property-additionaldata) | *Описание* |
| [`ContactValue`](#property-contactvalue) | *Описание* |
| [`Currency`](#property-currency) | *Описание* |
| [`Description`](#property-description) | *Описание* |
| [`Exchange`](#property-exchange) | *Описание* |
| [`Expiration`](#property-expiration) | *Описание* |
| [`ID`](#property-id) | *Описание* |
| [`IsBinance`](#property-isbinance) | *Описание* |
| [`IsBitFinex`](#property-isbitfinex) | *Описание* |
| [`IsBitMEX`](#property-isbitmex) | *Описание* |
| [`IsBybit`](#property-isbybit) | *Описание* |
| [`IsCrypto`](#property-iscrypto) | *Описание* |
| [`IsCryptoFuture`](#property-iscryptofuture) | *Описание* |
| [`IsDeleted`](#property-isdeleted) | *Описание* |
| [`IsDeribit`](#property-isderibit) | *Описание* |
| [`IsFTX`](#property-isftx) | *Описание* |
| [`IsHitBTC`](#property-ishitbtc) | *Описание* |
| [`IsLinkable`](#property-islinkable) | *Описание* |
| [`IsMaster`](#property-ismaster) | *Описание* |
| [`IsOKX`](#property-isokx) | *Описание* |
| [`IsSplicedFutures`](#property-issplicedfutures) | *Описание* |
| [`LongCode`](#property-longcode) | *Описание* |
| [`LotSize`](#property-lotsize) | *Описание* |
| [`LotStep`](#property-lotstep) | *Описание* |
| [`Mapping`](#property-mapping) | *Описание* |
| [`Master`](#property-master) | *Описание* |
| [`MinNotional`](#property-minnotional) | *Описание* |
| [`MinQty`](#property-minqty) | *Описание* |
| [`Name`](#property-name) | *Описание* |
| [`OptAsset`](#property-optasset) | *Описание* |
| [`OptStrike`](#property-optstrike) | *Описание* |
| [`OptType`](#property-opttype) | *Описание* |
| [`PnlPrecision`](#property-pnlprecision) | *Описание* |
| [`Precision`](#property-precision) | *Описание* |
| [`SizePrecision`](#property-sizeprecision) | *Описание* |
| [`SizeStep`](#property-sizestep) | *Описание* |
| [`SpecChangeUtcDate`](#property-specchangeutcdate) | *Описание* |
| [`Step`](#property-step) | *Описание* |
| [`Type`](#property-type) | *Описание* |





***  
***  
# Методы

## `CheckContract`<a href="method-checkcontract" id="method-checkcontract"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CheckContract(string symbolID)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `CheckContract`<a href="method-checkcontract" id="method-checkcontract"></a>
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

## `ConvertTimeFromLocal`<a href="method-converttimefromlocal" id="method-converttimefromlocal"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime ConvertTimeFromLocal(DateTime dt)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ConvertTimeToLocal`<a href="method-converttimetolocal" id="method-converttimetolocal"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `CurrentSymbolID`<a href="method-currentsymbolid" id="method-currentsymbolid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string CurrentSymbolID()
```

***  

## `FormatAvgSize`<a href="method-formatavgsize" id="method-formatavgsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatAvgSize(double size, bool f = false)
```

`size` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatFullSize`<a href="method-formatfullsize" id="method-formatfullsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatFullSize(long size, bool f = false)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatFullSize`<a href="method-formatfullsize" id="method-formatfullsize"></a>
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

## `FormatFullSize`<a href="method-formatfullsize" id="method-formatfullsize"></a>
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

## `FormatPnl`<a href="method-formatpnl" id="method-formatpnl"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatPnl(double pnl, bool f = false)
```
`pnl` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `FormatPnl`<a href="method-formatpnl" id="method-formatpnl"></a>
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

## `FormatPrice`<a href="method-formatprice" id="method-formatprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatPrice(long price, bool f = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatPrice`<a href="method-formatprice" id="method-formatprice"></a>
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

## `FormatPrice`<a href="method-formatprice" id="method-formatprice"></a>
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

## `FormatPrice`<a href="method-formatprice" id="method-formatprice"></a>
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

## `FormatSize`<a href="method-formatsize" id="method-formatsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatSize(long size)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatSize`<a href="method-formatsize" id="method-formatsize"></a>
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

## `FormatTime`<a href="method-formattime" id="method-formattime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatTime(DateTime dt, string format)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatTime`<a href="method-formattime" id="method-formattime"></a>
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

## `GetBaseCurrency`<a href="method-getbasecurrency" id="method-getbasecurrency"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string GetBaseCurrency()
```

***  

## `GetContracts`<a href="method-getcontracts" id="method-getcontracts"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<Symbol> GetContracts()
```

***  

## `GetRealPrice`<a href="method-getrealprice" id="method-getrealprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetRealPrice(long price)
```

`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetRealSize`<a href="method-getrealsize" id="method-getrealsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetRealSize(long size)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetShortPrice`<a href="method-getshortprice" id="method-getshortprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long GetShortPrice(double price)
```
`price` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetShortSize`<a href="method-getshortsize" id="method-getshortsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long GetShortSize(double size)
```
`size` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetStepPrice`<a href="method-getstepprice" id="method-getstepprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetStepPrice()
```

***  

## `GetSymbol`<a href="method-getsymbol" id="method-getsymbol"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol GetSymbol()
```

***  

## `GetSymbol`<a href="method-getsymbol" id="method-getsymbol"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol GetSymbol()
public Symbol GetSymbol(DateTime date)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  

## `UpdateFields`<a href="method-updatefields" id="method-updatefields"></a>
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

## `AdditionalData`<a href="property-additionaldata" id="property-additionaldata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Hashtable AdditionalData { get; set; }
```  
***

## `ContactValue`<a href="property-contactvalue" id="property-contactvalue"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double ContactValue { get; set; }
```  
***

## `Currency`<a href="property-currency" id="property-currency"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Currency { get; internal set; }
```  
***

## `Description`<a href="property-description" id="property-description"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Description { get; internal set; }
```  
***

## `Exchange`<a href="property-exchange" id="property-exchange"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Exchange { get; internal set; }
```  
***

## `Expiration`<a href="property-expiration" id="property-expiration"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Expiration { get; private set; }
```  
***

## `ID`<a href="property-id" id="property-id"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `IsBinance`<a href="property-isbinance" id="property-isbinance"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBinance { get; }
```  
***

## `IsBitFinex`<a href="property-isbitfinex" id="property-isbitfinex"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBitFinex { get; }
```  
***

## `IsBitMEX`<a href="property-isbitmex" id="property-isbitmex"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBitMEX { get; }
```  
***

## `IsBybit`<a href="property-isbybit" id="property-isbybit"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBybit { get; }
```  
***

## `IsCrypto`<a href="property-iscrypto" id="property-iscrypto"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsCrypto { get; }
```  
***

## `IsCryptoFuture`<a href="property-iscryptofuture" id="property-iscryptofuture"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsCryptoFuture { get; }
```  
***

## `IsDeleted`<a href="property-isdeleted" id="property-isdeleted"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsDeleted { get; set; }
```  
***

## `IsDeribit`<a href="property-isderibit" id="property-isderibit"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsDeribit { get; }
```  
***

## `IsFTX`<a href="property-isftx" id="property-isftx"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsFTX { get; }
```  
***

## `IsHitBTC`<a href="property-ishitbtc" id="property-ishitbtc"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsHitBTC { get; }
```  
***

## `IsLinkable`<a href="property-islinkable" id="property-islinkable"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsLinkable { get; }
```  
***

## `IsMaster`<a href="property-ismaster" id="property-ismaster"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsMaster { get; }
```  
***

## `IsOKX`<a href="property-isokx" id="property-isokx"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsOKX { get; }
```  
***

## `IsSplicedFutures`<a href="property-issplicedfutures" id="property-issplicedfutures"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSplicedFutures { get; private set; }
```  
***

## `LongCode`<a href="property-longcode" id="property-longcode"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string LongCode { get; set; }
```  
***

## `LotSize`<a href="property-lotsize" id="property-lotsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LotSize { get; internal set; }
```  
***

## `LotStep`<a href="property-lotstep" id="property-lotstep"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double LotStep { get; internal set; }
```  
***

## `Mapping`<a href="property-mapping" id="property-mapping"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Mapping { get; internal set; }
```  
***

## `Master`<a href="property-master" id="property-master"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Master { get; }
```  
***

## `MinNotional`<a href="property-minnotional" id="property-minnotional"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinNotional { get; internal set; }
```  
***

## `MinQty`<a href="property-minqty" id="property-minqty"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinQty { get; internal set; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; internal set; }
```  
***

## `OptAsset`<a href="property-optasset" id="property-optasset"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string OptAsset { get; set; }
```  
***

## `OptStrike`<a href="property-optstrike" id="property-optstrike"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double OptStrike { get; set; }
```  
***

## `OptType`<a href="property-opttype" id="property-opttype"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public SymbolOptType OptType { get; set; }
```  
***

## `PnlPrecision`<a href="property-pnlprecision" id="property-pnlprecision"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int PnlPrecision { get; internal set; }
```  
***

## `Precision`<a href="property-precision" id="property-precision"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Precision { get; internal set; }
```  
***

## `SizePrecision`<a href="property-sizeprecision" id="property-sizeprecision"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int SizePrecision { get; set; }
```  
***

## `SizeStep`<a href="property-sizestep" id="property-sizestep"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double SizeStep { get; internal set; }
```  
***

## `SpecChangeUtcDate`<a href="property-specchangeutcdate" id="property-specchangeutcdate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime SpecChangeUtcDate { get; set; }
```  
***

## `Step`<a href="property-step" id="property-step"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Step { get; internal set; }
```  
***

## `Type`<a href="property-type" id="property-type"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public SymbolType Type { get; }
```  
***

