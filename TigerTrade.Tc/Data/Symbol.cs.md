
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


===

### Синтаксис
```csharp
public sealed class Symbol
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckContract`](#method-checkcontract) | *===* |
| [`ConvertTimeFromLocal`](#method-converttimefromlocal) | *===* |
| [`ConvertTimeToLocal`](#method-converttimetolocal) | *===* |
| [`CurrentSymbolID`](#method-currentsymbolid) | *===* |
| [`FormatAvgSize`](#method-formatavgsize) | *===* |
| [`FormatFullSize`](#method-formatfullsize) | *===* |
| [`FormatPnl`](#method-formatpnl) | *===* |
| [`FormatPrice`](#method-formatprice) | *===* |
| [`FormatSize`](#method-formatsize) | *===* |
| [`FormatTime`](#method-formattime) | *===* |
| [`GetBaseCurrency`](#method-getbasecurrency) | *===* |
| [`GetContracts`](#method-getcontracts) | *===* |
| [`GetRealPrice`](#method-getrealprice) | *===* |
| [`GetRealSize`](#method-getrealsize) | *===* |
| [`GetShortPrice`](#method-getshortprice) | *===* |
| [`GetShortSize`](#method-getshortsize) | *===* |
| [`GetStepPrice`](#method-getstepprice) | *===* |
| [`GetSymbol`](#method-getsymbol) | *===* |
| [`ToString`](#method-tostring) | *===* |
| [`UpdateFields`](#method-updatefields) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AdditionalData`](#property-additionaldata) | *===* |
| [`ContactValue`](#property-contactvalue) | *===* |
| [`Currency`](#property-currency) | *===* |
| [`Description`](#property-description) | *===* |
| [`Exchange`](#property-exchange) | *===* |
| [`Expiration`](#property-expiration) | *===* |
| [`ID`](#property-id) | *===* |
| [`IsBinance`](#property-isbinance) | *===* |
| [`IsBitFinex`](#property-isbitfinex) | *===* |
| [`IsBitMEX`](#property-isbitmex) | *===* |
| [`IsBybit`](#property-isbybit) | *===* |
| [`IsCrypto`](#property-iscrypto) | *===* |
| [`IsCryptoFuture`](#property-iscryptofuture) | *===* |
| [`IsDeleted`](#property-isdeleted) | *===* |
| [`IsDeribit`](#property-isderibit) | *===* |
| [`IsFTX`](#property-isftx) | *===* |
| [`IsHitBTC`](#property-ishitbtc) | *===* |
| [`IsLinkable`](#property-islinkable) | *===* |
| [`IsMaster`](#property-ismaster) | *===* |
| [`IsOKX`](#property-isokx) | *===* |
| [`IsSplicedFutures`](#property-issplicedfutures) | *===* |
| [`LongCode`](#property-longcode) | *===* |
| [`LotSize`](#property-lotsize) | *===* |
| [`LotStep`](#property-lotstep) | *===* |
| [`Mapping`](#property-mapping) | *===* |
| [`Master`](#property-master) | *===* |
| [`MinNotional`](#property-minnotional) | *===* |
| [`MinQty`](#property-minqty) | *===* |
| [`Name`](#property-name) | *===* |
| [`OptAsset`](#property-optasset) | *===* |
| [`OptStrike`](#property-optstrike) | *===* |
| [`OptType`](#property-opttype) | *===* |
| [`PnlPrecision`](#property-pnlprecision) | *===* |
| [`Precision`](#property-precision) | *===* |
| [`SizePrecision`](#property-sizeprecision) | *===* |
| [`SizeStep`](#property-sizestep) | *===* |
| [`SpecChangeUtcDate`](#property-specchangeutcdate) | *===* |
| [`Step`](#property-step) | *===* |
| [`Type`](#property-type) | *===* |





***  
***  
# Методы

## `CheckContract`<a href="method-checkcontract" id="method-checkcontract"></a>
===
```csharp
public bool CheckContract(string symbolID)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `CheckContract`<a href="method-checkcontract" id="method-checkcontract"></a>
===
```csharp
public bool CheckContract(string symbolID)
public bool CheckContract(Symbol symbol)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *===*  

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  


***  

## `ConvertTimeFromLocal`<a href="method-converttimefromlocal" id="method-converttimefromlocal"></a>
===
```csharp
public DateTime ConvertTimeFromLocal(DateTime dt)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  


***  

## `ConvertTimeToLocal`<a href="method-converttimetolocal" id="method-converttimetolocal"></a>
===
```csharp
public DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `CurrentSymbolID`<a href="method-currentsymbolid" id="method-currentsymbolid"></a>
===
```csharp
public string CurrentSymbolID()
```

***  

## `FormatAvgSize`<a href="method-formatavgsize" id="method-formatavgsize"></a>
===
```csharp
public string FormatAvgSize(double size, bool f = false)
```

`size` <mark style="color:red;">*`double`*</mark>  
 *===*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `FormatFullSize`<a href="method-formatfullsize" id="method-formatfullsize"></a>
===
```csharp
public string FormatFullSize(long size, bool f = false)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `FormatFullSize`<a href="method-formatfullsize" id="method-formatfullsize"></a>
===
```csharp
public string FormatFullSize(long size, bool f = false)
public string FormatFullSize(long size, IFormatProvider provider, bool f = false)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *===*  

`provider` <mark style="color:red;">*`IFormatProvider`*</mark>  
 *===*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `FormatFullSize`<a href="method-formatfullsize" id="method-formatfullsize"></a>
===
```csharp
public string FormatFullSize(long size, bool f = false)
public string FormatFullSize(long size, IFormatProvider provider, bool f = false)
public string FormatFullSize(long? size, bool f = false)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *===*  

`provider` <mark style="color:red;">*`IFormatProvider`*</mark>  
 *===*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `FormatPnl`<a href="method-formatpnl" id="method-formatpnl"></a>
===
```csharp
public string FormatPnl(double pnl, bool f = false)
```
`pnl` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `FormatPnl`<a href="method-formatpnl" id="method-formatpnl"></a>
===
```csharp
public string FormatPnl(double pnl, bool f = false)
public string FormatPnl(double? pnl, bool f = false)
```
`pnl` <mark style="color:red;">*`double`*</mark>  
 *===*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `FormatPrice`<a href="method-formatprice" id="method-formatprice"></a>
===
```csharp
public string FormatPrice(long price, bool f = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `FormatPrice`<a href="method-formatprice" id="method-formatprice"></a>
===
```csharp
public string FormatPrice(long price, bool f = false)
public string FormatPrice(long price, IFormatProvider provider, bool f = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *===*  

`provider` <mark style="color:red;">*`IFormatProvider`*</mark>  
 *===*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `FormatPrice`<a href="method-formatprice" id="method-formatprice"></a>
===
```csharp
public string FormatPrice(long price, bool f = false)
public string FormatPrice(long price, IFormatProvider provider, bool f = false)
public string FormatPrice(double price, bool f = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *===*  

`provider` <mark style="color:red;">*`IFormatProvider`*</mark>  
 *===*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`price` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `FormatPrice`<a href="method-formatprice" id="method-formatprice"></a>
===
```csharp
public string FormatPrice(long price, bool f = false)
public string FormatPrice(long price, IFormatProvider provider, bool f = false)
public string FormatPrice(double price, bool f = false)
public string FormatPrice(double? price, bool f = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *===*  

`provider` <mark style="color:red;">*`IFormatProvider`*</mark>  
 *===*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`price` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `FormatSize`<a href="method-formatsize" id="method-formatsize"></a>
===
```csharp
public string FormatSize(long size)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `FormatSize`<a href="method-formatsize" id="method-formatsize"></a>
===
```csharp
public string FormatSize(long size)
public string FormatSize(double size, bool f = false)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *===*  

`size` <mark style="color:red;">*`double`*</mark>  
 *===*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `FormatTime`<a href="method-formattime" id="method-formattime"></a>
===
```csharp
public string FormatTime(DateTime dt, string format)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`format` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `FormatTime`<a href="method-formattime" id="method-formattime"></a>
===
```csharp
public string FormatTime(DateTime dt, string format)
public string FormatTime(DateTime dt, string dateFormat, string timeFormat)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  

`format` <mark style="color:red;">*`string`*</mark>  
 *===*  

`dateFormat` <mark style="color:red;">*`string`*</mark>  
 *===*  

`timeFormat` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetBaseCurrency`<a href="method-getbasecurrency" id="method-getbasecurrency"></a>
===
```csharp
public string GetBaseCurrency()
```

***  

## `GetContracts`<a href="method-getcontracts" id="method-getcontracts"></a>
===
```csharp
public List<Symbol> GetContracts()
```

***  

## `GetRealPrice`<a href="method-getrealprice" id="method-getrealprice"></a>
===
```csharp
public double GetRealPrice(long price)
```

`price` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `GetRealSize`<a href="method-getrealsize" id="method-getrealsize"></a>
===
```csharp
public double GetRealSize(long size)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `GetShortPrice`<a href="method-getshortprice" id="method-getshortprice"></a>
===
```csharp
public long GetShortPrice(double price)
```
`price` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `GetShortSize`<a href="method-getshortsize" id="method-getshortsize"></a>
===
```csharp
public long GetShortSize(double size)
```
`size` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `GetStepPrice`<a href="method-getstepprice" id="method-getstepprice"></a>
===
```csharp
public double GetStepPrice()
```

***  

## `GetSymbol`<a href="method-getsymbol" id="method-getsymbol"></a>
===
```csharp
public Symbol GetSymbol()
```

***  

## `GetSymbol`<a href="method-getsymbol" id="method-getsymbol"></a>
===
```csharp
public Symbol GetSymbol()
public Symbol GetSymbol(DateTime date)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *===*  


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
===
```csharp
public override string ToString()
```

***  

## `UpdateFields`<a href="method-updatefields" id="method-updatefields"></a>
===
```csharp
public void UpdateFields(Symbol symbol)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `AdditionalData`<a href="property-additionaldata" id="property-additionaldata"></a>
===
```csharp
public Hashtable AdditionalData { get; set; }
```  
***

## `ContactValue`<a href="property-contactvalue" id="property-contactvalue"></a>
===
```csharp
public double ContactValue { get; set; }
```  
***

## `Currency`<a href="property-currency" id="property-currency"></a>
===
```csharp
public string Currency { get; internal set; }
```  
***

## `Description`<a href="property-description" id="property-description"></a>
===
```csharp
public string Description { get; internal set; }
```  
***

## `Exchange`<a href="property-exchange" id="property-exchange"></a>
===
```csharp
public string Exchange { get; internal set; }
```  
***

## `Expiration`<a href="property-expiration" id="property-expiration"></a>
===
```csharp
public DateTime Expiration { get; private set; }
```  
***

## `ID`<a href="property-id" id="property-id"></a>
===
```csharp
public string ID { get; }
```  
***

## `IsBinance`<a href="property-isbinance" id="property-isbinance"></a>
===
```csharp
public bool IsBinance { get; }
```  
***

## `IsBitFinex`<a href="property-isbitfinex" id="property-isbitfinex"></a>
===
```csharp
public bool IsBitFinex { get; }
```  
***

## `IsBitMEX`<a href="property-isbitmex" id="property-isbitmex"></a>
===
```csharp
public bool IsBitMEX { get; }
```  
***

## `IsBybit`<a href="property-isbybit" id="property-isbybit"></a>
===
```csharp
public bool IsBybit { get; }
```  
***

## `IsCrypto`<a href="property-iscrypto" id="property-iscrypto"></a>
===
```csharp
public bool IsCrypto { get; }
```  
***

## `IsCryptoFuture`<a href="property-iscryptofuture" id="property-iscryptofuture"></a>
===
```csharp
public bool IsCryptoFuture { get; }
```  
***

## `IsDeleted`<a href="property-isdeleted" id="property-isdeleted"></a>
===
```csharp
public bool IsDeleted { get; set; }
```  
***

## `IsDeribit`<a href="property-isderibit" id="property-isderibit"></a>
===
```csharp
public bool IsDeribit { get; }
```  
***

## `IsFTX`<a href="property-isftx" id="property-isftx"></a>
===
```csharp
public bool IsFTX { get; }
```  
***

## `IsHitBTC`<a href="property-ishitbtc" id="property-ishitbtc"></a>
===
```csharp
public bool IsHitBTC { get; }
```  
***

## `IsLinkable`<a href="property-islinkable" id="property-islinkable"></a>
===
```csharp
public bool IsLinkable { get; }
```  
***

## `IsMaster`<a href="property-ismaster" id="property-ismaster"></a>
===
```csharp
public bool IsMaster { get; }
```  
***

## `IsOKX`<a href="property-isokx" id="property-isokx"></a>
===
```csharp
public bool IsOKX { get; }
```  
***

## `IsSplicedFutures`<a href="property-issplicedfutures" id="property-issplicedfutures"></a>
===
```csharp
public bool IsSplicedFutures { get; private set; }
```  
***

## `LongCode`<a href="property-longcode" id="property-longcode"></a>
===
```csharp
public string LongCode { get; set; }
```  
***

## `LotSize`<a href="property-lotsize" id="property-lotsize"></a>
===
```csharp
public int LotSize { get; internal set; }
```  
***

## `LotStep`<a href="property-lotstep" id="property-lotstep"></a>
===
```csharp
public double LotStep { get; internal set; }
```  
***

## `Mapping`<a href="property-mapping" id="property-mapping"></a>
===
```csharp
public string Mapping { get; internal set; }
```  
***

## `Master`<a href="property-master" id="property-master"></a>
===
```csharp
public Symbol Master { get; }
```  
***

## `MinNotional`<a href="property-minnotional" id="property-minnotional"></a>
===
```csharp
public double MinNotional { get; internal set; }
```  
***

## `MinQty`<a href="property-minqty" id="property-minqty"></a>
===
```csharp
public double MinQty { get; internal set; }
```  
***

## `Name`<a href="property-name" id="property-name"></a>
===
```csharp
public string Name { get; internal set; }
```  
***

## `OptAsset`<a href="property-optasset" id="property-optasset"></a>
===
```csharp
public string OptAsset { get; set; }
```  
***

## `OptStrike`<a href="property-optstrike" id="property-optstrike"></a>
===
```csharp
public double OptStrike { get; set; }
```  
***

## `OptType`<a href="property-opttype" id="property-opttype"></a>
===
```csharp
public SymbolOptType OptType { get; set; }
```  
***

## `PnlPrecision`<a href="property-pnlprecision" id="property-pnlprecision"></a>
===
```csharp
public int PnlPrecision { get; internal set; }
```  
***

## `Precision`<a href="property-precision" id="property-precision"></a>
===
```csharp
public int Precision { get; internal set; }
```  
***

## `SizePrecision`<a href="property-sizeprecision" id="property-sizeprecision"></a>
===
```csharp
public int SizePrecision { get; set; }
```  
***

## `SizeStep`<a href="property-sizestep" id="property-sizestep"></a>
===
```csharp
public double SizeStep { get; internal set; }
```  
***

## `SpecChangeUtcDate`<a href="property-specchangeutcdate" id="property-specchangeutcdate"></a>
===
```csharp
public DateTime SpecChangeUtcDate { get; set; }
```  
***

## `Step`<a href="property-step" id="property-step"></a>
===
```csharp
public double Step { get; internal set; }
```  
***

## `Type`<a href="property-type" id="property-type"></a>
===
```csharp
public SymbolType Type { get; }
```  
***

