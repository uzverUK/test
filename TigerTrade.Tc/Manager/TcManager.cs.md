
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


Описание

### Синтаксис
```csharp
public static class TcManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetMarketDataConnections`](#GetMarketDataConnections-m) | *Описание* |
| [`Load`](#Load-m) | *Описание* |
| [`LoadSimulator`](#LoadSimulator-m) | *Описание* |
| [`Save`](#Save-m) | *Описание* |
| [`SaveSettings`](#SaveSettings-m) | *Описание* |
| [`SetCancelOrdersOnClose`](#SetCancelOrdersOnClose-m) | *Описание* |
| [`SetDynamicStopLoss`](#SetDynamicStopLoss-m) | *Описание* |
| [`SetDynamicTakeProfit`](#SetDynamicTakeProfit-m) | *Описание* |
| [`SetPositionPartClose`](#SetPositionPartClose-m) | *Описание* |
| [`SetServerStopLoss`](#SetServerStopLoss-m) | *Описание* |
| [`SetServerTakeProfit`](#SetServerTakeProfit-m) | *Описание* |
| [`SetViewDeletedSymbols`](#SetViewDeletedSymbols-m) | *Описание* |
| [`SetViewOptionsSymbols`](#SetViewOptionsSymbols-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AccountValidator`](#AccountValidator-p) | *Описание* |
| [`CommonDataPath;`](#CommonDataPath;-p) | *Описание* |
| [`SortSettings`](#SortSettings-p) | *Описание* |





***  
***  
# Методы

## `GetMarketDataConnections`<a href="GetMarketDataConnections-m" id="GetMarketDataConnections-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static ConnectionInfo[] GetMarketDataConnections(string symbolId)
```

`symbolId` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Load`<a href="Load-m" id="Load-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Load(byte[] clients)
```

***  

## `LoadSimulator`<a href="LoadSimulator-m" id="LoadSimulator-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void LoadSimulator()
```

***  

## `Save`<a href="Save-m" id="Save-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Save()
```

***  

## `SaveSettings`<a href="SaveSettings-m" id="SaveSettings-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SaveSettings()
```

***  

## `SetCancelOrdersOnClose`<a href="SetCancelOrdersOnClose-m" id="SetCancelOrdersOnClose-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetCancelOrdersOnClose(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetDynamicStopLoss`<a href="SetDynamicStopLoss-m" id="SetDynamicStopLoss-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetDynamicStopLoss(bool value)
```

***  

## `SetDynamicTakeProfit`<a href="SetDynamicTakeProfit-m" id="SetDynamicTakeProfit-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetDynamicTakeProfit(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetPositionPartClose`<a href="SetPositionPartClose-m" id="SetPositionPartClose-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetPositionPartClose(bool value)
```

***  

## `SetServerStopLoss`<a href="SetServerStopLoss-m" id="SetServerStopLoss-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetServerStopLoss(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetServerTakeProfit`<a href="SetServerTakeProfit-m" id="SetServerTakeProfit-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetServerTakeProfit(bool value)
```

***  

## `SetViewDeletedSymbols`<a href="SetViewDeletedSymbols-m" id="SetViewDeletedSymbols-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetViewDeletedSymbols(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetViewOptionsSymbols`<a href="SetViewOptionsSymbols-m" id="SetViewOptionsSymbols-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetViewOptionsSymbols(bool value)
```

***  
***  
 ***  
# Свойства

## `AccountValidator`<a href="AccountValidator-p" id="AccountValidator-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static zYmFZWVu32MJxRml897u AccountValidator { get; private set; }
```  
***

## `CommonDataPath;`<a href="CommonDataPath;-p" id="CommonDataPath;-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string CommonDataPath; {}
```  
***

## `SortSettings`<a href="SortSettings-p" id="SortSettings-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static tlSh00wib4PcbfluEhqD SortSettings { get; set; }
```  
***

