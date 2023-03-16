
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


===

### Синтаксис
```csharp
public sealed class BarsResponce
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BarsResponce`](#method-barsresponce) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Reader`](#property-reader) | *===* |
| [`Request`](#property-request) | *===* |





***  
***  
# Методы

## `BarsResponce`<a href="method-barsresponce" id="method-barsresponce"></a>
===
```csharp
public BarsResponce(BarsRequest request, IDataReader<Bar> reader)
```

`request` <mark style="color:red;">*`BarsRequest`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Reader`<a href="property-reader" id="property-reader"></a>
===
```csharp
public IDataReader<Bar> Reader { get; }
```  
***

## `Request`<a href="property-request" id="property-request"></a>
===
```csharp
public BarsRequest Request { get; }
```  
***

