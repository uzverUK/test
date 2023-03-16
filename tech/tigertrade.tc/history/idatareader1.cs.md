# IDataReader1

`namespace` [TigerTrade.Tc](../).[History](./)

\===

#### Синтаксис

```csharp
public interface IDataReader<out T>
```

## Список методов

| Название                                       | Описание |
| ---------------------------------------------- | -------- |
| [`Dispose`](idatareader1.cs.md#method-dispose) | _===_    |
| [`Read`](idatareader1.cs.md#method-read)       | _===_    |
| [`Reset`](idatareader1.cs.md#method-reset)     | _===_    |

## Список свойств

| Название                                           | Описание |
| -------------------------------------------------- | -------- |
| [`IsEmpty`](idatareader1.cs.md#property-isempty)   | _===_    |
| [`LastItem`](idatareader1.cs.md#property-lastitem) | _===_    |
| [`PrevItem`](idatareader1.cs.md#property-previtem) | _===_    |

***

***

## Методы

### `Dispose` <a href="#method-dispose" id="method-dispose"></a>

\===

```csharp
void Dispose()
```

***

### `Read` <a href="#method-read" id="method-read"></a>

\===

```csharp
bool Read()
```

***

### `Reset` <a href="#method-reset" id="method-reset"></a>

\===

```csharp
void Reset()
```

***

***

***

## Свойства

### `IsEmpty` <a href="#property-isempty" id="property-isempty"></a>

\===

```csharp
bool IsEmpty { get; }
```

***

### `LastItem` <a href="#property-lastitem" id="property-lastitem"></a>

\===

```csharp
T LastItem { get; }
```

***

### `PrevItem` <a href="#property-previtem" id="property-previtem"></a>

\===

```csharp
T PrevItem { get; }
```

***
