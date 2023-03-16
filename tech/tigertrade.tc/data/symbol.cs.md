# Symbol

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class Symbol
```

## Список методов

| Название                                                           | Описание |
| ------------------------------------------------------------------ | -------- |
| [`CheckContract`](symbol.cs.md#method-checkcontract)               | _===_    |
| [`ConvertTimeFromLocal`](symbol.cs.md#method-converttimefromlocal) | _===_    |
| [`ConvertTimeToLocal`](symbol.cs.md#method-converttimetolocal)     | _===_    |
| [`CurrentSymbolID`](symbol.cs.md#method-currentsymbolid)           | _===_    |
| [`FormatAvgSize`](symbol.cs.md#method-formatavgsize)               | _===_    |
| [`FormatFullSize`](symbol.cs.md#method-formatfullsize)             | _===_    |
| [`FormatPnl`](symbol.cs.md#method-formatpnl)                       | _===_    |
| [`FormatPrice`](symbol.cs.md#method-formatprice)                   | _===_    |
| [`FormatSize`](symbol.cs.md#method-formatsize)                     | _===_    |
| [`FormatTime`](symbol.cs.md#method-formattime)                     | _===_    |
| [`GetBaseCurrency`](symbol.cs.md#method-getbasecurrency)           | _===_    |
| [`GetContracts`](symbol.cs.md#method-getcontracts)                 | _===_    |
| [`GetRealPrice`](symbol.cs.md#method-getrealprice)                 | _===_    |
| [`GetRealSize`](symbol.cs.md#method-getrealsize)                   | _===_    |
| [`GetShortPrice`](symbol.cs.md#method-getshortprice)               | _===_    |
| [`GetShortSize`](symbol.cs.md#method-getshortsize)                 | _===_    |
| [`GetStepPrice`](symbol.cs.md#method-getstepprice)                 | _===_    |
| [`GetSymbol`](symbol.cs.md#method-getsymbol)                       | _===_    |
| [`ToString`](symbol.cs.md#method-tostring)                         | _===_    |
| [`UpdateFields`](symbol.cs.md#method-updatefields)                 | _===_    |

## Список свойств

| Название                                                       | Описание |
| -------------------------------------------------------------- | -------- |
| [`AdditionalData`](symbol.cs.md#property-additionaldata)       | _===_    |
| [`ContactValue`](symbol.cs.md#property-contactvalue)           | _===_    |
| [`Currency`](symbol.cs.md#property-currency)                   | _===_    |
| [`Description`](symbol.cs.md#property-description)             | _===_    |
| [`Exchange`](symbol.cs.md#property-exchange)                   | _===_    |
| [`Expiration`](symbol.cs.md#property-expiration)               | _===_    |
| [`ID`](symbol.cs.md#property-id)                               | _===_    |
| [`IsBinance`](symbol.cs.md#property-isbinance)                 | _===_    |
| [`IsBitFinex`](symbol.cs.md#property-isbitfinex)               | _===_    |
| [`IsBitMEX`](symbol.cs.md#property-isbitmex)                   | _===_    |
| [`IsBybit`](symbol.cs.md#property-isbybit)                     | _===_    |
| [`IsCrypto`](symbol.cs.md#property-iscrypto)                   | _===_    |
| [`IsCryptoFuture`](symbol.cs.md#property-iscryptofuture)       | _===_    |
| [`IsDeleted`](symbol.cs.md#property-isdeleted)                 | _===_    |
| [`IsDeribit`](symbol.cs.md#property-isderibit)                 | _===_    |
| [`IsFTX`](symbol.cs.md#property-isftx)                         | _===_    |
| [`IsHitBTC`](symbol.cs.md#property-ishitbtc)                   | _===_    |
| [`IsLinkable`](symbol.cs.md#property-islinkable)               | _===_    |
| [`IsMaster`](symbol.cs.md#property-ismaster)                   | _===_    |
| [`IsOKX`](symbol.cs.md#property-isokx)                         | _===_    |
| [`IsSplicedFutures`](symbol.cs.md#property-issplicedfutures)   | _===_    |
| [`LongCode`](symbol.cs.md#property-longcode)                   | _===_    |
| [`LotSize`](symbol.cs.md#property-lotsize)                     | _===_    |
| [`LotStep`](symbol.cs.md#property-lotstep)                     | _===_    |
| [`Mapping`](symbol.cs.md#property-mapping)                     | _===_    |
| [`Master`](symbol.cs.md#property-master)                       | _===_    |
| [`MinNotional`](symbol.cs.md#property-minnotional)             | _===_    |
| [`MinQty`](symbol.cs.md#property-minqty)                       | _===_    |
| [`Name`](symbol.cs.md#property-name)                           | _===_    |
| [`OptAsset`](symbol.cs.md#property-optasset)                   | _===_    |
| [`OptStrike`](symbol.cs.md#property-optstrike)                 | _===_    |
| [`OptType`](symbol.cs.md#property-opttype)                     | _===_    |
| [`PnlPrecision`](symbol.cs.md#property-pnlprecision)           | _===_    |
| [`Precision`](symbol.cs.md#property-precision)                 | _===_    |
| [`SizePrecision`](symbol.cs.md#property-sizeprecision)         | _===_    |
| [`SizeStep`](symbol.cs.md#property-sizestep)                   | _===_    |
| [`SpecChangeUtcDate`](symbol.cs.md#property-specchangeutcdate) | _===_    |
| [`Step`](symbol.cs.md#property-step)                           | _===_    |
| [`Type`](symbol.cs.md#property-type)                           | _===_    |

***

***

## Методы

### `CheckContract` <a href="#method-checkcontract" id="method-checkcontract"></a>

\===

```csharp
public bool CheckContract(string symbolID)
```

`symbolID` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `CheckContract` <a href="#method-checkcontract" id="method-checkcontract"></a>

\===

```csharp
public bool CheckContract(string symbolID)
public bool CheckContract(Symbol symbol)
```

`symbolID` _<mark style="color:red;">`string`</mark>_\
_===_

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

***

### `ConvertTimeFromLocal` <a href="#method-converttimefromlocal" id="method-converttimefromlocal"></a>

\===

```csharp
public DateTime ConvertTimeFromLocal(DateTime dt)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

