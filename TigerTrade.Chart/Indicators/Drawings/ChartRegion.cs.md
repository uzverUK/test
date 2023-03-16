
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


Описание

### Синтаксис
```csharp
public sealed class ChartRegion : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartRegion`](./ChartRegion.cs/Методы/ChartRegion.md) | *Описание* |
| [`CopyTheme`](./ChartRegion.cs/Методы/CopyTheme.md) | *Описание* |
| [`ToString`](./ChartRegion.cs/Методы/ToString.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Color`](./ChartRegion.cs/Свойства/Color.md) | *Описание* |
| [`Visible`](./ChartRegion.cs/Свойства/Visible.md) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ChartRegion.cs/События/PropertyChanged.md) | *Описание* |





***  
***  
# Методы

## `ChartRegion<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartRegion()
```

***  

## `ChartRegion<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartRegion()
public ChartRegion(XColor color)
```

`color` <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  


***  

## `CopyTheme<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CopyTheme(ChartRegion chartRegion)
```
`chartRegion` <mark style="color:red;">*`ChartRegion`*</mark>  
 *Описание*  


***  

## `ToString<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Color`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color { get; set; }
```  
***

## `Visible`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Visible { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

