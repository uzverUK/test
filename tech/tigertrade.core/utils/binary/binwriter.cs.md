# BinWriter

`namespace` [TigerTrade.Core](../../).[Utils](../).[Binary](./)

\===

#### Синтаксис

```csharp
public abstract class BinWriter
```

## Список методов

| Название                                                | Описание |
| ------------------------------------------------------- | -------- |
| [`BinWriter`](binwriter.cs.md#method-binwriter)         | _===_    |
| [`GetStreamData`](binwriter.cs.md#method-getstreamdata) | _===_    |
| [`Write`](binwriter.cs.md#method-write)                 | _===_    |
| [`WriteLeb128`](binwriter.cs.md#method-writeleb128)     | _===_    |

***

***

## Методы

### `BinWriter` <a href="#method-binwriter" id="method-binwriter"></a>

\===

```csharp
protected BinWriter()
```

***

### `GetStreamData` <a href="#method-getstreamdata" id="method-getstreamdata"></a>

\===

```csharp
protected byte[] GetStreamData()
```

`is` _<mark style="color:red;">`BaseStream`</mark>_\
_===_

`baseStream` _<mark style="color:red;">`MemoryStream`</mark>_\
_===_

***

### `Write` <a href="#method-write" id="method-write"></a>

\===

```csharp
protected void Write(bool value)
```

`value` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `Write` <a href="#method-write" id="method-write"></a>

\===

```csharp
protected void Write(bool value)
protected void Write(byte value)
```

`value` _<mark style="color:red;">`bool`</mark>_\
_===_

`value` _<mark style="color:red;">`byte`</mark>_\
_===_

***

### `Write` <a href="#method-write" id="method-write"></a>

\===

```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
```

`value` _<mark style="color:red;">`bool`</mark>_\
_===_

`value` _<mark style="color:red;">`byte`</mark>_\
_===_

`value` _<mark style="color:red;">`int`</mark>_\
_===_

***

### `Write` <a href="#method-write" id="method-write"></a>

\===

```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
protected void Write(long value)
```

`value` _<mark style="color:red;">`bool`</mark>_\
_===_

`value` _<mark style="color:red;">`byte`</mark>_\
_===_

`value` _<mark style="color:red;">`int`</mark>_\
_===_

`value` _<mark style="color:red;">`long`</mark>_\
_===_

***

### `Write` <a href="#method-write" id="method-write"></a>

\===

```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
protected void Write(long value)
protected void Write(double value)
```

`value` _<mark style="color:red;">`bool`</mark>_\
_===_

`value` _<mark style="color:red;">`byte`</mark>_\
_===_

`value` _<mark style="color:red;">`int`</mark>_\
_===_

`value` _<mark style="color:red;">`long`</mark>_\
_===_

`value` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `Write` <a href="#method-write" id="method-write"></a>

\===

```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
protected void Write(long value)
protected void Write(double value)
protected void Write(string value)
```

`value` _<mark style="color:red;">`bool`</mark>_\
_===_

`value` _<mark style="color:red;">`byte`</mark>_\
_===_

`value` _<mark style="color:red;">`int`</mark>_\
_===_

`value` _<mark style="color:red;">`long`</mark>_\
_===_

`value` _<mark style="color:red;">`double`</mark>_\
_===_

`value` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `WriteLeb128` <a href="#method-writeleb128" id="method-writeleb128"></a>

\===

```csharp
protected void WriteLeb128(long value)
```

***
