# ChartLine

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Drawings](./)

\===

#### Синтаксис

```csharp
public sealed class ChartLine : INotifyPropertyChanged
```

## Список методов

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`ChartLine`](chartline.cs.md#method-chartline) | _===_    |
| [`CopyTheme`](chartline.cs.md#method-copytheme) | _===_    |
| [`ToString`](chartline.cs.md#method-tostring)   | _===_    |

## Список свойств

| Название                                            | Описание |
| --------------------------------------------------- | -------- |
| [`Color`](chartline.cs.md#property-color)           | _===_    |
| [`ShowMarker`](chartline.cs.md#property-showmarker) | _===_    |
| [`Style`](chartline.cs.md#property-style)           | _===_    |
| [`Visible`](chartline.cs.md#property-visible)       | _===_    |
| [`Width`](chartline.cs.md#property-width)           | _===_    |

## Список событий

| Название                                                   | Описание |
| ---------------------------------------------------------- | -------- |
| [`PropertyChanged`](chartline.cs.md#event-propertychanged) | _===_    |

***

***

## Методы

### `ChartLine` <a href="#method-chartline" id="method-chartline"></a>

\===

```csharp
public ChartLine()
```

***

### `CopyTheme` <a href="#method-copytheme" id="method-copytheme"></a>

\===

```csharp
public void CopyTheme(ChartLine chartLine)
```

`chartLine` _<mark style="color:red;">`ChartLine`</mark>_\
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

### `ShowMarker` <a href="#property-showmarker" id="property-showmarker"></a>

\===

```csharp
public bool ShowMarker { get; set; }
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
