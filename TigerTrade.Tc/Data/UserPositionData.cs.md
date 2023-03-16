
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class UserPositionData
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ClearPosition`](#method-clearposition) | *Описание* |
| [`ClosePosition`](#method-closeposition) | *Описание* |
| [`HidePosition`](#method-hideposition) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsLive`](#property-islive) | *Описание* |
| [`IsPlayer`](#property-isplayer) | *Описание* |
| [`IsSimulator`](#property-issimulator) | *Описание* |





***  
***  
# Методы

## `ClearPosition`<a href="method-clearposition" id="method-clearposition"></a>
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

## `ClosePosition`<a href="method-closeposition" id="method-closeposition"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static UserPositionData ClosePosition(string connectionID, string positionID)
```

***  

## `HidePosition`<a href="method-hideposition" id="method-hideposition"></a>
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

## `IsLive`<a href="property-islive" id="property-islive"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsLive { get; }
```  
***

## `IsPlayer`<a href="property-isplayer" id="property-isplayer"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsPlayer { get; }
```  
***

## `IsSimulator`<a href="property-issimulator" id="property-issimulator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsSimulator { get; }
```  
***

