# ChartLevel

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Drawings](./)

\===

#### Синтаксис

```csharp
public sealed class ChartLevel : INotifyPropertyChanged
```

## Список методов

| Название                                           | Описание |
| -------------------------------------------------- | -------- |
| [`ChartLevel`](chartlevel.cs.md#method-chartlevel) | _===_    |
| [`CopyTheme`](chartlevel.cs.md#method-copytheme)   | _===_    |
| [`ToString`](chartlevel.cs.md#method-tostring)     | _===_    |

## Список свойств

| Название                                           | Описание |
| -------------------------------------------------- | -------- |
| [`Color`](chartlevel.cs.md#property-color)         | _===_    |
| [`Level`](chartlevel.cs.md#property-level)         | _===_    |
| [`LineBrush`](chartlevel.cs.md#property-linebrush) | _===_    |
| [`LinePen`](chartlevel.cs.md#property-linepen)     | _===_    |
| [`Style`](chartlevel.cs.md#property-style)         | _===_    |
| [`Visible`](chartlevel.cs.md#property-visible)     | _===_    |
| [`Width`](chartlevel.cs.md#property-width)         | _===_    |

## Список событий

| Название                                                    | Описание |
| ----------------------------------------------------------- | -------- |
| [`PropertyChanged`](chartlevel.cs.md#event-propertychanged) | _===_    |

***

***

## Методы

### `ChartLevel` <a href="#method-chartlevel" id="method-chartlevel"></a>

\===

```csharp
public ChartLevel()
```

***

### `ChartLevel` <a href="#method-chartlevel" id="method-chartlevel"></a>

\===

```csharp
public ChartLevel()
public ChartLevel(Decimal level, XColor color)
```

`level` _<mark style="color:red;">`Decimal`</mark>_\
_===_

`color` _<mark style="color:red;">`XColor`</mark>_\
_===_

***

### `CopyTheme` <a href="#method-copytheme" id="method-copytheme"></a>

\===

```csharp
public void CopyTheme(ChartLevel chartLevel)
```

`chartLevel` _<mark style="color:red;">`ChartLevel`</mark>_\
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

### `Level` <a href="#property-level" id="property-level"></a>

\===

```csharp
public Decimal Level { get; set; }
```

***

### `LineBrush` <a href="#property-linebrush" id="property-linebrush"></a>

\===

```csharp
public XBrush LineBrush { get; private set; }
```

***

### `LinePen` <a href="#property-linepen" id="property-linepen"></a>

\===

```csharp
public XPen LinePen { get; private set; }
```

***

### `Style` <a href="#property-style" id="property-style"></a>

\===

```csharp
public XDashStyle Style { get; set; }
```

***

### `Visible` <a href="#property-visible" id="property-visible"></a>

\===

```csharp
public bool Visible { get; set; }
```

***

### `Width` <a href="#property-width" id="property-width"></a>

\===

```csharp
public int Width { get; set; }
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
