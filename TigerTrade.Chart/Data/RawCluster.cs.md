
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public sealed class RawCluster : IRawCluster
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`AddCluster`](./RawCluster.cs/Методы/AddCluster.md) | *Описание* |
| [`AddItem`](./RawCluster.cs/Методы/AddItem.md) | *Описание* |
| [`AddTick`](./RawCluster.cs/Методы/AddTick.md) | *Описание* |
| [`GetItem`](./RawCluster.cs/Методы/GetItem.md) | *Описание* |
| [`GetValueArea`](./RawCluster.cs/Методы/GetValueArea.md) | *Описание* |
| [`RawCluster`](./RawCluster.cs/Методы/RawCluster.md) | *Описание* |
| [`UpdateData`](./RawCluster.cs/Методы/UpdateData.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Ask`](./RawCluster.cs/Свойства/Ask.md) | *Описание* |
| [`AskTrades`](./RawCluster.cs/Свойства/AskTrades.md) | *Описание* |
| [`Bid`](./RawCluster.cs/Свойства/Bid.md) | *Описание* |
| [`BidTrades`](./RawCluster.cs/Свойства/BidTrades.md) | *Описание* |
| [`Close`](./RawCluster.cs/Свойства/Close.md) | *Описание* |
| [`CloseTime`](./RawCluster.cs/Свойства/CloseTime.md) | *Описание* |
| [`Delta`](./RawCluster.cs/Свойства/Delta.md) | *Описание* |
| [`DeltaHigh`](./RawCluster.cs/Свойства/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./RawCluster.cs/Свойства/DeltaLow.md) | *Описание* |
| [`High`](./RawCluster.cs/Свойства/High.md) | *Описание* |
| [`IsUp`](./RawCluster.cs/Свойства/IsUp.md) | *Описание* |
| [`Items`](./RawCluster.cs/Свойства/Items.md) | *Описание* |
| [`Low`](./RawCluster.cs/Свойства/Low.md) | *Описание* |
| [`MaxValues`](./RawCluster.cs/Свойства/MaxValues.md) | *Описание* |
| [`Open`](./RawCluster.cs/Свойства/Open.md) | *Описание* |
| [`OpenPos`](./RawCluster.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosAskChg`](./RawCluster.cs/Свойства/OpenPosAskChg.md) | *Описание* |
| [`OpenPosBidChg`](./RawCluster.cs/Свойства/OpenPosBidChg.md) | *Описание* |
| [`OpenPosChg`](./RawCluster.cs/Свойства/OpenPosChg.md) | *Описание* |
| [`OpenPosHigh`](./RawCluster.cs/Свойства/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./RawCluster.cs/Свойства/OpenPosLow.md) | *Описание* |
| [`OpenTime`](./RawCluster.cs/Свойства/OpenTime.md) | *Описание* |
| [`Time`](./RawCluster.cs/Свойства/Time.md) | *Описание* |
| [`Trades`](./RawCluster.cs/Свойства/Trades.md) | *Описание* |
| [`Volume`](./RawCluster.cs/Свойства/Volume.md) | *Описание* |





# Методы

## `AddCluster`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddCluster(IRawCluster cluster)
```

<mark style="color:purple;">`cluster`</mark> <mark style="color:red;">*`IRawCluster`*</mark>  
 *Описание*  



## `AddItem`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddItem(IRawClusterItem item)
```
<mark style="color:purple;">`item`</mark> <mark style="color:red;">*`IRawClusterItem`*</mark>  
 *Описание*  



## `AddTick`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddTick(IRawTick tick, int scale)
```
<mark style="color:purple;">`tick`</mark> <mark style="color:red;">*`IRawTick`*</mark>  
 *Описание*  

<mark style="color:purple;">`scale`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## `GetItem`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IRawClusterItem GetItem(long price)
```
<mark style="color:purple;">`price`</mark> <mark style="color:red;">*`long`*</mark>  
 *Описание*  



## `GetValueArea`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IRawClusterValueArea GetValueArea(int valueArea)
```
<mark style="color:purple;">`valueArea`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## `RawCluster`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RawCluster(DateTime time)
```
<mark style="color:purple;">`time`</mark> <mark style="color:red;">*`DateTime`*</mark>  
 *Описание*  



## `UpdateData`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void UpdateData()
```

# Свойства

## `Ask`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Ask { get; private set; }
```

## `AskTrades`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AskTrades { get; private set; }
```

## `Bid`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Bid { get; private set; }
```

## `BidTrades`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int BidTrades { get; private set; }
```

## `Close`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Close { get; set; }
```

## `CloseTime`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime CloseTime { get; private set; }
```

## `Delta`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Delta { get; }
```

## `DeltaHigh`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long DeltaHigh { get; private set; }
```

## `DeltaLow`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long DeltaLow { get; private set; }
```

## `High`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long High { get; set; }
```

## `IsUp`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsUp { get; set; }
```

## `Items`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<IRawClusterItem> Items { get; }
```

## `Low`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Low { get; set; }
```

## `MaxValues`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IRawClusterMaxValues MaxValues { get; }
```

## `Open`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Open { get; set; }
```

## `OpenPos`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPos { get; private set; }
```

## `OpenPosAskChg`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosAskChg { get; private set; }
```

## `OpenPosBidChg`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosBidChg { get; private set; }
```

## `OpenPosChg`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosChg { get; }
```

## `OpenPosHigh`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosHigh { get; private set; }
```

## `OpenPosLow`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long OpenPosLow { get; private set; }
```

## `OpenTime`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime OpenTime { get; private set; }
```

## `Time`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; }
```

## `Trades`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Trades { get; }
```

## `Volume`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Volume { get; }
```

