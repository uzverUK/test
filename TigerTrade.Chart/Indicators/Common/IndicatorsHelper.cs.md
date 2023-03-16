
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


Описание

### Синтаксис
```csharp
public sealed class IndicatorsHelper
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AC`](#method-ac) | *Описание* |
| [`AD`](#method-ad) | *Описание* |
| [`ADX`](#method-adx) | *Описание* |
| [`AO`](#method-ao) | *Описание* |
| [`ATR`](#method-atr) | *Описание* |
| [`Aroon`](#method-aroon) | *Описание* |
| [`BWMFI`](#method-bwmfi) | *Описание* |
| [`BearsPower`](#method-bearspower) | *Описание* |
| [`BullsPower`](#method-bullspower) | *Описание* |
| [`CCI`](#method-cci) | *Описание* |
| [`CMF`](#method-cmf) | *Описание* |
| [`CMO`](#method-cmo) | *Описание* |
| [`CO`](#method-co) | *Описание* |
| [`ChaikinsVolatility`](#method-chaikinsvolatility) | *Описание* |
| [`CumDelta`](#method-cumdelta) | *Описание* |
| [`EFI`](#method-efi) | *Описание* |
| [`Fractal`](#method-fractal) | *Описание* |
| [`IndicatorsHelper`](#method-indicatorshelper) | *Описание* |
| [`LinReg`](#method-linreg) | *Описание* |
| [`MFI`](#method-mfi) | *Описание* |
| [`Max`](#method-max) | *Описание* |
| [`MedianPrice`](#method-medianprice) | *Описание* |
| [`Min`](#method-min) | *Описание* |
| [`MinusDI`](#method-minusdi) | *Описание* |
| [`Momentum`](#method-momentum) | *Описание* |
| [`MovingAverage`](#method-movingaverage) | *Описание* |
| [`OBV`](#method-obv) | *Описание* |
| [`PPO`](#method-ppo) | *Описание* |
| [`PlusDI`](#method-plusdi) | *Описание* |
| [`Price`](#method-price) | *Описание* |
| [`PriceChannel`](#method-pricechannel) | *Описание* |
| [`ROC`](#method-roc) | *Описание* |
| [`RSI`](#method-rsi) | *Описание* |
| [`SAR`](#method-sar) | *Описание* |
| [`SMMA`](#method-smma) | *Описание* |
| [`SetDataProvider`](#method-setdataprovider) | *Описание* |
| [`ShiftData`](#method-shiftdata) | *Описание* |
| [`StdDev`](#method-stddev) | *Описание* |
| [`Subtraction`](#method-subtraction) | *Описание* |
| [`TRIX`](#method-trix) | *Описание* |
| [`TypicalPrice`](#method-typicalprice) | *Описание* |
| [`UltOsc`](#method-ultosc) | *Описание* |
| [`VHF`](#method-vhf) | *Описание* |
| [`Variance`](#method-variance) | *Описание* |
| [`VolumeOscillator`](#method-volumeoscillator) | *Описание* |
| [`WilliamsAD`](#method-williamsad) | *Описание* |
| [`WilliamsR`](#method-williamsr) | *Описание* |
| [`ZIGZAG`](#method-zigzag) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Ask`](#property-ask) | *Описание* |
| [`Bid`](#property-bid) | *Описание* |
| [`Close`](#property-close) | *Описание* |
| [`Count`](#property-count) | *Описание* |
| [`DataProvider`](#property-dataprovider) | *Описание* |
| [`Date`](#property-date) | *Описание* |
| [`Delta`](#property-delta) | *Описание* |
| [`High`](#property-high) | *Описание* |
| [`Low`](#property-low) | *Описание* |
| [`Open`](#property-open) | *Описание* |
| [`OpenPos`](#property-openpos) | *Описание* |
| [`OpenPosAskChg`](#property-openposaskchg) | *Описание* |
| [`OpenPosBidChg`](#property-openposbidchg) | *Описание* |
| [`OpenPosChg`](#property-openposchg) | *Описание* |
| [`Poc`](#property-poc) | *Описание* |
| [`Trades`](#property-trades) | *Описание* |
| [`Volume`](#property-volume) | *Описание* |





***  
***  
# Методы

## `AC`<a href="method-ac" id="method-ac"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] AC(IndicatorMaType type, int shortN, int longN)
```

`type` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *Описание*  

`shortN` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`longN` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `AD`<a href="method-ad" id="method-ad"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] AD()
```

***  

## `ADX`<a href="method-adx" id="method-adx"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] ADX(int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `AO`<a href="method-ao" id="method-ao"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] AO(IndicatorMaType type, int shortN, int longN)
```
`type` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *Описание*  

`shortN` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`longN` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `ATR`<a href="method-atr" id="method-atr"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] ATR(int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `Aroon`<a href="method-aroon" id="method-aroon"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Aroon(int period, out double[] aroonUp, out double[] aroonDown)
```
`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  

`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  


***  

## `BWMFI`<a href="method-bwmfi" id="method-bwmfi"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] BWMFI(IndicatorBWMFIType volumeType = IndicatorBWMFIType.Ticks)
```
`volumeType` <mark style="color:red;">*`IndicatorBWMFIType`*</mark>  
 *Описание*  


***  

## `BearsPower`<a href="method-bearspower" id="method-bearspower"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] BearsPower(int n)
```
`n` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `BullsPower`<a href="method-bullspower" id="method-bullspower"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] BullsPower(int n)
```

***  

## `CCI`<a href="method-cci" id="method-cci"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] CCI(int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `CMF`<a href="method-cmf" id="method-cmf"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] CMF(int n)
```
`n` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `CMO`<a href="method-cmo" id="method-cmo"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] CMO(double[] d, int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `CO`<a href="method-co" id="method-co"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] CO(IndicatorMaType maType, int shortPeriod, int longPeriod)
```
`maType` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *Описание*  

`shortPeriod` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`longPeriod` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `ChaikinsVolatility`<a href="method-chaikinsvolatility" id="method-chaikinsvolatility"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] ChaikinsVolatility(IndicatorMaType type, int n)
```
`type` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *Описание*  

`n` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `CumDelta`<a href="method-cumdelta" id="method-cumdelta"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] CumDelta()
```

***  

## `EFI`<a href="method-efi" id="method-efi"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] EFI(double[] d, IndicatorMaType type, int n)
```

`type` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *Описание*  

`n` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `Fractal`<a href="method-fractal" id="method-fractal"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Fractal(int n, out double[] up, out double[] down)
```
`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  

`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  


***  

## `IndicatorsHelper`<a href="method-indicatorshelper" id="method-indicatorshelper"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IndicatorsHelper()
```

***  

## `LinReg`<a href="method-linreg" id="method-linreg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] LinReg(double[] d, int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `MFI`<a href="method-mfi" id="method-mfi"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] MFI(int period)
```

***  

## `Max`<a href="method-max" id="method-max"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Max(double[] d, int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `MedianPrice`<a href="method-medianprice" id="method-medianprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] MedianPrice()
```

***  

## `Min`<a href="method-min" id="method-min"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Min(double[] d, int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `MinusDI`<a href="method-minusdi" id="method-minusdi"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] MinusDI(int period)
```

***  

## `Momentum`<a href="method-momentum" id="method-momentum"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Momentum(double[] d, int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `MovingAverage`<a href="method-movingaverage" id="method-movingaverage"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] MovingAverage(IndicatorMaType maType, double[] d, int period)
```
`maType` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *Описание*  


***  

## `OBV`<a href="method-obv" id="method-obv"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] OBV()
```

***  

## `PPO`<a href="method-ppo" id="method-ppo"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] PPO(IndicatorMaType maType, double[] d, int shortPeriod, int longPeriod)
```

`maType` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *Описание*  

`shortPeriod` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`longPeriod` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `PlusDI`<a href="method-plusdi" id="method-plusdi"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] PlusDI(int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `Price`<a href="method-price" id="method-price"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Price(IndicatorPriceType priceField)
```
`priceField` <mark style="color:red;">*`IndicatorPriceType`*</mark>  
 *Описание*  


***  

## `PriceChannel`<a href="method-pricechannel" id="method-pricechannel"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void PriceChannel(int n, out double[] avg, out double[] upper, out double[] lower)
```
`n` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  

`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  

`double` <mark style="color:red;">*`out`*</mark>  
 *Описание*  


***  

## `ROC`<a href="method-roc" id="method-roc"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] ROC(double[] d, int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `RSI`<a href="method-rsi" id="method-rsi"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] RSI(double[] d, int period)
```

***  

## `SAR`<a href="method-sar" id="method-sar"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] SAR(double step, double maxp)
```

`step` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`maxp` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `SMMA`<a href="method-smma" id="method-smma"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] SMMA(double[] d, int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `SetDataProvider`<a href="method-setdataprovider" id="method-setdataprovider"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void SetDataProvider(IChartDataProvider dp)
```
`dp` <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *Описание*  


***  

## `ShiftData`<a href="method-shiftdata" id="method-shiftdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] ShiftData(double[] data, int shift)
```
`shift` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `StdDev`<a href="method-stddev" id="method-stddev"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] StdDev(double[] d, int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `Subtraction`<a href="method-subtraction" id="method-subtraction"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Subtraction(double[] d1, double[] d2)
```

***  

## `TRIX`<a href="method-trix" id="method-trix"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] TRIX(int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `TypicalPrice`<a href="method-typicalprice" id="method-typicalprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] TypicalPrice()
```

***  

## `UltOsc`<a href="method-ultosc" id="method-ultosc"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] UltOsc(int period1, int period2, int period3)
```

`period1` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`period2` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`period3` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `VHF`<a href="method-vhf" id="method-vhf"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] VHF(int n)
```
`n` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `Variance`<a href="method-variance" id="method-variance"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Variance(double[] d, int period, double dev)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`dev` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `VolumeOscillator`<a href="method-volumeoscillator" id="method-volumeoscillator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] VolumeOscillator(IndicatorMaType type, int shortN, int longN)
```
`type` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *Описание*  

`shortN` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`longN` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `WilliamsAD`<a href="method-williamsad" id="method-williamsad"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] WilliamsAD()
```

***  

## `WilliamsR`<a href="method-williamsr" id="method-williamsr"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] WilliamsR(int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `ZIGZAG`<a href="method-zigzag" id="method-zigzag"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] ZIGZAG(int depth, int deviation, int backstep, bool reg = true)
```
`depth` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`deviation` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`backstep` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`reg` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Ask`<a href="property-ask" id="property-ask"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Ask { get; }
```  
***

## `Bid`<a href="property-bid" id="property-bid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Bid { get; }
```  
***

## `Close`<a href="property-close" id="property-close"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Close { get; }
```  
***

## `Count`<a href="property-count" id="property-count"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Count { get; }
```  
***

## `DataProvider`<a href="property-dataprovider" id="property-dataprovider"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IChartDataProvider DataProvider { get; private set; }
```  
***

## `Date`<a href="property-date" id="property-date"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Date { get; }
```  
***

## `Delta`<a href="property-delta" id="property-delta"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Delta { get; }
```  
***

## `High`<a href="property-high" id="property-high"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] High { get; }
```  
***

## `Low`<a href="property-low" id="property-low"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Low { get; }
```  
***

## `Open`<a href="property-open" id="property-open"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Open { get; }
```  
***

## `OpenPos`<a href="property-openpos" id="property-openpos"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] OpenPos { get; }
```  
***

## `OpenPosAskChg`<a href="property-openposaskchg" id="property-openposaskchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] OpenPosAskChg { get; }
```  
***

## `OpenPosBidChg`<a href="property-openposbidchg" id="property-openposbidchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] OpenPosBidChg { get; }
```  
***

## `OpenPosChg`<a href="property-openposchg" id="property-openposchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] OpenPosChg { get; }
```  
***

## `Poc`<a href="property-poc" id="property-poc"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Poc { get; }
```  
***

## `Trades`<a href="property-trades" id="property-trades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Trades { get; }
```  
***

## `Volume`<a href="property-volume" id="property-volume"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double[] Volume { get; }
```  
***

