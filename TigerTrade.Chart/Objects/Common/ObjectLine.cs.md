
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

## `ObjectLine`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectLine()
```


## `ObjectLine`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectLine()
public ObjectLine(double value, XColor color)
```

`value` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  



## `ObjectLine`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectLine()
public ObjectLine(double value, XColor color)
public ObjectLine(ObjectLine line)
```

`value` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  

`line` <mark style="color:red;">*`ObjectLine`*</mark>  
 *Описание*  



## `ToString`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

# Свойства

## `LineBrush`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XBrush LineBrush { get; private set; }
```

## `LineColor`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor LineColor { get; set; }
```

## `LinePen`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XPen LinePen { get; private set; }
```

## `LineStyle`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle LineStyle { get; set; }
```

## `LineWidth`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LineWidth { get; set; }
```

## `ShowLine`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowLine { get; set; }
```

## `Value`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Value { get; set; }
```
# События

## `PropertyChanged`
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

