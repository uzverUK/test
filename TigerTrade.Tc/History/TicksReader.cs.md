
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[History](../../TigerTrade.Tc/History.md)


Описание

### Синтаксис
```csharp
public sealed class TicksReader : BinReader<Tick>, IDataReader<Tick>
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ReadItem`](#ReadItem-m) | *Описание* |
| [`Reset`](#Reset-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`PriceStep`](#PriceStep-p) | *Описание* |
| [`SizeStep`](#SizeStep-p) | *Описание* |
| [`Version`](#Version-p) | *Описание* |





***  
***  
# Методы

## `ReadItem`<a href="ReadItem-m" id="ReadItem-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override Tick ReadItem()
```

***  

## `Reset`<a href="Reset-m" id="Reset-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void Reset()
```

***  
***  
 ***  
# Свойства

## `PriceStep`<a href="PriceStep-p" id="PriceStep-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double PriceStep { get; private set; }
```  
***

## `SizeStep`<a href="SizeStep-p" id="SizeStep-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double SizeStep { get; private set; }
```  
***

## `Version`<a href="Version-p" id="Version-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Version { get; private set; }
```  
***

