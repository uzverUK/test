
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class OrderInfo
```


# Список методов
| Название | Описание |
| --- | --- |
| [`OrderInfo`](./OrderInfo.cs/Методы/OrderInfo.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ErrorMsg`](./OrderInfo.cs/Свойства/ErrorMsg.md) | *Описание* |
| [`Order`](./OrderInfo.cs/Свойства/Order.md) | *Описание* |
| [`Silent`](./OrderInfo.cs/Свойства/Silent.md) | *Описание* |
| [`Status`](./OrderInfo.cs/Свойства/Status.md) | *Описание* |





***  
***  
# Методы

## `OrderInfo<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderInfo(Order order, OrderStatus status, string errorMsg = "")
```

`order` <mark style="color:red;">*`Order`*</mark>  
 *Описание*  

`status` <mark style="color:red;">*`OrderStatus`*</mark>  
 *Описание*  

`errorMsg` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `ErrorMsg`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ErrorMsg { get; set; }
```  
***

## `Order`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Order Order { get; }
```  
***

## `Silent`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Silent { get; }
```  
***

## `Status`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderStatus Status { get; }
```  
***

