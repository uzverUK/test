# ObjectLine

`namespace` [TigerTrade.Chart](../../../../).[Objects](../).[Common](./)

\===

#### Синтаксис

```csharp
public sealed class ObjectLine : INotifyPropertyChanged
```

## Список методов

| Название                                           | Описание |
| -------------------------------------------------- | -------- |
| [`ObjectLine`](objectline.cs.md#method-objectline) | _===_    |
| [`ToString`](objectline.cs.md#method-tostring)     | _===_    |

## Список свойств

| Название                                           | Описание |
| -------------------------------------------------- | -------- |
| [`LineBrush`](objectline.cs.md#property-linebrush) | _===_    |
| [`LineColor`](objectline.cs.md#property-linecolor) | _===_    |
| [`LinePen`](objectline.cs.md#property-linepen)     | _===_    |
| [`LineStyle`](objectline.cs.md#property-linestyle) | _===_    |
| [`LineWidth`](objectline.cs.md#property-linewidth) | _===_    |
| [`ShowLine`](objectline.cs.md#property-showline)   | _===_    |
| [`Value`](objectline.cs.md#property-value)         | _===_    |

## Список событий

| Название                                                    | Описание |
| ----------------------------------------------------------- | -------- |
| [`PropertyChanged`](objectline.cs.md#event-propertychanged) | _===_    |

***

***

## Методы

### `ObjectLine` <a href="#method-objectline" id="method-objectline"></a>

\===

```csharp
public ObjectLine()
```

***

### `ObjectLine` <a href="#method-objectline" id="method-objectline"></a>

\===

```csharp
public ObjectLine()
public ObjectLine(double value, XColor color)
```

`value` _<mark style="color:red;">`double`</mark>_\
_===_

`color` _<mark style="color:red;">`XColor`</mark>_\
_===_

***

### `ObjectLine` <a href="#method-objectline" id="method-objectline"></a>

\===

```csharp
public ObjectLine()
public ObjectLine(double value, XColor color)
public ObjectLine(ObjectLine line)
```

`value` _<mark style="color:red;">`double`</mark>_\
_===_

`color` _<mark style="color:red;">`XColor`</mark>_\
_===_

`line` _<mark style="color:red;">`ObjectLine`</mark>_\
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

### `LineBrush` <a href="#property-linebrush" id="property-linebrush"></a>

\===

```csharp
public XBrush LineBrush { get; private set; }
```

***

### `LineColor` <a href="#property-linecolor" id="property-linecolor"></a>

\===

```csharp
public XColor LineColor { get; set; }
```

***

### `LinePen` <a href="#property-linepen" id="property-linepen"></a>

\===

```csharp
public XPen LinePen { get; private set; }
```

***

### `LineStyle` <a href="#property-linestyle" id="property-linestyle"></a>

\===

```csharp
public XDashStyle LineStyle { get; set; }
```

***

### `LineWidth` <a href="#property-linewidth" id="property-linewidth"></a>

\===

```csharp
public int LineWidth { get; set; }
```

***

### `ShowLine` <a href="#property-showline" id="property-showline"></a>

\===

```csharp
public bool ShowLine { get; set; }
```

***

### `Value` <a href="#property-value" id="property-value"></a>

\===

```csharp
public double Value { get; set; }
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
