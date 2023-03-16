
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


Описание

### Синтаксис
```csharp
public static class TcManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetMarketDataConnections`](./TcManager.cs/Методы/GetMarketDataConnections.md) | *Описание* |
| [`Load`](./TcManager.cs/Методы/Load.md) | *Описание* |
| [`LoadSimulator`](./TcManager.cs/Методы/LoadSimulator.md) | *Описание* |
| [`Save`](./TcManager.cs/Методы/Save.md) | *Описание* |
| [`SaveSettings`](./TcManager.cs/Методы/SaveSettings.md) | *Описание* |
| [`SetCancelOrdersOnClose`](./TcManager.cs/Методы/SetCancelOrdersOnClose.md) | *Описание* |
| [`SetDynamicStopLoss`](./TcManager.cs/Методы/SetDynamicStopLoss.md) | *Описание* |
| [`SetDynamicTakeProfit`](./TcManager.cs/Методы/SetDynamicTakeProfit.md) | *Описание* |
| [`SetPositionPartClose`](./TcManager.cs/Методы/SetPositionPartClose.md) | *Описание* |
| [`SetServerStopLoss`](./TcManager.cs/Методы/SetServerStopLoss.md) | *Описание* |
| [`SetServerTakeProfit`](./TcManager.cs/Методы/SetServerTakeProfit.md) | *Описание* |
| [`SetViewDeletedSymbols`](./TcManager.cs/Методы/SetViewDeletedSymbols.md) | *Описание* |
| [`SetViewOptionsSymbols`](./TcManager.cs/Методы/SetViewOptionsSymbols.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`AccountValidator`](./TcManager.cs/Свойства/AccountValidator.md) | *Описание* |
| [`CommonDataPath;`](./TcManager.cs/Свойства/CommonDataPath;.md) | *Описание* |
| [`SortSettings`](./TcManager.cs/Свойства/SortSettings.md) | *Описание* |





***  
***  
# Методы

## `GetMarketDataConnections`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static ConnectionInfo[] GetMarketDataConnections(string symbolId)
```

`symbolId` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `Load`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Load(byte[] clients)
```

***  

## `LoadSimulator`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void LoadSimulator()
```

***  

## `Save`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Save()
```

***  

## `SaveSettings`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SaveSettings()
```

***  

## `SetCancelOrdersOnClose`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetCancelOrdersOnClose(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetDynamicStopLoss`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetDynamicStopLoss(bool value)
```

***  

## `SetDynamicTakeProfit`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetDynamicTakeProfit(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetPositionPartClose`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetPositionPartClose(bool value)
```

***  

## `SetServerStopLoss`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetServerStopLoss(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetServerTakeProfit`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetServerTakeProfit(bool value)
```

***  

## `SetViewDeletedSymbols`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetViewDeletedSymbols(bool value)
```

`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `SetViewOptionsSymbols`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetViewOptionsSymbols(bool value)
```

***  
***  
 ***  
# Свойства

## `AccountValidator`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static zYmFZWVu32MJxRml897u AccountValidator { get; private set; }
```  
***

## `CommonDataPath;`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string CommonDataPath; {}
```  
***

## `SortSettings`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static tlSh00wib4PcbfluEhqD SortSettings { get; set; }
```  
***

