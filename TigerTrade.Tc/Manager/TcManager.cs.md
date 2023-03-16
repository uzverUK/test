
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


===

### Синтаксис
```csharp
public static class TcManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetMarketDataConnections`](#method-getmarketdataconnections) | *===* |
| [`Load`](#method-load) | *===* |
| [`LoadSimulator`](#method-loadsimulator) | *===* |
| [`Save`](#method-save) | *===* |
| [`SaveSettings`](#method-savesettings) | *===* |
| [`SetCancelOrdersOnClose`](#method-setcancelordersonclose) | *===* |
| [`SetDynamicStopLoss`](#method-setdynamicstoploss) | *===* |
| [`SetDynamicTakeProfit`](#method-setdynamictakeprofit) | *===* |
| [`SetPositionPartClose`](#method-setpositionpartclose) | *===* |
| [`SetServerStopLoss`](#method-setserverstoploss) | *===* |
| [`SetServerTakeProfit`](#method-setservertakeprofit) | *===* |
| [`SetViewDeletedSymbols`](#method-setviewdeletedsymbols) | *===* |
| [`SetViewOptionsSymbols`](#method-setviewoptionssymbols) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AccountValidator`](#property-accountvalidator) | *===* |
| [`CommonDataPath;`](#property-commondatapath;) | *===* |
| [`SortSettings`](#property-sortsettings) | *===* |





***  
***  
# Методы

## `GetMarketDataConnections`<a href="method-getmarketdataconnections" id="method-getmarketdataconnections"></a>
===
```csharp
public static ConnectionInfo[] GetMarketDataConnections(string symbolId)
```

`symbolId` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `Load`<a href="method-load" id="method-load"></a>
===
```csharp
public static void Load(byte[] clients)
```

***  

## `LoadSimulator`<a href="method-loadsimulator" id="method-loadsimulator"></a>
===
```csharp
public static void LoadSimulator()
```

***  

## `Save`<a href="method-save" id="method-save"></a>
===
```csharp
public static void Save()
```

***  

## `SaveSettings`<a href="method-savesettings" id="method-savesettings"></a>
===
```csharp
public static void SaveSettings()
```

***  

## `SetCancelOrdersOnClose`<a href="method-setcancelordersonclose" id="method-setcancelordersonclose"></a>
===
```csharp
public static void SetCancelOrdersOnClose(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `SetDynamicStopLoss`<a href="method-setdynamicstoploss" id="method-setdynamicstoploss"></a>
===
```csharp
public static void SetDynamicStopLoss(bool value)
```

***  

## `SetDynamicTakeProfit`<a href="method-setdynamictakeprofit" id="method-setdynamictakeprofit"></a>
===
```csharp
public static void SetDynamicTakeProfit(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `SetPositionPartClose`<a href="method-setpositionpartclose" id="method-setpositionpartclose"></a>
===
```csharp
public static void SetPositionPartClose(bool value)
```

***  

## `SetServerStopLoss`<a href="method-setserverstoploss" id="method-setserverstoploss"></a>
===
```csharp
public static void SetServerStopLoss(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `SetServerTakeProfit`<a href="method-setservertakeprofit" id="method-setservertakeprofit"></a>
===
```csharp
public static void SetServerTakeProfit(bool value)
```

***  

## `SetViewDeletedSymbols`<a href="method-setviewdeletedsymbols" id="method-setviewdeletedsymbols"></a>
===
```csharp
public static void SetViewDeletedSymbols(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `SetViewOptionsSymbols`<a href="method-setviewoptionssymbols" id="method-setviewoptionssymbols"></a>
===
```csharp
public static void SetViewOptionsSymbols(bool value)
```

***  
***  
 ***  
# Свойства

## `AccountValidator`<a href="property-accountvalidator" id="property-accountvalidator"></a>
===
```csharp
public static zYmFZWVu32MJxRml897u AccountValidator { get; private set; }
```  
***

## `CommonDataPath;`<a href="property-commondatapath;" id="property-commondatapath;"></a>
===
```csharp
public static string CommonDataPath; {}
```  
***

## `SortSettings`<a href="property-sortsettings" id="property-sortsettings"></a>
===
```csharp
public static tlSh00wib4PcbfluEhqD SortSettings { get; set; }
```  
***

