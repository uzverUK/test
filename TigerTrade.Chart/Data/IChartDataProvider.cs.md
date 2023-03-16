
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


===

### Синтаксис
```csharp
public interface IChartDataProvider
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetCluster`](#method-getcluster) | *===* |
| [`GetMarketDepth`](#method-getmarketdepth) | *===* |
| [`GetRawCluster`](#method-getrawcluster) | *===* |
| [`GetRawMarketDepth`](#method-getrawmarketdepth) | *===* |
| [`GetRawSecurity`](#method-getrawsecurity) | *===* |
| [`GetSecurity`](#method-getsecurity) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Count`](#property-count) | *===* |
| [`Period`](#property-period) | *===* |
| [`Scale`](#property-scale) | *===* |
| [`Step`](#property-step) | *===* |
| [`Symbol`](#property-symbol) | *===* |





***  
***  
# Методы

## `GetCluster`<a href="method-getcluster" id="method-getcluster"></a>
===
```csharp
IChartCluster GetCluster(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `GetMarketDepth`<a href="method-getmarketdepth" id="method-getmarketdepth"></a>
===
```csharp
IChartMarketDepth GetMarketDepth()
```

***  

## `GetRawCluster`<a href="method-getrawcluster" id="method-getrawcluster"></a>
===
```csharp
IRawCluster GetRawCluster(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `GetRawMarketDepth`<a href="method-getrawmarketdepth" id="method-getrawmarketdepth"></a>
===
```csharp
IRawMarketDepth GetRawMarketDepth()
```

***  

## `GetRawSecurity`<a href="method-getrawsecurity" id="method-getrawsecurity"></a>
===
```csharp
IRawSecurity GetRawSecurity()
```

***  

## `GetSecurity`<a href="method-getsecurity" id="method-getsecurity"></a>
===
```csharp
IChartSecurity GetSecurity()
```

***  
***  
 ***  
# Свойства

## `Count`<a href="property-count" id="property-count"></a>
===
```csharp
int Count { get; }
```  
***

## `Period`<a href="property-period" id="property-period"></a>
===
```csharp
IChartPeriod Period { get; }
```  
***

## `Scale`<a href="property-scale" id="property-scale"></a>
===
```csharp
int Scale { get; }
```  
***

## `Step`<a href="property-step" id="property-step"></a>
===
```csharp
double Step { get; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
===
```csharp
IChartSymbol Symbol { get; }
```  
***

