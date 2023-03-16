
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class Execution
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Execution`](#Execution-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Account`](#Account-p) | *Описание* |
| [`Comission`](#Comission-p) | *Описание* |
| [`Connection`](#Connection-p) | *Описание* |
| [`Currency`](#Currency-p) | *Описание* |
| [`ExecutionID`](#ExecutionID-p) | *Описание* |
| [`ID`](#ID-p) | *Описание* |
| [`OrderID`](#OrderID-p) | *Описание* |
| [`Price`](#Price-p) | *Описание* |
| [`Quantity`](#Quantity-p) | *Описание* |
| [`RealizedPnl`](#RealizedPnl-p) | *Описание* |
| [`Side`](#Side-p) | *Описание* |
| [`Symbol`](#Symbol-p) | *Описание* |
| [`Time`](#Time-p) | *Описание* |





***  
***  
# Методы

## `Execution`<a href="Execution-m" id="Execution-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Execution(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Account`<a href="Account-p" id="Account-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Account Account { get; }
```  
***

## `Comission`<a href="Comission-p" id="Comission-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? Comission { get; set; }
```  
***

## `Connection`<a href="Connection-p" id="Connection-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ConnectionInfo Connection { get; }
```  
***

## `Currency`<a href="Currency-p" id="Currency-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Currency { get; set; }
```  
***

## `ExecutionID`<a href="ExecutionID-p" id="ExecutionID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ExecutionID { get; set; }
```  
***

## `ID`<a href="ID-p" id="ID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string ID { get; }
```  
***

## `OrderID`<a href="OrderID-p" id="OrderID-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string OrderID { get; set; }
```  
***

## `Price`<a href="Price-p" id="Price-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Price { get; set; }
```  
***

## `Quantity`<a href="Quantity-p" id="Quantity-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public long Quantity { get; set; }
```  
***

## `RealizedPnl`<a href="RealizedPnl-p" id="RealizedPnl-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double? RealizedPnl { get; set; }
```  
***

## `Side`<a href="Side-p" id="Side-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Side Side { get; set; }
```  
***

## `Symbol`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Symbol Symbol { get; }
```  
***

## `Time`<a href="Time-p" id="Time-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; set; }
```  
***

