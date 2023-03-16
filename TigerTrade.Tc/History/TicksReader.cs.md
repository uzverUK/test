
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class TicksReader : BinReader<Tick>, IDataReader<Tick>
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ReadItem`](#method-readitem) | *Описание* |
| [`Reset`](#method-reset) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`PriceStep`](#property-pricestep) | *Описание* |
| [`SizeStep`](#property-sizestep) | *Описание* |
| [`Version`](#property-version) | *Описание* |





***  
***  
# Методы

## `ReadItem`<a href="method-readitem" id="method-readitem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override Tick ReadItem()
```

***  

## `Reset`<a href="method-reset" id="method-reset"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void Reset()
```

***  
***  
 ***  
# Свойства

## `PriceStep`<a href="property-pricestep" id="property-pricestep"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double PriceStep { get; private set; }
```  
***

## `SizeStep`<a href="property-sizestep" id="property-sizestep"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double SizeStep { get; private set; }
```  
***

## `Version`<a href="property-version" id="property-version"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Version { get; private set; }
```  
***

