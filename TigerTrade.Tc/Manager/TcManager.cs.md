
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


Описание

### Синтаксис
```csharp
public static class TcManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetMarketDataConnections`](#method-getmarketdataconnections) | *Описание* |
| [`Load`](#method-load) | *Описание* |
| [`LoadSimulator`](#method-loadsimulator) | *Описание* |
| [`Save`](#method-save) | *Описание* |
| [`SaveSettings`](#method-savesettings) | *Описание* |
| [`SetCancelOrdersOnClose`](#method-setcancelordersonclose) | *Описание* |
| [`SetDynamicStopLoss`](#method-setdynamicstoploss) | *Описание* |
| [`SetDynamicTakeProfit`](#method-setdynamictakeprofit) | *Описание* |
| [`SetPositionPartClose`](#method-setpositionpartclose) | *Описание* |
| [`SetServerStopLoss`](#method-setserverstoploss) | *Описание* |
| [`SetServerTakeProfit`](#method-setservertakeprofit) | *Описание* |
| [`SetViewDeletedSymbols`](#method-setviewdeletedsymbols) | *Описание* |
| [`SetViewOptionsSymbols`](#method-setviewoptionssymbols) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AccountValidator`](#property-accountvalidator) | *Описание* |
| [`CommonDataPath;`](#property-commondatapath;) | *Описание* |
| [`SortSettings`](#property-sortsettings) | *Описание* |





***  
***  
# Методы

## `GetMarketDataConnections`<a href="method-getmarketdataconnections" id="method-getmarketdataconnections"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static ConnectionInfo[] GetMarketDataConnections(string symbolId)
```

`symbolId` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Load`<a href="method-load" id="method-load"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Load(byte[] clients)
```

***  

## `LoadSimulator`<a href="method-loadsimulator" id="method-loadsimulator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void LoadSimulator()
```

***  

## `Save`<a href="method-save" id="method-save"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Save()
```

***  

## `SaveSettings`<a href="method-savesettings" id="method-savesettings"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SaveSettings()
```

***  

## `SetCancelOrdersOnClose`<a href="method-setcancelordersonclose" id="method-setcancelordersonclose"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetCancelOrdersOnClose(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetDynamicStopLoss`<a href="method-setdynamicstoploss" id="method-setdynamicstoploss"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetDynamicStopLoss(bool value)
```

***  

## `SetDynamicTakeProfit`<a href="method-setdynamictakeprofit" id="method-setdynamictakeprofit"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetDynamicTakeProfit(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetPositionPartClose`<a href="method-setpositionpartclose" id="method-setpositionpartclose"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetPositionPartClose(bool value)
```

***  

## `SetServerStopLoss`<a href="method-setserverstoploss" id="method-setserverstoploss"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetServerStopLoss(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetServerTakeProfit`<a href="method-setservertakeprofit" id="method-setservertakeprofit"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetServerTakeProfit(bool value)
```

***  

## `SetViewDeletedSymbols`<a href="method-setviewdeletedsymbols" id="method-setviewdeletedsymbols"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetViewDeletedSymbols(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetViewOptionsSymbols`<a href="method-setviewoptionssymbols" id="method-setviewoptionssymbols"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetViewOptionsSymbols(bool value)
```

***  
***  
 ***  
# Свойства

## `AccountValidator`<a href="property-accountvalidator" id="property-accountvalidator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static zYmFZWVu32MJxRml897u AccountValidator { get; private set; }
```  
***

## `CommonDataPath;`<a href="property-commondatapath;" id="property-commondatapath;"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string CommonDataPath; {}
```  
***

## `SortSettings`<a href="property-sortsettings" id="property-sortsettings"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static tlSh00wib4PcbfluEhqD SortSettings { get; set; }
```  
***

