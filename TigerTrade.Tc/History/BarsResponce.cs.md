
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class BarsResponce
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BarsResponce`](#method-barsresponce) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Reader`](#property-reader) | *Описание* |
| [`Request`](#property-request) | *Описание* |





***  
***  
# Методы

## `BarsResponce`<a href="method-barsresponce" id="method-barsresponce"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BarsResponce(BarsRequest request, IDataReader<Bar> reader)
```

`request` <mark style="color:red;">*`BarsRequest`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Reader`<a href="property-reader" id="property-reader"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IDataReader<Bar> Reader { get; }
```  
***

## `Request`<a href="property-request" id="property-request"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BarsRequest Request { get; }
```  
***

