
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public interface IRawCluster
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetItem`](#method-getitem) | *Описание* |
| [`GetValueArea`](#method-getvaluearea) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Ask`](#property-ask) | *Описание* |
| [`AskTrades`](#property-asktrades) | *Описание* |
| [`Bid`](#property-bid) | *Описание* |
| [`BidTrades`](#property-bidtrades) | *Описание* |
| [`Close`](#property-close) | *Описание* |
| [`CloseTime`](#property-closetime) | *Описание* |
| [`Delta`](#property-delta) | *Описание* |
| [`DeltaHigh`](#property-deltahigh) | *Описание* |
| [`DeltaLow`](#property-deltalow) | *Описание* |
| [`High`](#property-high) | *Описание* |
| [`IsUp`](#property-isup) | *Описание* |
| [`Low`](#property-low) | *Описание* |
| [`MaxValues`](#property-maxvalues) | *Описание* |
| [`Open`](#property-open) | *Описание* |
| [`OpenPos`](#property-openpos) | *Описание* |
| [`OpenPosAskChg`](#property-openposaskchg) | *Описание* |
| [`OpenPosBidChg`](#property-openposbidchg) | *Описание* |
| [`OpenPosChg`](#property-openposchg) | *Описание* |
| [`OpenPosHigh`](#property-openposhigh) | *Описание* |
| [`OpenPosLow`](#property-openposlow) | *Описание* |
| [`OpenTime`](#property-opentime) | *Описание* |
| [`Time`](#property-time) | *Описание* |
| [`Trades`](#property-trades) | *Описание* |
| [`Volume`](#property-volume) | *Описание* |





***  
***  
# Методы

## `GetItem`<a href="method-getitem" id="method-getitem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawClusterItem GetItem(long price)
```

`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetValueArea`<a href="method-getvaluearea" id="method-getvaluearea"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawClusterValueArea GetValueArea(int valueArea)
```
`valueArea` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Ask`<a href="property-ask" id="property-ask"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long Ask { get; }
```  
***

## `AskTrades`<a href="property-asktrades" id="property-asktrades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int AskTrades { get; }
```  
***

## `Bid`<a href="property-bid" id="property-bid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long Bid { get; }
```  
***

## `BidTrades`<a href="property-bidtrades" id="property-bidtrades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int BidTrades { get; }
```  
***

## `Close`<a href="property-close" id="property-close"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long Close { get; }
```  
***

## `CloseTime`<a href="property-closetime" id="property-closetime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime CloseTime { get; }
```  
***

## `Delta`<a href="property-delta" id="property-delta"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long Delta { get; }
```  
***

## `DeltaHigh`<a href="property-deltahigh" id="property-deltahigh"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long DeltaHigh { get; }
```  
***

## `DeltaLow`<a href="property-deltalow" id="property-deltalow"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long DeltaLow { get; }
```  
***

## `High`<a href="property-high" id="property-high"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long High { get; }
```  
***

## `IsUp`<a href="property-isup" id="property-isup"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
bool IsUp { get; }
```  
***

## `Low`<a href="property-low" id="property-low"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long Low { get; }
```  
***

## `MaxValues`<a href="property-maxvalues" id="property-maxvalues"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawClusterMaxValues MaxValues { get; }
```  
***

## `Open`<a href="property-open" id="property-open"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long Open { get; }
```  
***

## `OpenPos`<a href="property-openpos" id="property-openpos"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long OpenPos { get; }
```  
***

## `OpenPosAskChg`<a href="property-openposaskchg" id="property-openposaskchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long OpenPosAskChg { get; }
```  
***

## `OpenPosBidChg`<a href="property-openposbidchg" id="property-openposbidchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long OpenPosBidChg { get; }
```  
***

## `OpenPosChg`<a href="property-openposchg" id="property-openposchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long OpenPosChg { get; }
```  
***

## `OpenPosHigh`<a href="property-openposhigh" id="property-openposhigh"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long OpenPosHigh { get; }
```  
***

## `OpenPosLow`<a href="property-openposlow" id="property-openposlow"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long OpenPosLow { get; }
```  
***

## `OpenTime`<a href="property-opentime" id="property-opentime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime OpenTime { get; }
```  
***

## `Time`<a href="property-time" id="property-time"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
DateTime Time { get; }
```  
***

## `Trades`<a href="property-trades" id="property-trades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Trades { get; }
```  
***

## `Volume`<a href="property-volume" id="property-volume"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
long Volume { get; }
```  
***