***

### `ConvertTimeToLocal` <a href="#method-converttimetolocal" id="method-converttimetolocal"></a>

\===

```csharp
public DateTime ConvertTimeToLocal(DateTime dt)
```

***

### `CurrentSymbolID` <a href="#method-currentsymbolid" id="method-currentsymbolid"></a>

\===

```csharp
public string CurrentSymbolID()
```

***

### `FormatAvgSize` <a href="#method-formatavgsize" id="method-formatavgsize"></a>

\===

```csharp
public string FormatAvgSize(double size, bool f = false)
```

`size` _<mark style="color:red;">`double`</mark>_\
_===_

`f` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `FormatFullSize` <a href="#method-formatfullsize" id="method-formatfullsize"></a>

\===

```csharp
public string FormatFullSize(long size, bool f = false)
```

`size` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `FormatFullSize` <a href="#method-formatfullsize" id="method-formatfullsize"></a>

\===

```csharp
public string FormatFullSize(long size, bool f = false)
public string FormatFullSize(long size, IFormatProvider provider, bool f = false)
```

`size` _<mark style="color:red;">`long`</mark>_\
_===_

`provider` _<mark style="color:red;">`IFormatProvider`</mark>_\
_===_

`f` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `FormatFullSize` <a href="#method-formatfullsize" id="method-formatfullsize"></a>

\===

```csharp
public string FormatFullSize(long size, bool f = false)
public string FormatFullSize(long size, IFormatProvider provider, bool f = false)
public string FormatFullSize(long? size, bool f = false)
```

`size` _<mark style="color:red;">`long`</mark>_\
_===_

`provider` _<mark style="color:red;">`IFormatProvider`</mark>_\
_===_

`f` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `FormatPnl` <a href="#method-formatpnl" id="method-formatpnl"></a>

\===

```csharp
public string FormatPnl(double pnl, bool f = false)
```

`pnl` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `FormatPnl` <a href="#method-formatpnl" id="method-formatpnl"></a>

\===

```csharp
public string FormatPnl(double pnl, bool f = false)
public string FormatPnl(double? pnl, bool f = false)
```

`pnl` _<mark style="color:red;">`double`</mark>_\
_===_

`f` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `FormatPrice` <a href="#method-formatprice" id="method-formatprice"></a>

\===

```csharp
public string FormatPrice(long price, bool f = false)
```

`price` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `FormatPrice` <a href="#method-formatprice" id="method-formatprice"></a>

\===

```csharp
public string FormatPrice(long price, bool f = false)
public string FormatPrice(long price, IFormatProvider provider, bool f = false)
```

`price` _<mark style="color:red;">`long`</mark>_\
_===_

`provider` _<mark style="color:red;">`IFormatProvider`</mark>_\
_===_

`f` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `FormatPrice` <a href="#method-formatprice" id="method-formatprice"></a>

\===

```csharp
public string FormatPrice(long price, bool f = false)
public string FormatPrice(long price, IFormatProvider provider, bool f = false)
public string FormatPrice(double price, bool f = false)
```

`price` _<mark style="color:red;">`long`</mark>_\
_===_

