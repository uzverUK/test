
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class TicksResponce
```


# Список методов
| Название | Описание |
| --- | --- |
| [`TicksResponce`](#TicksResponce-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Reader`](#Reader-p) | *Описание* |
| [`Request`](#Request-p) | *Описание* |





***  
***  
# Методы

## `TicksResponce`<a href="TicksResponce-m" id="TicksResponce-m"></a>
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

## `Reader`<a href="Request-p" id="Request-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IDataReader<Tick> Reader { get; }
```  
***

## `Request`<a href="Request-p" id="Request-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public TicksRequest Request { get; }
```  
***

