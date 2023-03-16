
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Binary](../../../TigerTrade.Core/Utils/Binary.md)


Описание

### Синтаксис
```csharp
public abstract class BinReader<T> : IDisposable
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BinReader`](#BinReader-m) | *Описание* |
| [`Dispose`](#Dispose-m) | *Описание* |
| [`Read`](#Read-m) | *Описание* |
| [`ReadBool`](#ReadBool-m) | *Описание* |
| [`ReadByte`](#ReadByte-m) | *Описание* |
| [`ReadDouble`](#ReadDouble-m) | *Описание* |
| [`ReadInt32`](#ReadInt32-m) | *Описание* |
| [`ReadItem`](#ReadItem-m) | *Описание* |
| [`ReadLeb128`](#ReadLeb128-m) | *Описание* |
| [`ReadLong`](#ReadLong-m) | *Описание* |
| [`ReadString`](#ReadString-m) | *Описание* |
| [`ReadStringAsBytes`](#ReadStringAsBytes-m) | *Описание* |
| [`ReadUInt16`](#ReadUInt16-m) | *Описание* |
| [`Reset`](#Reset-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsEmpty`](#IsEmpty-p) | *Описание* |
| [`LastItem`](#LastItem-p) | *Описание* |
| [`PrevItem`](#PrevItem-p) | *Описание* |





***  
***  
# Методы

## `BinReader`<a href="BinReader-m" id="BinReader-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected BinReader(byte[] data)
```

***  

## `Dispose`<a href="Dispose-m" id="Dispose-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Dispose()
```

***  

## `Read`<a href="Read-m" id="Read-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Read()
```

***  

## `ReadBool`<a href="ReadBool-m" id="ReadBool-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected bool ReadBool()
```

***  

## `ReadByte`<a href="ReadByte-m" id="ReadByte-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected byte ReadByte()
```

***  

## `ReadDouble`<a href="ReadDouble-m" id="ReadDouble-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double ReadDouble()
```

***  

## `ReadInt32`<a href="ReadInt32-m" id="ReadInt32-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected int ReadInt32()
```

***  

## `ReadItem`<a href="ReadItem-m" id="ReadItem-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract T ReadItem()
```

***  

## `ReadLeb128`<a href="ReadLeb128-m" id="ReadLeb128-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected long ReadLeb128()
```

***  

## `ReadLong`<a href="ReadLong-m" id="ReadLong-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected long ReadLong()
```

***  

## `ReadString`<a href="ReadString-m" id="ReadString-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected string ReadString()
```

***  

## `ReadStringAsBytes`<a href="ReadStringAsBytes-m" id="ReadStringAsBytes-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected byte[] ReadStringAsBytes()
```

***  

## `ReadUInt16`<a href="ReadUInt16-m" id="ReadUInt16-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected ushort ReadUInt16()
```

***  

## `Reset`<a href="Reset-m" id="Reset-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void Reset()
```

***  
***  
 ***  
# Свойства

## `IsEmpty`<a href="IsEmpty-p" id="IsEmpty-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsEmpty { get; }
```  
***

## `LastItem`<a href="LastItem-p" id="LastItem-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T LastItem { get; private set; }
```  
***

## `PrevItem`<a href="PrevItem-p" id="PrevItem-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T PrevItem { get; private set; }
```  
***

