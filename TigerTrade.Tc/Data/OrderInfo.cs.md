
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


===

### Синтаксис
```csharp
public sealed class OrderInfo
```


# Список методов
| Название | Описание |
| --- | --- |
| [`OrderInfo`](#method-orderinfo) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ErrorMsg`](#property-errormsg) | *===* |
| [`Order`](#property-order) | *===* |
| [`Silent`](#property-silent) | *===* |
| [`Status`](#property-status) | *===* |





***  
***  
# Методы

## `OrderInfo`<a href="method-orderinfo" id="method-orderinfo"></a>
===
```csharp
public OrderInfo(Order order, OrderStatus status, string errorMsg = "")
```

`order` <mark style="color:red;">*`Order`*</mark>  
 *===*  

`status` <mark style="color:red;">*`OrderStatus`*</mark>  
 *===*  

`errorMsg` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `ErrorMsg`<a href="property-errormsg" id="property-errormsg"></a>
===
```csharp
public string ErrorMsg { get; set; }
```  
***

## `Order`<a href="property-order" id="property-order"></a>
===
```csharp
public Order Order { get; }
```  
***

## `Silent`<a href="property-silent" id="property-silent"></a>
===
```csharp
public bool Silent { get; }
```  
***

## `Status`<a href="property-status" id="property-status"></a>
===
```csharp
public OrderStatus Status { get; }
```  
***

