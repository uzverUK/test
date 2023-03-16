# TicksReader

`namespace` [TigerTrade.Tc](../).[History](./)

\===

#### Синтаксис

```csharp
public sealed class TicksReader : BinReader<Tick>, IDataReader<Tick>
```

## Список методов

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`ReadItem`](ticksreader.cs.md#method-readitem) | _===_    |
| [`Reset`](ticksreader.cs.md#method-reset)       | _===_    |

## Список свойств

| Название                                            | Описание |
| --------------------------------------------------- | -------- |
| [`PriceStep`](ticksreader.cs.md#property-pricestep) | _===_    |
| [`SizeStep`](ticksreader.cs.md#property-sizestep)   | _===_    |
| [`Version`](ticksreader.cs.md#property-version)     | _===_    |

***

***

## Методы

### `ReadItem` <a href="#method-readitem" id="method-readitem"></a>

\===

```csharp
protected override Tick ReadItem()
```

***

### `Reset` <a href="#method-reset" id="method-reset"></a>

\===

```csharp
public override void Reset()
```

***

***

***

## Свойства

### `PriceStep` <a href="#property-pricestep" id="property-pricestep"></a>

\===

```csharp
public double PriceStep { get; private set; }
```

***

### `SizeStep` <a href="#property-sizestep" id="property-sizestep"></a>

\===

```csharp
public double SizeStep { get; private set; }
```

***

### `Version` <a href="#property-version" id="property-version"></a>

\===

```csharp
public int Version { get; private set; }
```

***
