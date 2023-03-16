
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class BarsResponce
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BarsResponce`](#BarsResponce-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Reader`](#Reader-p) | *Описание* |
| [`Request`](#Request-p) | *Описание* |





***  
***  
# Методы

## `BarsResponce`<a href="BarsResponce-m" id="BarsResponce-m"></a>
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

## `Reader`<a href="Reader-p" id="Reader-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IDataReader<Bar> Reader { get; }
```  
***

## `Request`<a href="Request-p" id="Request-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BarsRequest Request { get; }
```  
***

