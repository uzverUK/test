
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


Описание

### Синтаксис
```csharp
public sealed class ChartLine : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartLine`](#ChartLine-m) | *Описание* |
| [`CopyTheme`](#CopyTheme-m) | *Описание* |
| [`ToString`](#ToString-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Color`](#Color-p) | *Описание* |
| [`ShowMarker`](#ShowMarker-p) | *Описание* |
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

## `ChartLine`<a href="ChartLine-m" id="ChartLine-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartLine()
```

***  

## `CopyTheme`<a href="CopyTheme-m" id="CopyTheme-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CopyTheme(ChartLine chartLine)
```

`chartLine` <mark style="color:red;">*`ChartLine`*</mark>  
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

## `ShowMarker`<a href="ShowMarker-p" id="ShowMarker-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowMarker { get; set; }
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

