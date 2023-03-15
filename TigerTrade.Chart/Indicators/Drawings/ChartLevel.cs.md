
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


Описание

### Синтаксис
```csharp
public sealed class ChartLevel : INotifyPropertyChanged
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ChartLevel`](./ChartLevel.cs/Методы/ChartLevel.md) | *Описание* |
| [`CopyTheme`](./ChartLevel.cs/Методы/CopyTheme.md) | *Описание* |
| [`ToString`](./ChartLevel.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Color`](./ChartLevel.cs/Свойства/Color.md) | *Описание* |
| [`Level`](./ChartLevel.cs/Свойства/Level.md) | *Описание* |
| [`LineBrush`](./ChartLevel.cs/Свойства/LineBrush.md) | *Описание* |
| [`LinePen`](./ChartLevel.cs/Свойства/LinePen.md) | *Описание* |
| [`Style`](./ChartLevel.cs/Свойства/Style.md) | *Описание* |
| [`Visible`](./ChartLevel.cs/Свойства/Visible.md) | *Описание* |
| [`Width`](./ChartLevel.cs/Свойства/Width.md) | *Описание* |

# Таблица событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ChartLevel.cs/События/PropertyChanged.md) | *Описание* |





# Методы

## *ChartLevel*
Описание

```csharp
public ChartLevel()
```


## *ChartLevel*
Описание

```csharp
public ChartLevel()
public ChartLevel(Decimal level, XColor color)
```

<mark style="color:yellow;">`level`</mark> <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

<mark style="color:yellow;">`color`</mark> <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  



## *CopyTheme*
Описание

```csharp
public void CopyTheme(ChartLevel chartLevel)
```
<mark style="color:yellow;">`chartLevel`</mark> <mark style="color:red;">*`ChartLevel`*</mark>  
 *Описание*  



## *ToString*
Описание

```csharp
public override string ToString()
```

# Свойства

## *Color*
Описание

```csharp
public XColor Color { get; set; }
```

## *Level*
Описание

```csharp
public Decimal Level { get; set; }
```

## *LineBrush*
Описание

```csharp
public XBrush LineBrush { get; private set; }
```

## *LinePen*
Описание

```csharp
public XPen LinePen { get; private set; }
```

## *Style*
Описание

```csharp
public XDashStyle Style { get; set; }
```

## *Visible*
Описание

```csharp
public bool Visible { get; set; }
```

## *Width*
Описание

```csharp
public int Width { get; set; }
```
# <font color="Purple">События</font>

## *PropertyChanged*
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

