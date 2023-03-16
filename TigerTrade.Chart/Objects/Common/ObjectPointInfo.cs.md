
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public sealed class ObjectPointInfo : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ObjectPointInfo`](#test) | *Описание* |
| [`ToString`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Price`](./ObjectPointInfo.cs/Свойства/Price.md) | *Описание* |
| [`Time`](./ObjectPointInfo.cs/Свойства/Time.md) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ObjectPointInfo.cs/События/PropertyChanged.md) | *Описание* |





***  
***  
# Методы

## `ObjectPointInfo`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPointInfo(ObjectPoint[] points, int index)
```

`index` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `ToString`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Price`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double Price { get; set; }
```  
***

## `Time`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime Time { get; set; }
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

