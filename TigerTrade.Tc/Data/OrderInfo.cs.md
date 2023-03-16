
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class OrderInfo
```


# Список методов
| Название | Описание |
| --- | --- |
| [`OrderInfo`](#OrderInfo-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ErrorMsg`](#ErrorMsg-p) | *Описание* |
| [`Order`](#Order-p) | *Описание* |
| [`Silent`](#Silent-p) | *Описание* |
| [`Status`](#Status-p) | *Описание* |





***  
***  
# Методы

## `OrderInfo`<a href="OrderInfo-m" id="OrderInfo-m"></a>
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

## `ErrorMsg`<a href="Status-p" id="Status-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ErrorMsg { get; set; }
```  
***

## `Order`<a href="Status-p" id="Status-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Order Order { get; }
```  
***

## `Silent`<a href="Status-p" id="Status-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Silent { get; }
```  
***

## `Status`<a href="Status-p" id="Status-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderStatus Status { get; }
```  
***

