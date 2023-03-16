
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class TicksRequest
```


# Список методов
| Название | Описание |
| --- | --- |
| [`TicksRequest`](#method-ticksrequest) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`CustomData`](#property-customdata) | *Описание* |
| [`RequestID`](#property-requestid) | *Описание* |
| [`Symbol`](#property-symbol) | *Описание* |
| [`TargetID`](#property-targetid) | *Описание* |





***  
***  
# Методы

## `TicksRequest`<a href="method-ticksrequest" id="method-ticksrequest"></a>
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

## `CustomData`<a href="property-customdata" id="property-customdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CustomData { get; set; }
```  
***

## `RequestID`<a href="property-requestid" id="property-requestid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string RequestID { get; set; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; set; }
```  
***

## `TargetID`<a href="property-targetid" id="property-targetid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string TargetID { get; }
```  
***

