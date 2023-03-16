
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class RawCluster : IRawCluster
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddCluster`](#method-addcluster) | *Описание* |
| [`AddItem`](#method-additem) | *Описание* |
| [`AddTick`](#method-addtick) | *Описание* |
| [`GetItem`](#method-getitem) | *Описание* |
| [`GetValueArea`](#method-getvaluearea) | *Описание* |
| [`RawCluster`](#method-rawcluster) | *Описание* |
| [`UpdateData`](#method-updatedata) | *Описание* |

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
| [`Items`](#property-items) | *Описание* |
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

## `AddCluster`<a href="method-addcluster" id="method-addcluster"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddCluster(IRawCluster cluster)
```

`cluster` <mark style="color:red;">*`IRawCluster`*</mark>  
 *Описание*  


***  

## `AddItem`<a href="method-additem" id="method-additem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddItem(IRawClusterItem item)
```
`item` <mark style="color:red;">*`IRawClusterItem`*</mark>  
 *Описание*  


***  

## `AddTick`<a href="method-addtick" id="method-addtick"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddTick(IRawTick tick, int scale)
```
`tick` <mark style="color:red;">*`IRawTick`*</mark>  
 *Описание*  

`scale` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetItem`<a href="method-getitem" id="method-getitem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IRawClusterItem GetItem(long price)
```
`price` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `GetValueArea`<a href="method-getvaluearea" id="method-getvaluearea"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IRawClusterValueArea GetValueArea(int valueArea)
```
`valueArea` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `RawCluster`<a href="method-rawcluster" id="method-rawcluster"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RawCluster(DateTime time)
```
`time` <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  


***  

## `UpdateData`<a href="method-updatedata" id="method-updatedata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void UpdateData()
```

***  
***  
 ***  
# Свойства

## `Ask`<a href="property-ask" id="property-ask"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Ask { get; private set; }
```  
***

## `AskTrades`<a href="property-asktrades" id="property-asktrades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AskTrades { get; private set; }
```  
***

## `Bid`<a href="property-bid" id="property-bid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Bid { get; private set; }
```  
***

## `BidTrades`<a href="property-bidtrades" id="property-bidtrades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int BidTrades { get; private set; }
```  
***

## `Close`<a href="property-close" id="property-close"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Close { get; set; }
```  
***

## `CloseTime`<a href="property-closetime" id="property-closetime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime CloseTime { get; private set; }
```  
***

## `Delta`<a href="property-delta" id="property-delta"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Delta { get; }
```  
***

## `DeltaHigh`<a href="property-deltahigh" id="property-deltahigh"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long DeltaHigh { get; private set; }
```  
***

## `DeltaLow`<a href="property-deltalow" id="property-deltalow"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long DeltaLow { get; private set; }
```  
***

## `High`<a href="property-high" id="property-high"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long High { get; set; }
```  
***

## `IsUp`<a href="property-isup" id="property-isup"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsUp { get; set; }
```  
***

## `Items`<a href="property-items" id="property-items"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<IRawClusterItem> Items { get; }
```  
***

## `Low`<a href="property-low" id="property-low"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Low { get; set; }
```  
***

## `MaxValues`<a href="property-maxvalues" id="property-maxvalues"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IRawClusterMaxValues MaxValues { get; }
```  
***

## `Open`<a href="property-open" id="property-open"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Open { get; set; }
```  
***

## `OpenPos`<a href="property-openpos" id="property-openpos"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPos { get; private set; }
```  
***

## `OpenPosAskChg`<a href="property-openposaskchg" id="property-openposaskchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosAskChg { get; private set; }
```  
***

## `OpenPosBidChg`<a href="property-openposbidchg" id="property-openposbidchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosBidChg { get; private set; }
```  
***

## `OpenPosChg`<a href="property-openposchg" id="property-openposchg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosChg { get; }
```  
***

## `OpenPosHigh`<a href="property-openposhigh" id="property-openposhigh"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosHigh { get; private set; }
```  
***

## `OpenPosLow`<a href="property-openposlow" id="property-openposlow"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosLow { get; private set; }
```  
***

## `OpenTime`<a href="property-opentime" id="property-opentime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime OpenTime { get; private set; }
```  
***

## `Time`<a href="property-time" id="property-time"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; }
```  
***

## `Trades`<a href="property-trades" id="property-trades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Trades { get; }
```  
***

## `Volume`<a href="property-volume" id="property-volume"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Volume { get; }
```  
***

