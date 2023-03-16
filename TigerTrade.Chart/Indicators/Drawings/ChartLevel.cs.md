
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


Описание

### Синтаксис
```csharp
public sealed class ChartLevel : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartLevel`](#method-chartlevel) | *Описание* |
| [`CopyTheme`](#method-copytheme) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Color`](#property-color) | *Описание* |
| [`Level`](#property-level) | *Описание* |
| [`LineBrush`](#property-linebrush) | *Описание* |
| [`LinePen`](#property-linepen) | *Описание* |
| [`Style`](#property-style) | *Описание* |
| [`Visible`](#property-visible) | *Описание* |
| [`Width`](#property-width) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *Описание* |





***  
***  
# Методы

## `ChartLevel`<a href="method-chartlevel" id="method-chartlevel"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartLevel()
```

***  

## `ChartLevel`<a href="method-chartlevel" id="method-chartlevel"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartLevel()
public ChartLevel(Decimal level, XColor color)
```

`level` <mark style="color:red;">*`Decimal`*</mark>  
 *Описание*  

`color` <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  


***  

## `CopyTheme`<a href="method-copytheme" id="method-copytheme"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CopyTheme(ChartLevel chartLevel)
```
`chartLevel` <mark style="color:red;">*`ChartLevel`*</mark>  
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

## `Color`<a href="property-color" id="property-color"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color { get; set; }
```  
***

## `Level`<a href="property-level" id="property-level"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Level { get; set; }
```  
***

## `LineBrush`<a href="property-linebrush" id="property-linebrush"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XBrush LineBrush { get; private set; }
```  
***

## `LinePen`<a href="property-linepen" id="property-linepen"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XPen LinePen { get; private set; }
```  
***

## `Style`<a href="property-style" id="property-style"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle Style { get; set; }
```  
***

## `Visible`<a href="property-visible" id="property-visible"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Visible { get; set; }
```  
***

## `Width`<a href="property-width" id="property-width"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Width { get; set; }
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

