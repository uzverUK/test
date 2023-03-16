
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


===

### Синтаксис
```csharp
public sealed class TicksReader : BinReader<Tick>, IDataReader<Tick>
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ReadItem`](#method-readitem) | *===* |
| [`Reset`](#method-reset) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`PriceStep`](#property-pricestep) | *===* |
| [`SizeStep`](#property-sizestep) | *===* |
| [`Version`](#property-version) | *===* |





***  
***  
# Методы

## `ReadItem`<a href="method-readitem" id="method-readitem"></a>
===
```csharp
protected override Tick ReadItem()
```

***  

## `Reset`<a href="method-reset" id="method-reset"></a>
===
```csharp
public override void Reset()
```

***  
***  
 ***  
# Свойства

## `PriceStep`<a href="property-pricestep" id="property-pricestep"></a>
===
```csharp
public double PriceStep { get; private set; }
```  
***

## `SizeStep`<a href="property-sizestep" id="property-sizestep"></a>
===
```csharp
public double SizeStep { get; private set; }
```  
***

## `Version`<a href="property-version" id="property-version"></a>
===
```csharp
public int Version { get; private set; }
```  
***

