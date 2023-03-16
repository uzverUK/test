
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class OrderInfo
```


# Список методов
| Название | Описание |
| --- | --- |
| [`OrderInfo`](#method-orderinfo) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ErrorMsg`](#property-errormsg) | *Описание* |
| [`Order`](#property-order) | *Описание* |
| [`Silent`](#property-silent) | *Описание* |
| [`Status`](#property-status) | *Описание* |





***  
***  
# Методы

## `OrderInfo`<a href="method-orderinfo" id="method-orderinfo"></a>
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

## `ErrorMsg`<a href="property-errormsg" id="property-errormsg"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ErrorMsg { get; set; }
```  
***

## `Order`<a href="property-order" id="property-order"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Order Order { get; }
```  
***

## `Silent`<a href="property-silent" id="property-silent"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Silent { get; }
```  
***

## `Status`<a href="property-status" id="property-status"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public OrderStatus Status { get; }
```  
***

