# ExitStrategyTarget

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class ExitStrategyTarget
```

## Список методов

| Название                                                                   | Описание |
| -------------------------------------------------------------------------- | -------- |
| [`ClearSl`](exitstrategytarget.cs.md#method-clearsl)                       | _===_    |
| [`ClearTp`](exitstrategytarget.cs.md#method-cleartp)                       | _===_    |
| [`ExitStrategyTarget`](exitstrategytarget.cs.md#method-exitstrategytarget) | _===_    |
| [`RemoveSlTrailing`](exitstrategytarget.cs.md#method-removesltrailing)     | _===_    |
| [`RemoveTpTrailing`](exitstrategytarget.cs.md#method-removetptrailing)     | _===_    |

## Список свойств

| Название                                                                               | Описание |
| -------------------------------------------------------------------------------------- | -------- |
| [`ID`](exitstrategytarget.cs.md#property-id)                                           | _===_    |
| [`IsServerOrderSl`](exitstrategytarget.cs.md#property-isserverordersl)                 | _===_    |
| [`IsServerOrderTP`](exitstrategytarget.cs.md#property-isserverordertp)                 | _===_    |
| [`Quantity`](exitstrategytarget.cs.md#property-quantity)                               | _===_    |
| [`SlOrderID`](exitstrategytarget.cs.md#property-slorderid)                             | _===_    |
| [`SlSynchronized`](exitstrategytarget.cs.md#property-slsynchronized)                   | _===_    |
| [`SlTpUpdateTime`](exitstrategytarget.cs.md#property-sltpupdatetime)                   | _===_    |
| [`StopLossBreakevenPlus`](exitstrategytarget.cs.md#property-stoplossbreakevenplus)     | _===_    |
| [`StopLossBreakevenProfit`](exitstrategytarget.cs.md#property-stoplossbreakevenprofit) | _===_    |
| [`StopLossOffset`](exitstrategytarget.cs.md#property-stoplossoffset)                   | _===_    |
| [`StopLossPrice`](exitstrategytarget.cs.md#property-stoplossprice)                     | _===_    |
| [`StopLossSize`](exitstrategytarget.cs.md#property-stoplosssize)                       | _===_    |
| [`StopLossTrailingRange`](exitstrategytarget.cs.md#property-stoplosstrailingrange)     | _===_    |
| [`StopLossTrailingStep`](exitstrategytarget.cs.md#property-stoplosstrailingstep)       | _===_    |
| [`TakeProfitOffset`](exitstrategytarget.cs.md#property-takeprofitoffset)               | _===_    |
| [`TakeProfitPrice`](exitstrategytarget.cs.md#property-takeprofitprice)                 | _===_    |
| [`TakeProfitRange`](exitstrategytarget.cs.md#property-takeprofitrange)                 | _===_    |
| [`TakeProfitSize`](exitstrategytarget.cs.md#property-takeprofitsize)                   | _===_    |
| [`TakeProfitStopActive`](exitstrategytarget.cs.md#property-takeprofitstopactive)       | _===_    |
| [`TpOrderID`](exitstrategytarget.cs.md#property-tporderid)                             | _===_    |
| [`TpSynchronized`](exitstrategytarget.cs.md#property-tpsynchronized)                   | _===_    |
| [`UpdateTime`](exitstrategytarget.cs.md#property-updatetime)                           | _===_    |

***

***

## Методы

### `ClearSl` <a href="#method-clearsl" id="method-clearsl"></a>

\===

```csharp
public void ClearSl()
```

***

### `ClearTp` <a href="#method-cleartp" id="method-cleartp"></a>

\===

```csharp
public void ClearTp()
```

***

### `ExitStrategyTarget` <a href="#method-exitstrategytarget" id="method-exitstrategytarget"></a>

\===

```csharp
public ExitStrategyTarget()
```

***

### `RemoveSlTrailing` <a href="#method-removesltrailing" id="method-removesltrailing"></a>

\===

```csharp
public void RemoveSlTrailing()
```

***

### `RemoveTpTrailing` <a href="#method-removetptrailing" id="method-removetptrailing"></a>

\===

```csharp
public void RemoveTpTrailing()
```

***

***

***

## Свойства

### `ID` <a href="#property-id" id="property-id"></a>

\===

```csharp
public string ID { get; set; }
```

***

### `IsServerOrderSl` <a href="#property-isserverordersl" id="property-isserverordersl"></a>

\===

```csharp
public bool IsServerOrderSl { get; set; }
```

***

### `IsServerOrderTP` <a href="#property-isserverordertp" id="property-isserverordertp"></a>

\===

```csharp
public bool IsServerOrderTP { get; set; }
```

***

### `Quantity` <a href="#property-quantity" id="property-quantity"></a>

\===

```csharp
public long Quantity { get; set; }
```

***

### `SlOrderID` <a href="#property-slorderid" id="property-slorderid"></a>

\===

```csharp
public string SlOrderID { get; set; }
```

***

### `SlSynchronized` <a href="#property-slsynchronized" id="property-slsynchronized"></a>

\===

```csharp
public bool SlSynchronized { get; set; }
```

***

### `SlTpUpdateTime` <a href="#property-sltpupdatetime" id="property-sltpupdatetime"></a>

\===

```csharp
public DateTime SlTpUpdateTime { get; set; }
```

***

### `StopLossBreakevenPlus` <a href="#property-stoplossbreakevenplus" id="property-stoplossbreakevenplus"></a>

\===

```csharp
public long StopLossBreakevenPlus { get; set; }
```

***

### `StopLossBreakevenProfit` <a href="#property-stoplossbreakevenprofit" id="property-stoplossbreakevenprofit"></a>

\===

```csharp
public long StopLossBreakevenProfit { get; set; }
```

***

### `StopLossOffset` <a href="#property-stoplossoffset" id="property-stoplossoffset"></a>

\===

```csharp
public int? StopLossOffset { get; set; }
```

***

### `StopLossPrice` <a href="#property-stoplossprice" id="property-stoplossprice"></a>

\===

```csharp
public long StopLossPrice { get; set; }
```

***

### `StopLossSize` <a href="#property-stoplosssize" id="property-stoplosssize"></a>

\===

```csharp
public long? StopLossSize { get; set; }
```

***

### `StopLossTrailingRange` <a href="#property-stoplosstrailingrange" id="property-stoplosstrailingrange"></a>

\===

```csharp
public long StopLossTrailingRange { get; set; }
```

***

### `StopLossTrailingStep` <a href="#property-stoplosstrailingstep" id="property-stoplosstrailingstep"></a>

\===

```csharp
public long StopLossTrailingStep { get; set; }
```

***

### `TakeProfitOffset` <a href="#property-takeprofitoffset" id="property-takeprofitoffset"></a>

\===

```csharp
public int? TakeProfitOffset { get; set; }
```

***

### `TakeProfitPrice` <a href="#property-takeprofitprice" id="property-takeprofitprice"></a>

\===

```csharp
public long TakeProfitPrice { get; set; }
```

***

### `TakeProfitRange` <a href="#property-takeprofitrange" id="property-takeprofitrange"></a>

\===

```csharp
public long TakeProfitRange { get; set; }
```

***

### `TakeProfitSize` <a href="#property-takeprofitsize" id="property-takeprofitsize"></a>

\===

```csharp
public long? TakeProfitSize { get; set; }
```

***

### `TakeProfitStopActive` <a href="#property-takeprofitstopactive" id="property-takeprofitstopactive"></a>

\===

```csharp
public bool TakeProfitStopActive { get; set; }
```

***

### `TpOrderID` <a href="#property-tporderid" id="property-tporderid"></a>

\===

```csharp
public string TpOrderID { get; set; }
```

***

### `TpSynchronized` <a href="#property-tpsynchronized" id="property-tpsynchronized"></a>

\===

```csharp
public bool TpSynchronized { get; set; }
```

***

### `UpdateTime` <a href="#property-updatetime" id="property-updatetime"></a>

\===

```csharp
public DateTime UpdateTime { get; private set; }
```

***
