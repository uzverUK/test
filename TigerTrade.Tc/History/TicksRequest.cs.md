
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


===

### Синтаксис
```csharp
public sealed class TicksRequest
```


# Список методов
| Название | Описание |
| --- | --- |
| [`TicksRequest`](#method-ticksrequest) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`CustomData`](#property-customdata) | *===* |
| [`RequestID`](#property-requestid) | *===* |
| [`Symbol`](#property-symbol) | *===* |
| [`TargetID`](#property-targetid) | *===* |





***  
***  
# Методы

## `TicksRequest`<a href="method-ticksrequest" id="method-ticksrequest"></a>
===
```csharp
public TicksRequest(Symbol symbol, string requestID, string targetID, bool customData)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  

`requestID` <mark style="color:red;">*`string`*</mark>  
 *===*  

`targetID` <mark style="color:red;">*`string`*</mark>  
 *===*  

`customData` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `CustomData`<a href="property-customdata" id="property-customdata"></a>
===
```csharp
public bool CustomData { get; set; }
```  
***

## `RequestID`<a href="property-requestid" id="property-requestid"></a>
===
```csharp
public string RequestID { get; set; }
```  
***

## `Symbol`<a href="property-symbol" id="property-symbol"></a>
===
```csharp
public Symbol Symbol { get; set; }
```  
***

## `TargetID`<a href="property-targetid" id="property-targetid"></a>
===
```csharp
public string TargetID { get; }
```  
***

