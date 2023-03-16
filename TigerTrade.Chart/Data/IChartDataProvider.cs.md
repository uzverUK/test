
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public interface IChartDataProvider
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetCluster`](#GetCluster-m) | *Описание* |
| [`GetMarketDepth`](#GetMarketDepth-m) | *Описание* |
| [`GetRawCluster`](#GetRawCluster-m) | *Описание* |
| [`GetRawMarketDepth`](#GetRawMarketDepth-m) | *Описание* |
| [`GetRawSecurity`](#GetRawSecurity-m) | *Описание* |
| [`GetSecurity`](#GetSecurity-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Count`](#Count-p) | *Описание* |
| [`Period`](#Period-p) | *Описание* |
| [`Scale`](#Scale-p) | *Описание* |
| [`Step`](#Step-p) | *Описание* |
| [`Symbol`](#Symbol-p) | *Описание* |





***  
***  
# Методы

## `GetCluster`<a href="GetCluster-m" id="GetCluster-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartCluster GetCluster(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetMarketDepth`<a href="GetMarketDepth-m" id="GetMarketDepth-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartMarketDepth GetMarketDepth()
```

***  

## `GetRawCluster`<a href="GetRawCluster-m" id="GetRawCluster-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawCluster GetRawCluster(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetRawMarketDepth`<a href="GetRawMarketDepth-m" id="GetRawMarketDepth-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawMarketDepth GetRawMarketDepth()
```

***  

## `GetRawSecurity`<a href="GetRawSecurity-m" id="GetRawSecurity-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawSecurity GetRawSecurity()
```

***  

## `GetSecurity`<a href="GetSecurity-m" id="GetSecurity-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartSecurity GetSecurity()
```

***  
***  
 ***  
# Свойства

## `Count`<a href="Count-p" id="Count-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Count { get; }
```  
***

## `Period`<a href="Period-p" id="Period-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartPeriod Period { get; }
```  
***

## `Scale`<a href="Scale-p" id="Scale-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Scale { get; }
```  
***

## `Step`<a href="Step-p" id="Step-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double Step { get; }
```  
***

## `Symbol`<a href="Symbol-p" id="Symbol-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartSymbol Symbol { get; }
```  
***

