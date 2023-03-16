
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Symbol
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckContract`](./Symbol.cs/Методы/CheckContract.md) | *Описание* |
| [`ConvertTimeFromLocal`](./Symbol.cs/Методы/ConvertTimeFromLocal.md) | *Описание* |
| [`ConvertTimeToLocal`](./Symbol.cs/Методы/ConvertTimeToLocal.md) | *Описание* |
| [`CurrentSymbolID`](./Symbol.cs/Методы/CurrentSymbolID.md) | *Описание* |
| [`FormatAvgSize`](./Symbol.cs/Методы/FormatAvgSize.md) | *Описание* |
| [`FormatFullSize`](./Symbol.cs/Методы/FormatFullSize.md) | *Описание* |
| [`FormatPnl`](./Symbol.cs/Методы/FormatPnl.md) | *Описание* |
| [`FormatPrice`](./Symbol.cs/Методы/FormatPrice.md) | *Описание* |
| [`FormatSize`](./Symbol.cs/Методы/FormatSize.md) | *Описание* |
| [`FormatTime`](./Symbol.cs/Методы/FormatTime.md) | *Описание* |
| [`GetBaseCurrency`](./Symbol.cs/Методы/GetBaseCurrency.md) | *Описание* |
| [`GetContracts`](./Symbol.cs/Методы/GetContracts.md) | *Описание* |
| [`GetRealPrice`](./Symbol.cs/Методы/GetRealPrice.md) | *Описание* |
| [`GetRealSize`](./Symbol.cs/Методы/GetRealSize.md) | *Описание* |
| [`GetShortPrice`](./Symbol.cs/Методы/GetShortPrice.md) | *Описание* |
| [`GetShortSize`](./Symbol.cs/Методы/GetShortSize.md) | *Описание* |
| [`GetStepPrice`](./Symbol.cs/Методы/GetStepPrice.md) | *Описание* |
| [`GetSymbol`](./Symbol.cs/Методы/GetSymbol.md) | *Описание* |
| [`ToString`](./Symbol.cs/Методы/ToString.md) | *Описание* |
| [`UpdateFields`](./Symbol.cs/Методы/UpdateFields.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AdditionalData`](./Symbol.cs/Свойства/AdditionalData.md) | *Описание* |
| [`ContactValue`](./Symbol.cs/Свойства/ContactValue.md) | *Описание* |
| [`Currency`](./Symbol.cs/Свойства/Currency.md) | *Описание* |
| [`Description`](./Symbol.cs/Свойства/Description.md) | *Описание* |
| [`Exchange`](./Symbol.cs/Свойства/Exchange.md) | *Описание* |
| [`Expiration`](./Symbol.cs/Свойства/Expiration.md) | *Описание* |
| [`ID`](./Symbol.cs/Свойства/ID.md) | *Описание* |
| [`IsBinance`](./Symbol.cs/Свойства/IsBinance.md) | *Описание* |
| [`IsBitFinex`](./Symbol.cs/Свойства/IsBitFinex.md) | *Описание* |
| [`IsBitMEX`](./Symbol.cs/Свойства/IsBitMEX.md) | *Описание* |
| [`IsBybit`](./Symbol.cs/Свойства/IsBybit.md) | *Описание* |
| [`IsCrypto`](./Symbol.cs/Свойства/IsCrypto.md) | *Описание* |
| [`IsCryptoFuture`](./Symbol.cs/Свойства/IsCryptoFuture.md) | *Описание* |
| [`IsDeleted`](./Symbol.cs/Свойства/IsDeleted.md) | *Описание* |
| [`IsDeribit`](./Symbol.cs/Свойства/IsDeribit.md) | *Описание* |
| [`IsFTX`](./Symbol.cs/Свойства/IsFTX.md) | *Описание* |
| [`IsHitBTC`](./Symbol.cs/Свойства/IsHitBTC.md) | *Описание* |
| [`IsLinkable`](./Symbol.cs/Свойства/IsLinkable.md) | *Описание* |
| [`IsMaster`](./Symbol.cs/Свойства/IsMaster.md) | *Описание* |
| [`IsOKX`](./Symbol.cs/Свойства/IsOKX.md) | *Описание* |
| [`IsSplicedFutures`](./Symbol.cs/Свойства/IsSplicedFutures.md) | *Описание* |
| [`LongCode`](./Symbol.cs/Свойства/LongCode.md) | *Описание* |
| [`LotSize`](./Symbol.cs/Свойства/LotSize.md) | *Описание* |
| [`LotStep`](./Symbol.cs/Свойства/LotStep.md) | *Описание* |
| [`Mapping`](./Symbol.cs/Свойства/Mapping.md) | *Описание* |
| [`Master`](./Symbol.cs/Свойства/Master.md) | *Описание* |
| [`MinNotional`](./Symbol.cs/Свойства/MinNotional.md) | *Описание* |
| [`MinQty`](./Symbol.cs/Свойства/MinQty.md) | *Описание* |
| [`Name`](./Symbol.cs/Свойства/Name.md) | *Описание* |
| [`OptAsset`](./Symbol.cs/Свойства/OptAsset.md) | *Описание* |
| [`OptStrike`](./Symbol.cs/Свойства/OptStrike.md) | *Описание* |
| [`OptType`](./Symbol.cs/Свойства/OptType.md) | *Описание* |
| [`PnlPrecision`](./Symbol.cs/Свойства/PnlPrecision.md) | *Описание* |
| [`Precision`](./Symbol.cs/Свойства/Precision.md) | *Описание* |
| [`SizePrecision`](./Symbol.cs/Свойства/SizePrecision.md) | *Описание* |
| [`SizeStep`](./Symbol.cs/Свойства/SizeStep.md) | *Описание* |
| [`SpecChangeUtcDate`](./Symbol.cs/Свойства/SpecChangeUtcDate.md) | *Описание* |
| [`Step`](./Symbol.cs/Свойства/Step.md) | *Описание* |
| [`Type`](./Symbol.cs/Свойства/Type.md) | *Описание* |





