
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Binary](../../../TigerTrade.Core/Utils/Binary.md)


Описание

### Синтаксис
```csharp
public abstract class BinWriter
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BinWriter`](#method-binwriter) | *Описание* |
| [`GetStreamData`](#method-getstreamdata) | *Описание* |
| [`Write`](#method-write) | *Описание* |
| [`WriteLeb128`](#method-writeleb128) | *Описание* |





***  
***  
# Методы

## `BinWriter`<a href="method-binwriter" id="method-binwriter"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected BinWriter()
```

***  

## `GetStreamData`<a href="method-getstreamdata" id="method-getstreamdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected byte[] GetStreamData()
```

`is` <mark style="color:red;">*`BaseStream`*</mark>  
 *Описание*  

`baseStream` <mark style="color:red;">*`MemoryStream`*</mark>  
 *Описание*  


***  

## `Write`<a href="method-write" id="method-write"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void Write(bool value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Write`<a href="method-write" id="method-write"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void Write(bool value)
protected void Write(byte value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`byte`*</mark>  
 *Описание*  


***  

## `Write`<a href="method-write" id="method-write"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`byte`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `Write`<a href="method-write" id="method-write"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
protected void Write(long value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`byte`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`long`*</mark>  
 *Описание*  


***  

## `Write`<a href="method-write" id="method-write"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
protected void Write(long value)
protected void Write(double value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`byte`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `Write`<a href="method-write" id="method-write"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
protected void Write(long value)
protected void Write(double value)
protected void Write(string value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`byte`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`long`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`double`*</mark>  
 *Описание*  

`value` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `WriteLeb128`<a href="method-writeleb128" id="method-writeleb128"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void WriteLeb128(long value)
```

***  

