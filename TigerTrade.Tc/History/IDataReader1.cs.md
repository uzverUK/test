
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


===

### Синтаксис
```csharp
public interface IDataReader<out T>
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Dispose`](#method-dispose) | *===* |
| [`Read`](#method-read) | *===* |
| [`Reset`](#method-reset) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsEmpty`](#property-isempty) | *===* |
| [`LastItem`](#property-lastitem) | *===* |
| [`PrevItem`](#property-previtem) | *===* |





***  
***  
# Методы

## `Dispose`<a href="method-dispose" id="method-dispose"></a>
===
```csharp
void Dispose()
```

***  

## `Read`<a href="method-read" id="method-read"></a>
===
```csharp
bool Read()
```

***  

## `Reset`<a href="method-reset" id="method-reset"></a>
===
```csharp
void Reset()
```

***  
***  
 ***  
# Свойства

## `IsEmpty`<a href="property-isempty" id="property-isempty"></a>
===
```csharp
bool IsEmpty { get; }
```  
***

## `LastItem`<a href="property-lastitem" id="property-lastitem"></a>
===
```csharp
T LastItem { get; }
```  
***

## `PrevItem`<a href="property-previtem" id="property-previtem"></a>
===
```csharp
T PrevItem { get; }
```  
***

