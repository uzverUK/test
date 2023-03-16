# TcManager

`namespace` [TigerTrade.Tc](../).[Manager](./)

\===

#### Синтаксис

```csharp
public static class TcManager
```

## Список методов

| Название                                                                      | Описание |
| ----------------------------------------------------------------------------- | -------- |
| [`GetMarketDataConnections`](tcmanager.cs.md#method-getmarketdataconnections) | _===_    |
| [`Load`](tcmanager.cs.md#method-load)                                         | _===_    |
| [`LoadSimulator`](tcmanager.cs.md#method-loadsimulator)                       | _===_    |
| [`Save`](tcmanager.cs.md#method-save)                                         | _===_    |
| [`SaveSettings`](tcmanager.cs.md#method-savesettings)                         | _===_    |
| [`SetCancelOrdersOnClose`](tcmanager.cs.md#method-setcancelordersonclose)     | _===_    |
| [`SetDynamicStopLoss`](tcmanager.cs.md#method-setdynamicstoploss)             | _===_    |
| [`SetDynamicTakeProfit`](tcmanager.cs.md#method-setdynamictakeprofit)         | _===_    |
| [`SetPositionPartClose`](tcmanager.cs.md#method-setpositionpartclose)         | _===_    |
| [`SetServerStopLoss`](tcmanager.cs.md#method-setserverstoploss)               | _===_    |
| [`SetServerTakeProfit`](tcmanager.cs.md#method-setservertakeprofit)           | _===_    |
| [`SetViewDeletedSymbols`](tcmanager.cs.md#method-setviewdeletedsymbols)       | _===_    |
| [`SetViewOptionsSymbols`](tcmanager.cs.md#method-setviewoptionssymbols)       | _===_    |

## Список свойств

| Название                                                        | Описание |
| --------------------------------------------------------------- | -------- |
| [`AccountValidator`](tcmanager.cs.md#property-accountvalidator) | _===_    |
| [`CommonDataPath;`](tcmanager.cs.md#property-commondatapath;)   | _===_    |
| [`SortSettings`](tcmanager.cs.md#property-sortsettings)         | _===_    |

***

***

## Методы

### `GetMarketDataConnections` <a href="#method-getmarketdataconnections" id="method-getmarketdataconnections"></a>

\===

```csharp
public static ConnectionInfo[] GetMarketDataConnections(string symbolId)
```

`symbolId` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `Load` <a href="#method-load" id="method-load"></a>

\===

```csharp
public static void Load(byte[] clients)
```

***

### `LoadSimulator` <a href="#method-loadsimulator" id="method-loadsimulator"></a>

\===

```csharp
public static void LoadSimulator()
```

***

### `Save` <a href="#method-save" id="method-save"></a>

\===

```csharp
public static void Save()
```

***

### `SaveSettings` <a href="#method-savesettings" id="method-savesettings"></a>

\===

```csharp
public static void SaveSettings()
```

***

### `SetCancelOrdersOnClose` <a href="#method-setcancelordersonclose" id="method-setcancelordersonclose"></a>

\===

```csharp
public static void SetCancelOrdersOnClose(bool value)
```

`value` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `SetDynamicStopLoss` <a href="#method-setdynamicstoploss" id="method-setdynamicstoploss"></a>

\===

```csharp
public static void SetDynamicStopLoss(bool value)
```

***

### `SetDynamicTakeProfit` <a href="#method-setdynamictakeprofit" id="method-setdynamictakeprofit"></a>

\===

```csharp
public static void SetDynamicTakeProfit(bool value)
```

`value` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `SetPositionPartClose` <a href="#method-setpositionpartclose" id="method-setpositionpartclose"></a>

\===

```csharp
public static void SetPositionPartClose(bool value)
```

***

### `SetServerStopLoss` <a href="#method-setserverstoploss" id="method-setserverstoploss"></a>

\===

```csharp
public static void SetServerStopLoss(bool value)
```

`value` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `SetServerTakeProfit` <a href="#method-setservertakeprofit" id="method-setservertakeprofit"></a>

\===

```csharp
public static void SetServerTakeProfit(bool value)
```

***

### `SetViewDeletedSymbols` <a href="#method-setviewdeletedsymbols" id="method-setviewdeletedsymbols"></a>

\===

```csharp
public static void SetViewDeletedSymbols(bool value)
```

`value` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `SetViewOptionsSymbols` <a href="#method-setviewoptionssymbols" id="method-setviewoptionssymbols"></a>

\===

```csharp
public static void SetViewOptionsSymbols(bool value)
```

***

***

***

## Свойства

### `AccountValidator` <a href="#property-accountvalidator" id="property-accountvalidator"></a>

\===

```csharp
public static zYmFZWVu32MJxRml897u AccountValidator { get; private set; }
```

***

### `CommonDataPath;` <a href="#property-commondatapath" id="property-commondatapath"></a>

\===

```csharp
public static string CommonDataPath; {}
```

***

### `SortSettings` <a href="#property-sortsettings" id="property-sortsettings"></a>

\===

```csharp
public static tlSh00wib4PcbfluEhqD SortSettings { get; set; }
```

***
