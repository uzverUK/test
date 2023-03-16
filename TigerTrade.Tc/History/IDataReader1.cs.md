
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public interface IDataReader<out T>
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Dispose`](#method-dispose) | *Описание* |
| [`Read`](#method-read) | *Описание* |
| [`Reset`](#method-reset) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsEmpty`](#property-isempty) | *Описание* |
| [`LastItem`](#property-lastitem) | *Описание* |
| [`PrevItem`](#property-previtem) | *Описание* |





***  
***  
# Методы

## `Dispose`<a href="method-dispose" id="method-dispose"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
void Dispose()
```

***  

## `Read`<a href="method-read" id="method-read"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
bool Read()
```

***  

## `Reset`<a href="method-reset" id="method-reset"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
void Reset()
```

***  
***  
 ***  
# Свойства

## `IsEmpty`<a href="property-isempty" id="property-isempty"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
bool IsEmpty { get; }
```  
***

## `LastItem`<a href="property-lastitem" id="property-lastitem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
T LastItem { get; }
```  
***

## `PrevItem`<a href="property-previtem" id="property-previtem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
T PrevItem { get; }
```  
***