`provider` _<mark style="color:red;">`IFormatProvider`</mark>_\
_===_

`f` _<mark style="color:red;">`bool`</mark>_\
_===_

`price` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `FormatPrice` <a href="#method-formatprice" id="method-formatprice"></a>

\===

```csharp
public string FormatPrice(long price, bool f = false)
public string FormatPrice(long price, IFormatProvider provider, bool f = false)
public string FormatPrice(double price, bool f = false)
public string FormatPrice(double? price, bool f = false)
```

`price` _<mark style="color:red;">`long`</mark>_\
_===_

`provider` _<mark style="color:red;">`IFormatProvider`</mark>_\
_===_

`f` _<mark style="color:red;">`bool`</mark>_\
_===_

`price` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `FormatSize` <a href="#method-formatsize" id="method-formatsize"></a>

\===

```csharp
public string FormatSize(long size)
```

`size` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `FormatSize` <a href="#method-formatsize" id="method-formatsize"></a>

\===

```csharp
public string FormatSize(long size)
public string FormatSize(double size, bool f = false)
```

`size` _<mark style="color:red;">`long`</mark>_\
_===_

`size` _<mark style="color:red;">`double`</mark>_\
_===_

`f` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `FormatTime` <a href="#method-formattime" id="method-formattime"></a>

\===

```csharp
public string FormatTime(DateTime dt, string format)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`format` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `FormatTime` <a href="#method-formattime" id="method-formattime"></a>

\===

```csharp
public string FormatTime(DateTime dt, string format)
public string FormatTime(DateTime dt, string dateFormat, string timeFormat)
```

`dt` _<mark style="color:red;">`DateTime`</mark>_\
_===_

`format` _<mark style="color:red;">`string`</mark>_\
_===_

`dateFormat` _<mark style="color:red;">`string`</mark>_\
_===_

`timeFormat` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetBaseCurrency` <a href="#method-getbasecurrency" id="method-getbasecurrency"></a>

\===

```csharp
public string GetBaseCurrency()
```

***

### `GetContracts` <a href="#method-getcontracts" id="method-getcontracts"></a>

\===

```csharp
public List<Symbol> GetContracts()
```

***

### `GetRealPrice` <a href="#method-getrealprice" id="method-getrealprice"></a>

\===

```csharp
public double GetRealPrice(long price)
```

`price` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `GetRealSize` <a href="#method-getrealsize" id="method-getrealsize"></a>

\===

```csharp
public double GetRealSize(long size)
```

`size` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `GetShortPrice` <a href="#method-getshortprice" id="method-getshortprice"></a>

\===

```csharp
public long GetShortPrice(double price)
```

`price` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `GetShortSize` <a href="#method-getshortsize" id="method-getshortsize"></a>

\===

```csharp
public long GetShortSize(double size)
```

`size` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `GetStepPrice` <a href="#method-getstepprice" id="method-getstepprice"></a>

\===

```csharp
public double GetStepPrice()
```

***

### `GetSymbol` <a href="#method-getsymbol" id="method-getsymbol"></a>

\===

```csharp
public Symbol GetSymbol()
```

***

### `GetSymbol` <a href="#method-getsymbol" id="method-getsymbol"></a>

\===

```csharp
public Symbol GetSymbol()
public Symbol GetSymbol(DateTime date)
```

`date` _<mark style="color:red;">`DateTime`</mark>_\
_===_

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

***

### `UpdateFields` <a href="#method-updatefields" id="method-updatefields"></a>

\===

