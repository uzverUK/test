
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class UserPositionData
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ClearPosition`](#ClearPosition-m) | *Описание* |
| [`ClosePosition`](#ClosePosition-m) | *Описание* |
| [`HidePosition`](#HidePosition-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsLive`](#IsLive-p) | *Описание* |
| [`IsPlayer`](#IsPlayer-p) | *Описание* |
| [`IsSimulator`](#IsSimulator-p) | *Описание* |





***  
***  
# Методы

## `ClearPosition`<a href="ClearPosition-m" id="ClearPosition-m"></a>
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

## `ClosePosition`<a href="ClosePosition-m" id="ClosePosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static UserPositionData ClosePosition(string connectionID, string positionID)
```

***  

## `HidePosition`<a href="HidePosition-m" id="HidePosition-m"></a>
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

## `IsLive`<a href="IsLive-p" id="IsLive-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsLive { get; }
```  
***

## `IsPlayer`<a href="IsPlayer-p" id="IsPlayer-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsPlayer { get; }
```  
***

## `IsSimulator`<a href="IsSimulator-p" id="IsSimulator-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSimulator { get; }
```  
***

