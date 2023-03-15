
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Indicators](../../../TigerTrade.Chart/Indicators.md).[Drawings](../../../TigerTrade.Chart/Indicators/Drawings.md)


Описание

### Синтаксис
```csharp
public sealed class ChartRegion : INotifyPropertyChanged
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ChartRegion`](./ChartRegion.cs/Методы/ChartRegion.md) | *Описание* |
| [`CopyTheme`](./ChartRegion.cs/Методы/CopyTheme.md) | *Описание* |
| [`ToString`](./ChartRegion.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Color`](./ChartRegion.cs/Свойства/Color.md) | *Описание* |
| [`Visible`](./ChartRegion.cs/Свойства/Visible.md) | *Описание* |

# Таблица событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ChartRegion.cs/События/PropertyChanged.md) | *Описание* |





# Методы

## `ChartRegion`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartRegion()
```


## `ChartRegion`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartRegion()
public ChartRegion(XColor color)
```

<mark style="color:purple;">`color`</mark> <mark style="color:red;">*`XColor`*</mark>  
 *Описание*  



## `CopyTheme`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void CopyTheme(ChartRegion chartRegion)
```
<mark style="color:purple;">`chartRegion`</mark> <mark style="color:red;">*`ChartRegion`*</mark>  
 *Описание*  



## `ToString`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

# Свойства

## `Color`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color { get; set; }
```

## `Visible`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Visible { get; set; }
```
# События

## `PropertyChanged`
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

