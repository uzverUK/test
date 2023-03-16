
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class TicksRequest
```


# Список методов
| Название | Описание |
| --- | --- |
| [`TicksRequest`](#TicksRequest-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`CustomData`](#CustomData-p) | *Описание* |
| [`RequestID`](#RequestID-p) | *Описание* |
| [`Symbol`](#Symbol-p) | *Описание* |
| [`TargetID`](#TargetID-p) | *Описание* |





***  
***  
# Методы

## `TicksRequest`<a href="TicksRequest-m" id="TicksRequest-m"></a>
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

## `CustomData`<a href="CustomData-p" id="CustomData-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CustomData { get; set; }
```  
***

## `RequestID`<a href="RequestID-p" id="RequestID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string RequestID { get; set; }
```  
***

## `Symbol`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; set; }
```  
***

## `TargetID`<a href="TargetID-p" id="TargetID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TargetID { get; }
```  
***

