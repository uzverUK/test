
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


===

### Синтаксис
```csharp
public sealed class UserPositionData
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ClearPosition`](#method-clearposition) | *===* |
| [`ClosePosition`](#method-closeposition) | *===* |
| [`HidePosition`](#method-hideposition) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsLive`](#property-islive) | *===* |
| [`IsPlayer`](#property-isplayer) | *===* |
| [`IsSimulator`](#property-issimulator) | *===* |





***  
***  
# Методы

## `ClearPosition`<a href="method-clearposition" id="method-clearposition"></a>
===
```csharp
public static UserPositionData ClearPosition(string connectionID, string positionID)
```

`connectionID` <mark style="color:red;">*`string`*</mark>  
 *===*  

`positionID` <mark style="color:red;">*`string`*</mark>  
 *===*  

`UserPositionData` <mark style="color:red;">*`new`*</mark>  
 *===*  


***  

## `ClosePosition`<a href="method-closeposition" id="method-closeposition"></a>
===
```csharp
public static UserPositionData ClosePosition(string connectionID, string positionID)
```

***  

## `HidePosition`<a href="method-hideposition" id="method-hideposition"></a>
===
```csharp
public static UserPositionData HidePosition(string connectionID, string positionID)
```

`connectionID` <mark style="color:red;">*`string`*</mark>  
 *===*  

`positionID` <mark style="color:red;">*`string`*</mark>  
 *===*  

`UserPositionData` <mark style="color:red;">*`new`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `IsLive`<a href="property-islive" id="property-islive"></a>
===
```csharp
public bool IsLive { get; }
```  
***

## `IsPlayer`<a href="property-isplayer" id="property-isplayer"></a>
===
```csharp
public bool IsPlayer { get; }
```  
***

## `IsSimulator`<a href="property-issimulator" id="property-issimulator"></a>
===
```csharp
public bool IsSimulator { get; }
```  
***

