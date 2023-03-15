
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public sealed class ObjectLine : INotifyPropertyChanged
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ObjectLine`](./ObjectLine.cs/Методы/ObjectLine.md) | *Описание* |
| [`ToString`](./ObjectLine.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`LineBrush`](./ObjectLine.cs/Свойства/LineBrush.md) | *Описание* |
| [`LineColor`](./ObjectLine.cs/Свойства/LineColor.md) | *Описание* |
| [`LinePen`](./ObjectLine.cs/Свойства/LinePen.md) | *Описание* |
| [`LineStyle`](./ObjectLine.cs/Свойства/LineStyle.md) | *Описание* |
| [`LineWidth`](./ObjectLine.cs/Свойства/LineWidth.md) | *Описание* |
| [`ShowLine`](./ObjectLine.cs/Свойства/ShowLine.md) | *Описание* |
| [`Value`](./ObjectLine.cs/Свойства/Value.md) | *Описание* |

# Таблица событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ObjectLine.cs/События/PropertyChanged.md) | *Описание* |





# Методы

## *ObjectLine*
Описание

```csharp
public ObjectLine()
```


## *ObjectLine*
Описание

```csharp
public ObjectLine()
public ObjectLine(double value, XColor color)
```

<mark style="color:yellow;">`value`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:yellow;">`color`</mark> <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  



## *ObjectLine*
Описание

```csharp
public ObjectLine()
public ObjectLine(double value, XColor color)
public ObjectLine(ObjectLine line)
```

<mark style="color:yellow;">`value`</mark> <mark style="color:red;">*`double`*</mark>  
 *Описание*  

<mark style="color:yellow;">`color`</mark> <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  

<mark style="color:yellow;">`line`</mark> <mark style="color:red;">*`ObjectLine`*</mark>  
 *Описание*  



## *ToString*
Описание

```csharp
public override string ToString()
```

# Свойства

## *LineBrush*
Описание

```csharp
public XBrush LineBrush { get; private set; }
```

## *LineColor*
Описание

```csharp
public XColor LineColor { get; set; }
```

## *LinePen*
Описание

```csharp
public XPen LinePen { get; private set; }
```

## *LineStyle*
Описание

```csharp
public XDashStyle LineStyle { get; set; }
```

## *LineWidth*
Описание

```csharp
public int LineWidth { get; set; }
```

## *ShowLine*
Описание

```csharp
public bool ShowLine { get; set; }
```

## *Value*
Описание

```csharp
public double Value { get; set; }
```
# <font color="Purple">Событияs</font>

## *PropertyChanged*
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