***  
***  
# Методы

## `CheckContract<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CheckContract(string symbolID)
```

`symbolID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `CheckContract<a href="test" id="test"></a>`
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

## `ConvertTimeFromLocal<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime ConvertTimeFromLocal(DateTime dt)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ConvertTimeToLocal<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime ConvertTimeToLocal(DateTime dt)
```

***  

## `CurrentSymbolID<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string CurrentSymbolID()
```

***  

## `FormatAvgSize<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatAvgSize(double size, bool f = false)
```

`size` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`f` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `FormatFullSize<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatFullSize(long size, bool f = false)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatFullSize<a href="test" id="test"></a>`
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

## `FormatFullSize<a href="test" id="test"></a>`
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

## `FormatPnl<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatPnl(double pnl, bool f = false)
```
`pnl` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `FormatPnl<a href="test" id="test"></a>`
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

## `FormatPrice<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatPrice(long price, bool f = false)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatPrice<a href="test" id="test"></a>`
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

## `FormatPrice<a href="test" id="test"></a>`
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

## `FormatPrice<a href="test" id="test"></a>`
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

## `FormatSize<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatSize(long size)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `FormatSize<a href="test" id="test"></a>`
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

## `FormatTime<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string FormatTime(DateTime dt, string format)
```
`dt` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  

`format` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `FormatTime<a href="test" id="test"></a>`
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

## `GetBaseCurrency<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string GetBaseCurrency()
```

***  

## `GetContracts<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<Symbol> GetContracts()
```

***  

## `GetRealPrice<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetRealPrice(long price)
```

`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetRealSize<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetRealSize(long size)
```
`size` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetShortPrice<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long GetShortPrice(double price)
```
`price` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetShortSize<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long GetShortSize(double size)
```
`size` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `GetStepPrice<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetStepPrice()
```

***  

## `GetSymbol<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol GetSymbol()
```

***  

## `GetSymbol<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol GetSymbol()
public Symbol GetSymbol(DateTime date)
```

`date` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `ToString<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  

## `UpdateFields<a href="test" id="test"></a>`
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

## `AdditionalData`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Hashtable AdditionalData { get; set; }
```  
***

## `ContactValue`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double ContactValue { get; set; }
```  
***

## `Currency`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Currency { get; internal set; }
```  
***

## `Description`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Description { get; internal set; }
```  
***

## `Exchange`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Exchange { get; internal set; }
```  
***

## `Expiration`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Expiration { get; private set; }
```  
***

## `ID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `IsBinance`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBinance { get; }
```  
***

## `IsBitFinex`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBitFinex { get; }
```  
***

## `IsBitMEX`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBitMEX { get; }
```  
***

## `IsBybit`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsBybit { get; }
```  
***

## `IsCrypto`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsCrypto { get; }
```  
***

## `IsCryptoFuture`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsCryptoFuture { get; }
```  
***

## `IsDeleted`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsDeleted { get; set; }
```  
***

## `IsDeribit`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsDeribit { get; }
```  
***

## `IsFTX`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsFTX { get; }
```  
***

## `IsHitBTC`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsHitBTC { get; }
```  
***

## `IsLinkable`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsLinkable { get; }
```  
***

## `IsMaster`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsMaster { get; }
```  
***

## `IsOKX`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsOKX { get; }
```  
***

## `IsSplicedFutures`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSplicedFutures { get; private set; }
```  
***

## `LongCode`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string LongCode { get; set; }
```  
***

## `LotSize`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LotSize { get; internal set; }
```  
***

## `LotStep`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double LotStep { get; internal set; }
```  
***

## `Mapping`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Mapping { get; internal set; }
```  
***

## `Master`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Master { get; }
```  
***

## `MinNotional`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinNotional { get; internal set; }
```  
***

## `MinQty`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double MinQty { get; internal set; }
```  
***

## `Name`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; internal set; }
```  
***

## `OptAsset`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string OptAsset { get; set; }
```  
***

## `OptStrike`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double OptStrike { get; set; }
```  
***

## `OptType`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public SymbolOptType OptType { get; set; }
```  
***

## `PnlPrecision`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int PnlPrecision { get; internal set; }
```  
***

## `Precision`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Precision { get; internal set; }
```  
***

## `SizePrecision`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int SizePrecision { get; set; }
```  
***

## `SizeStep`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double SizeStep { get; internal set; }
```  
***

## `SpecChangeUtcDate`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime SpecChangeUtcDate { get; set; }
```  
***

## `Step`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Step { get; internal set; }
```  
***

## `Type`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public SymbolType Type { get; }
```  
***

