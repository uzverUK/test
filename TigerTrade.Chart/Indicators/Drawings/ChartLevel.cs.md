
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


Описание

### Синтаксис
```csharp
public sealed class ChartLevel : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartLevel`](#ChartLevel-m) | *Описание* |
| [`CopyTheme`](#CopyTheme-m) | *Описание* |
| [`ToString`](#ToString-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Color`](#Color-p) | *Описание* |
| [`Level`](#Level-p) | *Описание* |
| [`LineBrush`](#LineBrush-p) | *Описание* |
| [`LinePen`](#LinePen-p) | *Описание* |
| [`Style`](#Style-p) | *Описание* |
| [`Visible`](#Visible-p) | *Описание* |
| [`Width`](#Width-p) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#PropertyChanged-p) | *Описание* |





***  
***  
# Методы

## `ChartLevel`<a href="ChartLevel-m" id="ChartLevel-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartLevel()
```

***  

## `ChartLevel`<a href="ChartLevel-m" id="ChartLevel-m"></a>
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

## `CopyTheme`<a href="CopyTheme-m" id="CopyTheme-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CopyTheme(ChartLevel chartLevel)
```
`chartLevel` <mark style="color:red;">*`ChartLevel`*</mark>  
 *Описание*  


***  

## `ToString`<a href="ToString-m" id="ToString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Color`<a href="Color-p" id="Color-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color { get; set; }
```  
***

## `Level`<a href="Level-p" id="Level-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Level { get; set; }
```  
***

## `LineBrush`<a href="LineBrush-p" id="LineBrush-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XBrush LineBrush { get; private set; }
```  
***

## `LinePen`<a href="LinePen-p" id="LinePen-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XPen LinePen { get; private set; }
```  
***

## `Style`<a href="Style-p" id="Style-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle Style { get; set; }
```  
***

## `Visible`<a href="Visible-p" id="Visible-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Visible { get; set; }
```  
***

## `Width`<a href="Width-p" id="Width-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Width { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="PropertyChanged-p" id="PropertyChanged-p"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

