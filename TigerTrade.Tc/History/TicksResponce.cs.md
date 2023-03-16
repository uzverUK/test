
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class TicksResponce
```


# Список методов
| Название | Описание |
| --- | --- |
| [`TicksResponce`](#method-ticksresponce) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Reader`](#property-reader) | *Описание* |
| [`Request`](#property-request) | *Описание* |





***  
***  
# Методы

## `TicksResponce`<a href="method-ticksresponce" id="method-ticksresponce"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public TicksResponce(TicksRequest request, IDataReader<Tick> reader)
```

`request` <mark style="color:red;">*`TicksRequest`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Reader`<a href="property-reader" id="property-reader"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IDataReader<Tick> Reader { get; }
```  
***

## `Request`<a href="property-request" id="property-request"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public TicksRequest Request { get; }
```  
***

