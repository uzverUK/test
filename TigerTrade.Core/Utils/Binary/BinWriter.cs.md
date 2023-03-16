
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[Utils](../../../TigerTrade.Core/Utils.md).[Binary](../../../TigerTrade.Core/Utils/Binary.md)


===

### Синтаксис
```csharp
public abstract class BinWriter
```


# Список методов
| Название | Описание |
| --- | --- |
| [`BinWriter`](#method-binwriter) | *===* |
| [`GetStreamData`](#method-getstreamdata) | *===* |
| [`Write`](#method-write) | *===* |
| [`WriteLeb128`](#method-writeleb128) | *===* |





***  
***  
# Методы

## `BinWriter`<a href="method-binwriter" id="method-binwriter"></a>
===
```csharp
protected BinWriter()
```

***  

## `GetStreamData`<a href="method-getstreamdata" id="method-getstreamdata"></a>
===
```csharp
protected byte[] GetStreamData()
```

`is` <mark style="color:red;">*`BaseStream`*</mark>  
 *===*  

`baseStream` <mark style="color:red;">*`MemoryStream`*</mark>  
 *===*  


***  

## `Write`<a href="method-write" id="method-write"></a>
===
```csharp
protected void Write(bool value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `Write`<a href="method-write" id="method-write"></a>
===
```csharp
protected void Write(bool value)
protected void Write(byte value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`value` <mark style="color:red;">*`byte`*</mark>  
 *===*  


***  

## `Write`<a href="method-write" id="method-write"></a>
===
```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`value` <mark style="color:red;">*`byte`*</mark>  
 *===*  

`value` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `Write`<a href="method-write" id="method-write"></a>
===
```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
protected void Write(long value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`value` <mark style="color:red;">*`byte`*</mark>  
 *===*  

`value` <mark style="color:red;">*`int`*</mark>  
 *===*  

`value` <mark style="color:red;">*`long`*</mark>  
 *===*  


***  

## `Write`<a href="method-write" id="method-write"></a>
===
```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
protected void Write(long value)
protected void Write(double value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`value` <mark style="color:red;">*`byte`*</mark>  
 *===*  

`value` <mark style="color:red;">*`int`*</mark>  
 *===*  

`value` <mark style="color:red;">*`long`*</mark>  
 *===*  

`value` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `Write`<a href="method-write" id="method-write"></a>
===
```csharp
protected void Write(bool value)
protected void Write(byte value)
protected void Write(int value)
protected void Write(long value)
protected void Write(double value)
protected void Write(string value)
```
`value` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`value` <mark style="color:red;">*`byte`*</mark>  
 *===*  

`value` <mark style="color:red;">*`int`*</mark>  
 *===*  

`value` <mark style="color:red;">*`long`*</mark>  
 *===*  

`value` <mark style="color:red;">*`double`*</mark>  
 *===*  

`value` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `WriteLeb128`<a href="method-writeleb128" id="method-writeleb128"></a>
===
```csharp
protected void WriteLeb128(long value)
```

***  