```csharp
public void UpdateFields(Symbol symbol)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

***

***

***

## Свойства

### `AdditionalData` <a href="#property-additionaldata" id="property-additionaldata"></a>

\===

```csharp
public Hashtable AdditionalData { get; set; }
```

***

### `ContactValue` <a href="#property-contactvalue" id="property-contactvalue"></a>

\===

```csharp
public double ContactValue { get; set; }
```

***

### `Currency` <a href="#property-currency" id="property-currency"></a>

\===

```csharp
public string Currency { get; internal set; }
```

***

### `Description` <a href="#property-description" id="property-description"></a>

\===

```csharp
public string Description { get; internal set; }
```

***

### `Exchange` <a href="#property-exchange" id="property-exchange"></a>

\===

```csharp
public string Exchange { get; internal set; }
```

***

### `Expiration` <a href="#property-expiration" id="property-expiration"></a>

\===

```csharp
public DateTime Expiration { get; private set; }
```

***

### `ID` <a href="#property-id" id="property-id"></a>

\===

```csharp
public string ID { get; }
```

***

### `IsBinance` <a href="#property-isbinance" id="property-isbinance"></a>

\===

```csharp
public bool IsBinance { get; }
```

***

### `IsBitFinex` <a href="#property-isbitfinex" id="property-isbitfinex"></a>

\===

```csharp
public bool IsBitFinex { get; }
```

***

### `IsBitMEX` <a href="#property-isbitmex" id="property-isbitmex"></a>

\===

```csharp
public bool IsBitMEX { get; }
```

***

### `IsBybit` <a href="#property-isbybit" id="property-isbybit"></a>

\===

```csharp
public bool IsBybit { get; }
```

***

### `IsCrypto` <a href="#property-iscrypto" id="property-iscrypto"></a>

\===

```csharp
public bool IsCrypto { get; }
```

***

### `IsCryptoFuture` <a href="#property-iscryptofuture" id="property-iscryptofuture"></a>

\===

```csharp
public bool IsCryptoFuture { get; }
```

***

### `IsDeleted` <a href="#property-isdeleted" id="property-isdeleted"></a>

\===

```csharp
public bool IsDeleted { get; set; }
```

***

### `IsDeribit` <a href="#property-isderibit" id="property-isderibit"></a>

\===

```csharp
public bool IsDeribit { get; }
```

***

### `IsFTX` <a href="#property-isftx" id="property-isftx"></a>

\===

```csharp
public bool IsFTX { get; }
```

***

### `IsHitBTC` <a href="#property-ishitbtc" id="property-ishitbtc"></a>

\===

```csharp
public bool IsHitBTC { get; }
```

***

### `IsLinkable` <a href="#property-islinkable" id="property-islinkable"></a>

\===

```csharp
public bool IsLinkable { get; }
```

***

### `IsMaster` <a href="#property-ismaster" id="property-ismaster"></a>

\===

```csharp
public bool IsMaster { get; }
```

***

### `IsOKX` <a href="#property-isokx" id="property-isokx"></a>

\===

```csharp
public bool IsOKX { get; }
```

***

### `IsSplicedFutures` <a href="#property-issplicedfutures" id="property-issplicedfutures"></a>

\===

```csharp
public bool IsSplicedFutures { get; private set; }
```

***

### `LongCode` <a href="#property-longcode" id="property-longcode"></a>

\===

```csharp
public string LongCode { get; set; }
```

***

### `LotSize` <a href="#property-lotsize" id="property-lotsize"></a>

\===

```csharp
public int LotSize { get; internal set; }
```

***

### `LotStep` <a href="#property-lotstep" id="property-lotstep"></a>

\===

```csharp
public double LotStep { get; internal set; }
```

***

### `Mapping` <a href="#property-mapping" id="property-mapping"></a>

\===

```csharp
public string Mapping { get; internal set; }
```

***

### `Master` <a href="#property-master" id="property-master"></a>

\===

```csharp
public Symbol Master { get; }
```

***

### `MinNotional` <a href="#property-minnotional" id="property-minnotional"></a>

\===

```csharp
public double MinNotional { get; internal set; }
```

***

### `MinQty` <a href="#property-minqty" id="property-minqty"></a>

\===

```csharp
public double MinQty { get; internal set; }
```

***

### `Name` <a href="#property-name" id="property-name"></a>

\===

```csharp
public string Name { get; internal set; }
```

***

### `OptAsset` <a href="#property-optasset" id="property-optasset"></a>

\===

```csharp
public string OptAsset { get; set; }
```

***

### `OptStrike` <a href="#property-optstrike" id="property-optstrike"></a>

\===

```csharp
public double OptStrike { get; set; }
```

***

### `OptType` <a href="#property-opttype" id="property-opttype"></a>

\===

```csharp
public SymbolOptType OptType { get; set; }
```

***

### `PnlPrecision` <a href="#property-pnlprecision" id="property-pnlprecision"></a>

\===

```csharp
public int PnlPrecision { get; internal set; }
```

***

### `Precision` <a href="#property-precision" id="property-precision"></a>

\===

```csharp
public int Precision { get; internal set; }
```

***

### `SizePrecision` <a href="#property-sizeprecision" id="property-sizeprecision"></a>

\===

```csharp
public int SizePrecision { get; set; }
```

***

### `SizeStep` <a href="#property-sizestep" id="property-sizestep"></a>

\===

```csharp
public double SizeStep { get; internal set; }
```

***

### `SpecChangeUtcDate` <a href="#property-specchangeutcdate" id="property-specchangeutcdate"></a>

\===

```csharp
public DateTime SpecChangeUtcDate { get; set; }
```

***

### `Step` <a href="#property-step" id="property-step"></a>

\===

```csharp
public double Step { get; internal set; }
```

***

### `Type` <a href="#property-type" id="property-type"></a>

\===

```csharp
public SymbolType Type { get; }
```

***
