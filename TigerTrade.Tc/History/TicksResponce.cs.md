
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class TicksResponce
```


# Список методов
| Название | Описание |
| --- | --- |
| [`TicksResponce`](./TicksResponce.cs/Методы/TicksResponce.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Reader`](./TicksResponce.cs/Свойства/Reader.md) | *Описание* |
| [`Request`](./TicksResponce.cs/Свойства/Request.md) | *Описание* |





***  
***  
# Методы

## `TicksResponce`
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

## `Reader`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IDataReader<Tick> Reader { get; }
```  
***

## `Request`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public TicksRequest Request { get; }
```  
***

