
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Binary](../../../TigerTrade.Core/Utils/Binary.md)


Описание

### Синтаксис
```csharp
public abstract class BinReader<T> : IDisposable
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BinReader`](#method-binreader) | *Описание* |
| [`Dispose`](#method-dispose) | *Описание* |
| [`Read`](#method-read) | *Описание* |
| [`ReadBool`](#method-readbool) | *Описание* |
| [`ReadByte`](#method-readbyte) | *Описание* |
| [`ReadDouble`](#method-readdouble) | *Описание* |
| [`ReadInt32`](#method-readint32) | *Описание* |
| [`ReadItem`](#method-readitem) | *Описание* |
| [`ReadLeb128`](#method-readleb128) | *Описание* |
| [`ReadLong`](#method-readlong) | *Описание* |
| [`ReadString`](#method-readstring) | *Описание* |
| [`ReadStringAsBytes`](#method-readstringasbytes) | *Описание* |
| [`ReadUInt16`](#method-readuint16) | *Описание* |
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

## `BinReader`<a href="method-binreader" id="method-binreader"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected BinReader(byte[] data)
```

***  

## `Dispose`<a href="method-dispose" id="method-dispose"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Dispose()
```

***  

## `Read`<a href="method-read" id="method-read"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Read()
```

***  

## `ReadBool`<a href="method-readbool" id="method-readbool"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected bool ReadBool()
```

***  

## `ReadByte`<a href="method-readbyte" id="method-readbyte"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected byte ReadByte()
```

***  

## `ReadDouble`<a href="method-readdouble" id="method-readdouble"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected double ReadDouble()
```

***  

## `ReadInt32`<a href="method-readint32" id="method-readint32"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected int ReadInt32()
```

***  

## `ReadItem`<a href="method-readitem" id="method-readitem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract T ReadItem()
```

***  

## `ReadLeb128`<a href="method-readleb128" id="method-readleb128"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected long ReadLeb128()
```

***  

## `ReadLong`<a href="method-readlong" id="method-readlong"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected long ReadLong()
```

***  

## `ReadString`<a href="method-readstring" id="method-readstring"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected string ReadString()
```

***  

## `ReadStringAsBytes`<a href="method-readstringasbytes" id="method-readstringasbytes"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected byte[] ReadStringAsBytes()
```

***  

## `ReadUInt16`<a href="method-readuint16" id="method-readuint16"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected ushort ReadUInt16()
```

***  

## `Reset`<a href="method-reset" id="method-reset"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public virtual void Reset()
```

***  
***  
 ***  
# Свойства

## `IsEmpty`<a href="property-isempty" id="property-isempty"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsEmpty { get; }
```  
***

## `LastItem`<a href="property-lastitem" id="property-lastitem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T LastItem { get; private set; }
```  
***

## `PrevItem`<a href="property-previtem" id="property-previtem"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public T PrevItem { get; private set; }
```  
***

