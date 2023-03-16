# BinReader1

`namespace` [TigerTrade.Core](../../).[Utils](../).[Binary](./)

\===

#### Синтаксис

```csharp
public abstract class BinReader<T> : IDisposable
```

## Список методов

| Название                                                         | Описание |
| ---------------------------------------------------------------- | -------- |
| [`BinReader`](binreader1.cs.md#method-binreader)                 | _===_    |
| [`Dispose`](binreader1.cs.md#method-dispose)                     | _===_    |
| [`Read`](binreader1.cs.md#method-read)                           | _===_    |
| [`ReadBool`](binreader1.cs.md#method-readbool)                   | _===_    |
| [`ReadByte`](binreader1.cs.md#method-readbyte)                   | _===_    |
| [`ReadDouble`](binreader1.cs.md#method-readdouble)               | _===_    |
| [`ReadInt32`](binreader1.cs.md#method-readint32)                 | _===_    |
| [`ReadItem`](binreader1.cs.md#method-readitem)                   | _===_    |
| [`ReadLeb128`](binreader1.cs.md#method-readleb128)               | _===_    |
| [`ReadLong`](binreader1.cs.md#method-readlong)                   | _===_    |
| [`ReadString`](binreader1.cs.md#method-readstring)               | _===_    |
| [`ReadStringAsBytes`](binreader1.cs.md#method-readstringasbytes) | _===_    |
| [`ReadUInt16`](binreader1.cs.md#method-readuint16)               | _===_    |
| [`Reset`](binreader1.cs.md#method-reset)                         | _===_    |

## Список свойств

| Название                                         | Описание |
| ------------------------------------------------ | -------- |
| [`IsEmpty`](binreader1.cs.md#property-isempty)   | _===_    |
| [`LastItem`](binreader1.cs.md#property-lastitem) | _===_    |
| [`PrevItem`](binreader1.cs.md#property-previtem) | _===_    |

***

***

## Методы

### `BinReader` <a href="#method-binreader" id="method-binreader"></a>

\===

```csharp
protected BinReader(byte[] data)
```

***

### `Dispose` <a href="#method-dispose" id="method-dispose"></a>

\===

```csharp
public void Dispose()
```

***

### `Read` <a href="#method-read" id="method-read"></a>

\===

```csharp
public bool Read()
```

***

### `ReadBool` <a href="#method-readbool" id="method-readbool"></a>

\===

```csharp
protected bool ReadBool()
```

***

### `ReadByte` <a href="#method-readbyte" id="method-readbyte"></a>

\===

```csharp
protected byte ReadByte()
```

***

### `ReadDouble` <a href="#method-readdouble" id="method-readdouble"></a>

\===

```csharp
protected double ReadDouble()
```

***

### `ReadInt32` <a href="#method-readint32" id="method-readint32"></a>

\===

```csharp
protected int ReadInt32()
```

***

### `ReadItem` <a href="#method-readitem" id="method-readitem"></a>

\===

```csharp
protected abstract T ReadItem()
```

***

### `ReadLeb128` <a href="#method-readleb128" id="method-readleb128"></a>

\===

```csharp
protected long ReadLeb128()
```

***

### `ReadLong` <a href="#method-readlong" id="method-readlong"></a>

\===

```csharp
protected long ReadLong()
```

***

### `ReadString` <a href="#method-readstring" id="method-readstring"></a>

\===

```csharp
protected string ReadString()
```

***

### `ReadStringAsBytes` <a href="#method-readstringasbytes" id="method-readstringasbytes"></a>

\===

```csharp
protected byte[] ReadStringAsBytes()
```

***

### `ReadUInt16` <a href="#method-readuint16" id="method-readuint16"></a>

\===

```csharp
protected ushort ReadUInt16()
```

***

### `Reset` <a href="#method-reset" id="method-reset"></a>

\===

```csharp
public virtual void Reset()
```

***

***

***

## Свойства

### `IsEmpty` <a href="#property-isempty" id="property-isempty"></a>

\===

```csharp
public bool IsEmpty { get; }
```

***

### `LastItem` <a href="#property-lastitem" id="property-lastitem"></a>

\===

```csharp
public T LastItem { get; private set; }
```

***

### `PrevItem` <a href="#property-previtem" id="property-previtem"></a>

\===

```csharp
public T PrevItem { get; private set; }
```

***
