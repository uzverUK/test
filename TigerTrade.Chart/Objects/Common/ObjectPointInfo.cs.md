
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Common](../../../TigerTrade.Chart/Objects/Common.md)


===

### Синтаксис
```csharp
public sealed class ObjectPointInfo : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ObjectPointInfo`](#method-objectpointinfo) | *===* |
| [`ToString`](#method-tostring) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Price`](#property-price) | *===* |
| [`Time`](#property-time) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *===* |





***  
***  
# Методы

## `ObjectPointInfo`<a href="method-objectpointinfo" id="method-objectpointinfo"></a>
===
```csharp
public ObjectPointInfo(ObjectPoint[] points, int index)
```

`index` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
===
```csharp
public override string ToString()
```

***  
***  
 ***  
# Свойства

## `Price`<a href="property-price" id="property-price"></a>
===
```csharp
public double Price { get; set; }
```  
***

## `Time`<a href="property-time" id="property-time"></a>
===
```csharp
public DateTime Time { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

