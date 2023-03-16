
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public interface IChartDataProvider
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetCluster`](#method-getcluster) | *Описание* |
| [`GetMarketDepth`](#method-getmarketdepth) | *Описание* |
| [`GetRawCluster`](#method-getrawcluster) | *Описание* |
| [`GetRawMarketDepth`](#method-getrawmarketdepth) | *Описание* |
| [`GetRawSecurity`](#method-getrawsecurity) | *Описание* |
| [`GetSecurity`](#method-getsecurity) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Count`](#property-count) | *Описание* |
| [`Period`](#property-period) | *Описание* |
| [`Scale`](#property-scale) | *Описание* |
| [`Step`](#property-step) | *Описание* |
| [`Symbol`](#property-symbol) | *Описание* |





***  
***  
# Методы

## `GetCluster`<a href="method-getcluster" id="method-getcluster"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartCluster GetCluster(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetMarketDepth`<a href="method-getmarketdepth" id="method-getmarketdepth"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartMarketDepth GetMarketDepth()
```

***  

## `GetRawCluster`<a href="method-getrawcluster" id="method-getrawcluster"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawCluster GetRawCluster(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetRawMarketDepth`<a href="method-getrawmarketdepth" id="method-getrawmarketdepth"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawMarketDepth GetRawMarketDepth()
```

***  

## `GetRawSecurity`<a href="method-getrawsecurity" id="method-getrawsecurity"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawSecurity GetRawSecurity()
```

***  

## `GetSecurity`<a href="method-getsecurity" id="method-getsecurity"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartSecurity GetSecurity()
```

***  
***  
 ***  
# Свойства

## `Count`<a href="property-count" id="property-count"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Count { get; }
```  
***

## `Period`<a href="property-period" id="property-period"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartPeriod Period { get; }
```  
***

## `Scale`<a href="property-scale" id="property-scale"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Scale { get; }
```  
***

## `Step`<a href="property-step" id="property-step"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double Step { get; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartSymbol Symbol { get; }
```  
***

