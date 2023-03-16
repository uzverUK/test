
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public sealed class ObjectPointInfo : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ObjectPointInfo`](#ObjectPointInfo-m) | *Описание* |
| [`ToString`](#ToString-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Price`](#Price-p) | *Описание* |
| [`Time`](#Time-p) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#PropertyChanged-p) | *Описание* |





***  
***  
# Методы

## `ObjectPointInfo`<a href="ObjectPointInfo-m" id="ObjectPointInfo-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPointInfo(ObjectPoint[] points, int index)
```

`index` <mark style="color:red;">*`int`*</mark>  
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

## `Price`<a href="Price-p" id="Price-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Price { get; set; }
```  
***

## `Time`<a href="Time-p" id="Time-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; set; }
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

