
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class TicksReader : BinReader<Tick>, IDataReader<Tick>
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ReadItem`](#test) | *Описание* |
| [`Reset`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`PriceStep`](./TicksReader.cs/Свойства/PriceStep.md) | *Описание* |
| [`SizeStep`](./TicksReader.cs/Свойства/SizeStep.md) | *Описание* |
| [`Version`](./TicksReader.cs/Свойства/Version.md) | *Описание* |





***  
***  
# Методы

## `ReadItem`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override Tick ReadItem()
```

***  

## `Reset`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void Reset()
```

***  
***  
 ***  
# Свойства

## `PriceStep`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double PriceStep { get; private set; }
```  
***

## `SizeStep`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double SizeStep { get; private set; }
```  
***

## `Version`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Version { get; private set; }
```  
***

