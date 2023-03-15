
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


Описание

### Синтаксис
```csharp
public sealed class ObjectPointInfo : INotifyPropertyChanged
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ObjectPointInfo`](./ObjectPointInfo.cs/Методы/ObjectPointInfo.md) | *Описание* |
| [`ToString`](./ObjectPointInfo.cs/Методы/ToString.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Price`](./ObjectPointInfo.cs/Свойства/Price.md) | *Описание* |
| [`Time`](./ObjectPointInfo.cs/Свойства/Time.md) | *Описание* |

# Таблица событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ObjectPointInfo.cs/События/PropertyChanged.md) | *Описание* |





***  
***  
# Методы

## *ObjectPointInfo*
Описание

```csharp
public ObjectPointInfo(ObjectPoint[] points, int index)
```

<mark style="color:yellow;">`index`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## *ToString*
Описание

```csharp
public override string ToString()
```

***                
***
  ***
  # Свойства

## *Price*
Описание

```csharp
public double Price { get; set; }
```
***

## *Time*
Описание

```csharp
public DateTime Time { get; set; }
```
***
***
  ***
  # События

## *PropertyChanged*
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```
***

