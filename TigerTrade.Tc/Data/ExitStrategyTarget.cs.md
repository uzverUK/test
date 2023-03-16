
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


===

### Синтаксис
```csharp
public sealed class ExitStrategyTarget
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ClearSl`](#method-clearsl) | *===* |
| [`ClearTp`](#method-cleartp) | *===* |
| [`ExitStrategyTarget`](#method-exitstrategytarget) | *===* |
| [`RemoveSlTrailing`](#method-removesltrailing) | *===* |
| [`RemoveTpTrailing`](#method-removetptrailing) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ID`](#property-id) | *===* |
| [`IsServerOrderSl`](#property-isserverordersl) | *===* |
| [`IsServerOrderTP`](#property-isserverordertp) | *===* |
| [`Quantity`](#property-quantity) | *===* |
| [`SlOrderID`](#property-slorderid) | *===* |
| [`SlSynchronized`](#property-slsynchronized) | *===* |
| [`SlTpUpdateTime`](#property-sltpupdatetime) | *===* |
| [`StopLossBreakevenPlus`](#property-stoplossbreakevenplus) | *===* |
| [`StopLossBreakevenProfit`](#property-stoplossbreakevenprofit) | *===* |
| [`StopLossOffset`](#property-stoplossoffset) | *===* |
| [`StopLossPrice`](#property-stoplossprice) | *===* |
| [`StopLossSize`](#property-stoplosssize) | *===* |
| [`StopLossTrailingRange`](#property-stoplosstrailingrange) | *===* |
| [`StopLossTrailingStep`](#property-stoplosstrailingstep) | *===* |
| [`TakeProfitOffset`](#property-takeprofitoffset) | *===* |
| [`TakeProfitPrice`](#property-takeprofitprice) | *===* |
| [`TakeProfitRange`](#property-takeprofitrange) | *===* |
| [`TakeProfitSize`](#property-takeprofitsize) | *===* |
| [`TakeProfitStopActive`](#property-takeprofitstopactive) | *===* |
| [`TpOrderID`](#property-tporderid) | *===* |
| [`TpSynchronized`](#property-tpsynchronized) | *===* |
| [`UpdateTime`](#property-updatetime) | *===* |





***  
***  
# Методы

## `ClearSl`<a href="method-clearsl" id="method-clearsl"></a>
===
```csharp
public void ClearSl()
```

***  

## `ClearTp`<a href="method-cleartp" id="method-cleartp"></a>
===
```csharp
public void ClearTp()
```

***  

## `ExitStrategyTarget`<a href="method-exitstrategytarget" id="method-exitstrategytarget"></a>
===
```csharp
public ExitStrategyTarget()
```

***  

## `RemoveSlTrailing`<a href="method-removesltrailing" id="method-removesltrailing"></a>
===
```csharp
public void RemoveSlTrailing()
```

***  

## `RemoveTpTrailing`<a href="method-removetptrailing" id="method-removetptrailing"></a>
===
```csharp
public void RemoveTpTrailing()
```

***  
***  
 ***  
# Свойства

## `ID`<a href="property-id" id="property-id"></a>
===
```csharp
public string ID { get; set; }
```  
***

## `IsServerOrderSl`<a href="property-isserverordersl" id="property-isserverordersl"></a>
===
```csharp
public bool IsServerOrderSl { get; set; }
```  
***

## `IsServerOrderTP`<a href="property-isserverordertp" id="property-isserverordertp"></a>
===
```csharp
public bool IsServerOrderTP { get; set; }
```  
***

## `Quantity`<a href="property-quantity" id="property-quantity"></a>
===
```csharp
public long Quantity { get; set; }
```  
***

## `SlOrderID`<a href="property-slorderid" id="property-slorderid"></a>
===
```csharp
public string SlOrderID { get; set; }
```  
***

## `SlSynchronized`<a href="property-slsynchronized" id="property-slsynchronized"></a>
===
```csharp
public bool SlSynchronized { get; set; }
```  
***

## `SlTpUpdateTime`<a href="property-sltpupdatetime" id="property-sltpupdatetime"></a>
===
```csharp
public DateTime SlTpUpdateTime { get; set; }
```  
***

## `StopLossBreakevenPlus`<a href="property-stoplossbreakevenplus" id="property-stoplossbreakevenplus"></a>
===
```csharp
public long StopLossBreakevenPlus { get; set; }
```  
***

## `StopLossBreakevenProfit`<a href="property-stoplossbreakevenprofit" id="property-stoplossbreakevenprofit"></a>
===
```csharp
public long StopLossBreakevenProfit { get; set; }
```  
***

## `StopLossOffset`<a href="property-stoplossoffset" id="property-stoplossoffset"></a>
===
```csharp
public int? StopLossOffset { get; set; }
```  
***

## `StopLossPrice`<a href="property-stoplossprice" id="property-stoplossprice"></a>
===
```csharp
public long StopLossPrice { get; set; }
```  
***

## `StopLossSize`<a href="property-stoplosssize" id="property-stoplosssize"></a>
===
```csharp
public long? StopLossSize { get; set; }
```  
***

## `StopLossTrailingRange`<a href="property-stoplosstrailingrange" id="property-stoplosstrailingrange"></a>
===
```csharp
public long StopLossTrailingRange { get; set; }
```  
***

## `StopLossTrailingStep`<a href="property-stoplosstrailingstep" id="property-stoplosstrailingstep"></a>
===
```csharp
public long StopLossTrailingStep { get; set; }
```  
***

## `TakeProfitOffset`<a href="property-takeprofitoffset" id="property-takeprofitoffset"></a>
===
```csharp
public int? TakeProfitOffset { get; set; }
```  
***

## `TakeProfitPrice`<a href="property-takeprofitprice" id="property-takeprofitprice"></a>
===
```csharp
public long TakeProfitPrice { get; set; }
```  
***

## `TakeProfitRange`<a href="property-takeprofitrange" id="property-takeprofitrange"></a>
===
```csharp
public long TakeProfitRange { get; set; }
```  
***

## `TakeProfitSize`<a href="property-takeprofitsize" id="property-takeprofitsize"></a>
===
```csharp
public long? TakeProfitSize { get; set; }
```  
***

## `TakeProfitStopActive`<a href="property-takeprofitstopactive" id="property-takeprofitstopactive"></a>
===
```csharp
public bool TakeProfitStopActive { get; set; }
```  
***

## `TpOrderID`<a href="property-tporderid" id="property-tporderid"></a>
===
```csharp
public string TpOrderID { get; set; }
```  
***

## `TpSynchronized`<a href="property-tpsynchronized" id="property-tpsynchronized"></a>
===
```csharp
public bool TpSynchronized { get; set; }
```  
***

## `UpdateTime`<a href="property-updatetime" id="property-updatetime"></a>
===
```csharp
public DateTime UpdateTime { get; private set; }
```  
***

