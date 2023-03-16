
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class TicksRequest
```


# Список методов
| Название | Описание |
| --- | --- |
| [`TicksRequest`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`CustomData`](./TicksRequest.cs/Свойства/CustomData.md) | *Описание* |
| [`RequestID`](./TicksRequest.cs/Свойства/RequestID.md) | *Описание* |
| [`Symbol`](./TicksRequest.cs/Свойства/Symbol.md) | *Описание* |
| [`TargetID`](./TicksRequest.cs/Свойства/TargetID.md) | *Описание* |





***  
***  
# Методы

## `TicksRequest`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public TicksRequest(Symbol symbol, string requestID, string targetID, bool customData)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`requestID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`targetID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`customData` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `CustomData`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CustomData { get; set; }
```  
***

## `RequestID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string RequestID { get; set; }
```  
***

## `Symbol`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; set; }
```  
***

## `TargetID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TargetID { get; }
```  
***

