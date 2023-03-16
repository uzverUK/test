
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class UserPositionData
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ClearPosition`](./UserPositionData.cs/Методы/ClearPosition.md) | *Описание* |
| [`ClosePosition`](./UserPositionData.cs/Методы/ClosePosition.md) | *Описание* |
| [`HidePosition`](./UserPositionData.cs/Методы/HidePosition.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsLive`](./UserPositionData.cs/Свойства/IsLive.md) | *Описание* |
| [`IsPlayer`](./UserPositionData.cs/Свойства/IsPlayer.md) | *Описание* |
| [`IsSimulator`](./UserPositionData.cs/Свойства/IsSimulator.md) | *Описание* |





***  
***  
# Методы

## `ClearPosition`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static UserPositionData ClearPosition(string connectionID, string positionID)
```

`connectionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`positionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`UserPositionData` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `ClosePosition`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static UserPositionData ClosePosition(string connectionID, string positionID)
```

***  

## `HidePosition`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static UserPositionData HidePosition(string connectionID, string positionID)
```

`connectionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`positionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`UserPositionData` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `IsLive`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsLive { get; }
```  
***

## `IsPlayer`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsPlayer { get; }
```  
***

## `IsSimulator`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSimulator { get; }
```  
***

