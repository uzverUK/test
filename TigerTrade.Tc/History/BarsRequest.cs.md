
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class BarsRequest
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BarsRequest`](#method-barsrequest) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`RequestID`](#property-requestid) | *Описание* |
| [`Symbol`](#property-symbol) | *Описание* |
| [`TargetID`](#property-targetid) | *Описание* |





***  
***  
# Методы

## `BarsRequest`<a href="method-barsrequest" id="method-barsrequest"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BarsRequest(Symbol symbol, string requestID, string targetID)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`requestID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`targetID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

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

