# ChartRegion

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Drawings](./)

\===

#### Синтаксис

```csharp
public sealed class ChartRegion : INotifyPropertyChanged
```

## Список методов

| Название                                              | Описание |
| ----------------------------------------------------- | -------- |
| [`ChartRegion`](chartregion.cs.md#method-chartregion) | _===_    |
| [`CopyTheme`](chartregion.cs.md#method-copytheme)     | _===_    |
| [`ToString`](chartregion.cs.md#method-tostring)       | _===_    |

## Список свойств

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`Color`](chartregion.cs.md#property-color)     | _===_    |
| [`Visible`](chartregion.cs.md#property-visible) | _===_    |

## Список событий

| Название                                                     | Описание |
| ------------------------------------------------------------ | -------- |
| [`PropertyChanged`](chartregion.cs.md#event-propertychanged) | _===_    |

***

***

## Методы

### `ChartRegion` <a href="#method-chartregion" id="method-chartregion"></a>

\===

```csharp
public ChartRegion()
```

***

### `ChartRegion` <a href="#method-chartregion" id="method-chartregion"></a>

\===

```csharp
public ChartRegion()
public ChartRegion(XColor color)
```

`color` _<mark style="color:red;">`XColor`</mark>_\
_===_

***

### `CopyTheme` <a href="#method-copytheme" id="method-copytheme"></a>

\===

```csharp
public void CopyTheme(ChartRegion chartRegion)
```

`chartRegion` _<mark style="color:red;">`ChartRegion`</mark>_\
_===_

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

***

***

***

## Свойства

### `Color` <a href="#property-color" id="property-color"></a>

\===

```csharp
public XColor Color { get; set; }
```

***

### `Visible` <a href="#property-visible" id="property-visible"></a>

\===

```csharp
public bool Visible { get; set; }
```

***

***

***

## События

### `PropertyChanged` <a href="#event-propertychanged" id="event-propertychanged"></a>

\===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```
