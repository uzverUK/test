
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Common](../../../TigerTrade.Chart/Indicators/Common.md)


===

### Синтаксис
```csharp
public sealed class IndicatorsHelper
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AC`](#method-ac) | *===* |
| [`AD`](#method-ad) | *===* |
| [`ADX`](#method-adx) | *===* |
| [`AO`](#method-ao) | *===* |
| [`ATR`](#method-atr) | *===* |
| [`Aroon`](#method-aroon) | *===* |
| [`BWMFI`](#method-bwmfi) | *===* |
| [`BearsPower`](#method-bearspower) | *===* |
| [`BullsPower`](#method-bullspower) | *===* |
| [`CCI`](#method-cci) | *===* |
| [`CMF`](#method-cmf) | *===* |
| [`CMO`](#method-cmo) | *===* |
| [`CO`](#method-co) | *===* |
| [`ChaikinsVolatility`](#method-chaikinsvolatility) | *===* |
| [`CumDelta`](#method-cumdelta) | *===* |
| [`EFI`](#method-efi) | *===* |
| [`Fractal`](#method-fractal) | *===* |
| [`IndicatorsHelper`](#method-indicatorshelper) | *===* |
| [`LinReg`](#method-linreg) | *===* |
| [`MFI`](#method-mfi) | *===* |
| [`Max`](#method-max) | *===* |
| [`MedianPrice`](#method-medianprice) | *===* |
| [`Min`](#method-min) | *===* |
| [`MinusDI`](#method-minusdi) | *===* |
| [`Momentum`](#method-momentum) | *===* |
| [`MovingAverage`](#method-movingaverage) | *===* |
| [`OBV`](#method-obv) | *===* |
| [`PPO`](#method-ppo) | *===* |
| [`PlusDI`](#method-plusdi) | *===* |
| [`Price`](#method-price) | *===* |
| [`PriceChannel`](#method-pricechannel) | *===* |
| [`ROC`](#method-roc) | *===* |
| [`RSI`](#method-rsi) | *===* |
| [`SAR`](#method-sar) | *===* |
| [`SMMA`](#method-smma) | *===* |
| [`SetDataProvider`](#method-setdataprovider) | *===* |
| [`ShiftData`](#method-shiftdata) | *===* |
| [`StdDev`](#method-stddev) | *===* |
| [`Subtraction`](#method-subtraction) | *===* |
| [`TRIX`](#method-trix) | *===* |
| [`TypicalPrice`](#method-typicalprice) | *===* |
| [`UltOsc`](#method-ultosc) | *===* |
| [`VHF`](#method-vhf) | *===* |
| [`Variance`](#method-variance) | *===* |
| [`VolumeOscillator`](#method-volumeoscillator) | *===* |
| [`WilliamsAD`](#method-williamsad) | *===* |
| [`WilliamsR`](#method-williamsr) | *===* |
| [`ZIGZAG`](#method-zigzag) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Ask`](#property-ask) | *===* |
| [`Bid`](#property-bid) | *===* |
| [`Close`](#property-close) | *===* |
| [`Count`](#property-count) | *===* |
| [`DataProvider`](#property-dataprovider) | *===* |
| [`Date`](#property-date) | *===* |
| [`Delta`](#property-delta) | *===* |
| [`High`](#property-high) | *===* |
| [`Low`](#property-low) | *===* |
| [`Open`](#property-open) | *===* |
| [`OpenPos`](#property-openpos) | *===* |
| [`OpenPosAskChg`](#property-openposaskchg) | *===* |
| [`OpenPosBidChg`](#property-openposbidchg) | *===* |
| [`OpenPosChg`](#property-openposchg) | *===* |
| [`Poc`](#property-poc) | *===* |
| [`Trades`](#property-trades) | *===* |
| [`Volume`](#property-volume) | *===* |





***  
***  
# Методы

## `AC`<a href="method-ac" id="method-ac"></a>
===
```csharp
public double[] AC(IndicatorMaType type, int shortN, int longN)
```

`type` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *===*  

`shortN` <mark style="color:red;">*`int`*</mark>  
 *===*  

`longN` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `AD`<a href="method-ad" id="method-ad"></a>
===
```csharp
public double[] AD()
```

***  

## `ADX`<a href="method-adx" id="method-adx"></a>
===
```csharp
public double[] ADX(int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `AO`<a href="method-ao" id="method-ao"></a>
===
```csharp
public double[] AO(IndicatorMaType type, int shortN, int longN)
```
`type` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *===*  

`shortN` <mark style="color:red;">*`int`*</mark>  
 *===*  

`longN` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `ATR`<a href="method-atr" id="method-atr"></a>
===
```csharp
public double[] ATR(int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `Aroon`<a href="method-aroon" id="method-aroon"></a>
===
```csharp
public void Aroon(int period, out double[] aroonUp, out double[] aroonDown)
```
`double` <mark style="color:red;">*`out`*</mark>  
 *===*  

`double` <mark style="color:red;">*`out`*</mark>  
 *===*  


***  

## `BWMFI`<a href="method-bwmfi" id="method-bwmfi"></a>
===
```csharp
public double[] BWMFI(IndicatorBWMFIType volumeType = IndicatorBWMFIType.Ticks)
```
`volumeType` <mark style="color:red;">*`IndicatorBWMFIType`*</mark>  
 *===*  


***  

## `BearsPower`<a href="method-bearspower" id="method-bearspower"></a>
===
```csharp
public double[] BearsPower(int n)
```
`n` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `BullsPower`<a href="method-bullspower" id="method-bullspower"></a>
===
```csharp
public double[] BullsPower(int n)
```

***  

## `CCI`<a href="method-cci" id="method-cci"></a>
===
```csharp
public double[] CCI(int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `CMF`<a href="method-cmf" id="method-cmf"></a>
===
```csharp
public double[] CMF(int n)
```
`n` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `CMO`<a href="method-cmo" id="method-cmo"></a>
===
```csharp
public double[] CMO(double[] d, int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `CO`<a href="method-co" id="method-co"></a>
===
```csharp
public double[] CO(IndicatorMaType maType, int shortPeriod, int longPeriod)
```
`maType` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *===*  

`shortPeriod` <mark style="color:red;">*`int`*</mark>  
 *===*  

`longPeriod` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `ChaikinsVolatility`<a href="method-chaikinsvolatility" id="method-chaikinsvolatility"></a>
===
```csharp
public double[] ChaikinsVolatility(IndicatorMaType type, int n)
```
`type` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *===*  

`n` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `CumDelta`<a href="method-cumdelta" id="method-cumdelta"></a>
===
```csharp
public double[] CumDelta()
```

***  

## `EFI`<a href="method-efi" id="method-efi"></a>
===
```csharp
public double[] EFI(double[] d, IndicatorMaType type, int n)
```

`type` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *===*  

`n` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `Fractal`<a href="method-fractal" id="method-fractal"></a>
===
```csharp
public void Fractal(int n, out double[] up, out double[] down)
```
`double` <mark style="color:red;">*`out`*</mark>  
 *===*  

`double` <mark style="color:red;">*`out`*</mark>  
 *===*  


***  

## `IndicatorsHelper`<a href="method-indicatorshelper" id="method-indicatorshelper"></a>
===
```csharp
public IndicatorsHelper()
```

***  

## `LinReg`<a href="method-linreg" id="method-linreg"></a>
===
```csharp
public double[] LinReg(double[] d, int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `MFI`<a href="method-mfi" id="method-mfi"></a>
===
```csharp
public double[] MFI(int period)
```

***  

## `Max`<a href="method-max" id="method-max"></a>
===
```csharp
public double[] Max(double[] d, int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `MedianPrice`<a href="method-medianprice" id="method-medianprice"></a>
===
```csharp
public double[] MedianPrice()
```

***  

## `Min`<a href="method-min" id="method-min"></a>
===
```csharp
public double[] Min(double[] d, int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `MinusDI`<a href="method-minusdi" id="method-minusdi"></a>
===
```csharp
public double[] MinusDI(int period)
```

***  

## `Momentum`<a href="method-momentum" id="method-momentum"></a>
===
```csharp
public double[] Momentum(double[] d, int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `MovingAverage`<a href="method-movingaverage" id="method-movingaverage"></a>
===
```csharp
public double[] MovingAverage(IndicatorMaType maType, double[] d, int period)
```
`maType` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *===*  


***  

## `OBV`<a href="method-obv" id="method-obv"></a>
===
```csharp
public double[] OBV()
```

***  

## `PPO`<a href="method-ppo" id="method-ppo"></a>
===
```csharp
public double[] PPO(IndicatorMaType maType, double[] d, int shortPeriod, int longPeriod)
```

`maType` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *===*  

`shortPeriod` <mark style="color:red;">*`int`*</mark>  
 *===*  

`longPeriod` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `PlusDI`<a href="method-plusdi" id="method-plusdi"></a>
===
```csharp
public double[] PlusDI(int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `Price`<a href="method-price" id="method-price"></a>
===
```csharp
public double[] Price(IndicatorPriceType priceField)
```
`priceField` <mark style="color:red;">*`IndicatorPriceType`*</mark>  
 *===*  


***  

## `PriceChannel`<a href="method-pricechannel" id="method-pricechannel"></a>
===
```csharp
public void PriceChannel(int n, out double[] avg, out double[] upper, out double[] lower)
```
`n` <mark style="color:red;">*`int`*</mark>  
 *===*  

`double` <mark style="color:red;">*`out`*</mark>  
 *===*  

`double` <mark style="color:red;">*`out`*</mark>  
 *===*  

`double` <mark style="color:red;">*`out`*</mark>  
 *===*  


***  

## `ROC`<a href="method-roc" id="method-roc"></a>
===
```csharp
public double[] ROC(double[] d, int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `RSI`<a href="method-rsi" id="method-rsi"></a>
===
```csharp
public double[] RSI(double[] d, int period)
```

***  

## `SAR`<a href="method-sar" id="method-sar"></a>
===
```csharp
public double[] SAR(double step, double maxp)
```

`step` <mark style="color:red;">*`double`*</mark>  
 *===*  

`maxp` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `SMMA`<a href="method-smma" id="method-smma"></a>
===
```csharp
public double[] SMMA(double[] d, int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `SetDataProvider`<a href="method-setdataprovider" id="method-setdataprovider"></a>
===
```csharp
public void SetDataProvider(IChartDataProvider dp)
```
`dp` <mark style="color:red;">*`IChartDataProvider`*</mark>  
 *===*  


***  

## `ShiftData`<a href="method-shiftdata" id="method-shiftdata"></a>
===
```csharp
public double[] ShiftData(double[] data, int shift)
```
`shift` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `StdDev`<a href="method-stddev" id="method-stddev"></a>
===
```csharp
public double[] StdDev(double[] d, int period)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `Subtraction`<a href="method-subtraction" id="method-subtraction"></a>
===
```csharp
public double[] Subtraction(double[] d1, double[] d2)
```

***  

## `TRIX`<a href="method-trix" id="method-trix"></a>
===
```csharp
public double[] TRIX(int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `TypicalPrice`<a href="method-typicalprice" id="method-typicalprice"></a>
===
```csharp
public double[] TypicalPrice()
```

***  

## `UltOsc`<a href="method-ultosc" id="method-ultosc"></a>
===
```csharp
public double[] UltOsc(int period1, int period2, int period3)
```

`period1` <mark style="color:red;">*`int`*</mark>  
 *===*  

`period2` <mark style="color:red;">*`int`*</mark>  
 *===*  

`period3` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `VHF`<a href="method-vhf" id="method-vhf"></a>
===
```csharp
public double[] VHF(int n)
```
`n` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `Variance`<a href="method-variance" id="method-variance"></a>
===
```csharp
public double[] Variance(double[] d, int period, double dev)
```
`period` <mark style="color:red;">*`int`*</mark>  
 *===*  

`dev` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `VolumeOscillator`<a href="method-volumeoscillator" id="method-volumeoscillator"></a>
===
```csharp
public double[] VolumeOscillator(IndicatorMaType type, int shortN, int longN)
```
`type` <mark style="color:red;">*`IndicatorMaType`*</mark>  
 *===*  

`shortN` <mark style="color:red;">*`int`*</mark>  
 *===*  

`longN` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `WilliamsAD`<a href="method-williamsad" id="method-williamsad"></a>
===
```csharp
public double[] WilliamsAD()
```

***  

## `WilliamsR`<a href="method-williamsr" id="method-williamsr"></a>
===
```csharp
public double[] WilliamsR(int period)
```

`period` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `ZIGZAG`<a href="method-zigzag" id="method-zigzag"></a>
===
```csharp
public double[] ZIGZAG(int depth, int deviation, int backstep, bool reg = true)
```
`depth` <mark style="color:red;">*`int`*</mark>  
 *===*  

`deviation` <mark style="color:red;">*`int`*</mark>  
 *===*  

`backstep` <mark style="color:red;">*`int`*</mark>  
 *===*  

`reg` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Ask`<a href="property-ask" id="property-ask"></a>
===
```csharp
public double[] Ask { get; }
```  
***

## `Bid`<a href="property-bid" id="property-bid"></a>
===
```csharp
public double[] Bid { get; }
```  
***

## `Close`<a href="property-close" id="property-close"></a>
===
```csharp
public double[] Close { get; }
```  
***

## `Count`<a href="property-count" id="property-count"></a>
===
```csharp
public int Count { get; }
```  
***

## `DataProvider`<a href="property-dataprovider" id="property-dataprovider"></a>
===
```csharp
public IChartDataProvider DataProvider { get; private set; }
```  
***

## `Date`<a href="property-date" id="property-date"></a>
===
```csharp
public double[] Date { get; }
```  
***

## `Delta`<a href="property-delta" id="property-delta"></a>
===
```csharp
public double[] Delta { get; }
```  
***

## `High`<a href="property-high" id="property-high"></a>
===
```csharp
public double[] High { get; }
```  
***

## `Low`<a href="property-low" id="property-low"></a>
===
```csharp
public double[] Low { get; }
```  
***

## `Open`<a href="property-open" id="property-open"></a>
===
```csharp
public double[] Open { get; }
```  
***

## `OpenPos`<a href="property-openpos" id="property-openpos"></a>
===
```csharp
public double[] OpenPos { get; }
```  
***

## `OpenPosAskChg`<a href="property-openposaskchg" id="property-openposaskchg"></a>
===
```csharp
public double[] OpenPosAskChg { get; }
```  
***

## `OpenPosBidChg`<a href="property-openposbidchg" id="property-openposbidchg"></a>
===
```csharp
public double[] OpenPosBidChg { get; }
```  
***

## `OpenPosChg`<a href="property-openposchg" id="property-openposchg"></a>
===
```csharp
public double[] OpenPosChg { get; }
```  
***

## `Poc`<a href="property-poc" id="property-poc"></a>
===
```csharp
public double[] Poc { get; }
```  
***

## `Trades`<a href="property-trades" id="property-trades"></a>
===
```csharp
public double[] Trades { get; }
```  
***

## `Volume`<a href="property-volume" id="property-volume"></a>
===
```csharp
public double[] Volume { get; }
```  
***

