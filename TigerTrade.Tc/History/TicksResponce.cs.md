
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


===

### Синтаксис
```csharp
public sealed class TicksResponce
```


# Список методов
| Название | Описание |
| --- | --- |
| [`TicksResponce`](#method-ticksresponce) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Reader`](#property-reader) | *===* |
| [`Request`](#property-request) | *===* |





***  
***  
# Методы

## `TicksResponce`<a href="method-ticksresponce" id="method-ticksresponce"></a>
===
```csharp
public TicksResponce(TicksRequest request, IDataReader<Tick> reader)
```

`request` <mark style="color:red;">*`TicksRequest`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Reader`<a href="property-reader" id="property-reader"></a>
===
```csharp
public IDataReader<Tick> Reader { get; }
```  
***

## `Request`<a href="property-request" id="property-request"></a>
===
```csharp
public TicksRequest Request { get; }
```  
***

