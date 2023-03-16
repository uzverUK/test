
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class BarsResponce
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BarsResponce`](./BarsResponce.cs/Методы/BarsResponce.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Reader`](./BarsResponce.cs/Свойства/Reader.md) | *Описание* |
| [`Request`](./BarsResponce.cs/Свойства/Request.md) | *Описание* |





***  
***  
# Методы

## `BarsResponce<a href="test" id="test"></a>`
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

## `Reader`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IDataReader<Bar> Reader { get; }
```  
***

## `Request`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BarsRequest Request { get; }
```  
***

