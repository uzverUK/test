
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

## *GetCluster*
Описание

```csharp
IChartCluster GetCluster(int i)
```

<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *GetMarketDepth*
Описание

```csharp
IChartMarketDepth GetMarketDepth()
```


## *GetRawCluster*
Описание

```csharp
IRawCluster GetRawCluster(int i)
```

<mark style="color:yellow;">`i`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *GetRawMarketDepth*
Описание

```csharp
IRawMarketDepth GetRawMarketDepth()
```


## *GetRawSecurity*
Описание

```csharp
IRawSecurity GetRawSecurity()
```


## *GetSecurity*
Описание

```csharp
IChartSecurity GetSecurity()
```

# Свойства

## *Count*
> Описание

```csharp
int Count { get; }
```

## *Period*
> Описание

```csharp
IChartPeriod Period { get; }
```

## *Scale*
> Описание

```csharp
int Scale { get; }
```

## *Step*
> Описание

```csharp
double Step { get; }
```

## *Symbol*
> Описание

```csharp
IChartSymbol Symbol { get; }
```

