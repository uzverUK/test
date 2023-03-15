
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


Описание

### Синтаксис
```csharp
public interface IChartDataProvider
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`GetCluster`](./IChartDataProvider.cs/Методы/GetCluster.md) | *Описание* |
| [`GetMarketDepth`](./IChartDataProvider.cs/Методы/GetMarketDepth.md) | *Описание* |
| [`GetRawCluster`](./IChartDataProvider.cs/Методы/GetRawCluster.md) | *Описание* |
| [`GetRawMarketDepth`](./IChartDataProvider.cs/Методы/GetRawMarketDepth.md) | *Описание* |
| [`GetRawSecurity`](./IChartDataProvider.cs/Методы/GetRawSecurity.md) | *Описание* |
| [`GetSecurity`](./IChartDataProvider.cs/Методы/GetSecurity.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Count`](./IChartDataProvider.cs/Свойства/Count.md) | *Описание* |
| [`Period`](./IChartDataProvider.cs/Свойства/Period.md) | *Описание* |
| [`Scale`](./IChartDataProvider.cs/Свойства/Scale.md) | *Описание* |
| [`Step`](./IChartDataProvider.cs/Свойства/Step.md) | *Описание* |
| [`Symbol`](./IChartDataProvider.cs/Свойства/Symbol.md) | *Описание* |





# Методы

## `GetCluster`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartCluster GetCluster(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## `GetMarketDepth`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartMarketDepth GetMarketDepth()
```


## `GetRawCluster`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawCluster GetRawCluster(int i)
```

`i` <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## `GetRawMarketDepth`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawMarketDepth GetRawMarketDepth()
```


## `GetRawSecurity`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IRawSecurity GetRawSecurity()
```


## `GetSecurity`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartSecurity GetSecurity()
```

# Свойства

## `Count`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Count { get; }
```

## `Period`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartPeriod Period { get; }
```

## `Scale`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
int Scale { get; }
```

## `Step`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
double Step { get; }
```

## `Symbol`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
IChartSymbol Symbol { get; }
```

