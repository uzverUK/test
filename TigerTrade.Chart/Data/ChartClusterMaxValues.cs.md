
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Data](../../TigerTrade.Chart/Data.md)


===

### Синтаксис
```csharp
public sealed class ChartClusterMaxValues : IChartClusterMaxValues
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartClusterMaxValues`](#method-chartclustermaxvalues) | *===* |
| [`Update`](#method-update) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`MaxAsk`](#property-maxask) | *===* |
| [`MaxBid`](#property-maxbid) | *===* |
| [`MaxDelta`](#property-maxdelta) | *===* |
| [`MaxOpenPos`](#property-maxopenpos) | *===* |
| [`MaxTrades`](#property-maxtrades) | *===* |
| [`MaxVolume`](#property-maxvolume) | *===* |
| [`MinDelta`](#property-mindelta) | *===* |
| [`MinOpenPos`](#property-minopenpos) | *===* |
| [`Poc`](#property-poc) | *===* |





***  
***  
# Методы

## `ChartClusterMaxValues`<a href="method-chartclustermaxvalues" id="method-chartclustermaxvalues"></a>
===
```csharp
public ChartClusterMaxValues()
```

***  

## `Update`<a href="method-update" id="method-update"></a>
===
```csharp
public void Update(Dictionary<Decimal, ChartClusterItem> items)
```

***  
***  
 ***  
# Свойства

## `MaxAsk`<a href="property-maxask" id="property-maxask"></a>
===
```csharp
public Decimal MaxAsk { get; private set; }
```  
***

## `MaxBid`<a href="property-maxbid" id="property-maxbid"></a>
===
```csharp
public Decimal MaxBid { get; private set; }
```  
***

## `MaxDelta`<a href="property-maxdelta" id="property-maxdelta"></a>
===
```csharp
public Decimal MaxDelta { get; private set; }
```  
***

## `MaxOpenPos`<a href="property-maxopenpos" id="property-maxopenpos"></a>
===
```csharp
public long MaxOpenPos { get; private set; }
```  
***

## `MaxTrades`<a href="property-maxtrades" id="property-maxtrades"></a>
===
```csharp
public int MaxTrades { get; private set; }
```  
***

## `MaxVolume`<a href="property-maxvolume" id="property-maxvolume"></a>
===
```csharp
public Decimal MaxVolume { get; private set; }
```  
***

## `MinDelta`<a href="property-mindelta" id="property-mindelta"></a>
===
```csharp
public Decimal MinDelta { get; private set; }
```  
***

## `MinOpenPos`<a href="property-minopenpos" id="property-minopenpos"></a>
===
```csharp
public long MinOpenPos { get; private set; }
```  
***

## `Poc`<a href="property-poc" id="property-poc"></a>
===
```csharp
public Decimal Poc { get; private set; }
```  
***

