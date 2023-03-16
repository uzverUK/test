
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public sealed class ObjectLine : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ObjectLine`](#method-objectline) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`LineBrush`](#property-linebrush) | *Описание* |
| [`LineColor`](#property-linecolor) | *Описание* |
| [`LinePen`](#property-linepen) | *Описание* |
| [`LineStyle`](#property-linestyle) | *Описание* |
| [`LineWidth`](#property-linewidth) | *Описание* |
| [`ShowLine`](#property-showline) | *Описание* |
| [`Value`](#property-value) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *Описание* |





***  
***  
# Методы

## `ObjectLine`<a href="method-objectline" id="method-objectline"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectLine()
```

***  

## `ObjectLine`<a href="method-objectline" id="method-objectline"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectLine()
public ObjectLine(double value, XColor color)
```

`value` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  


***  

## `ObjectLine`<a href="method-objectline" id="method-objectline"></a>
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


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `LineBrush`<a href="property-linebrush" id="property-linebrush"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XBrush LineBrush { get; private set; }
```  
***

## `LineColor`<a href="property-linecolor" id="property-linecolor"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor LineColor { get; set; }
```  
***

## `LinePen`<a href="property-linepen" id="property-linepen"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XPen LinePen { get; private set; }
```  
***

## `LineStyle`<a href="property-linestyle" id="property-linestyle"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle LineStyle { get; set; }
```  
***

## `LineWidth`<a href="property-linewidth" id="property-linewidth"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LineWidth { get; set; }
```  
***

## `ShowLine`<a href="property-showline" id="property-showline"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowLine { get; set; }
```  
***

## `Value`<a href="property-value" id="property-value"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Value { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

