
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class BarsRequest
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BarsRequest`](#BarsRequest-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`RequestID`](#RequestID-p) | *Описание* |
| [`Symbol`](#Symbol-p) | *Описание* |
| [`TargetID`](#TargetID-p) | *Описание* |





***  
***  
# Методы

## `BarsRequest`<a href="BarsRequest-m" id="BarsRequest-m"></a>
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

## `RequestID`<a href="TargetID-p" id="TargetID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string RequestID { get; set; }
```  
***

## `Symbol`<a href="TargetID-p" id="TargetID-p"></a>
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

