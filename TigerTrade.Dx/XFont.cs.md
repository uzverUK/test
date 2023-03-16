
`namespace` [TigerTrade.Dx](../TigerTrade.Dx.md)


Описание

### Синтаксис
```csharp
public sealed class XFont
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetFont`](./XFont.cs/Методы/GetFont.md) | *Описание* |
| [`GetFontName`](./XFont.cs/Методы/GetFontName.md) | *Описание* |
| [`GetHeight`](./XFont.cs/Методы/GetHeight.md) | *Описание* |
| [`GetWidth`](./XFont.cs/Методы/GetWidth.md) | *Описание* |
| [`ToString`](./XFont.cs/Методы/ToString.md) | *Описание* |
| [`XFont`](./XFont.cs/Методы/XFont.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Bold`](./XFont.cs/Свойства/Bold.md) | *Описание* |
| [`Fonts;`](./XFont.cs/Свойства/Fonts;.md) | *Описание* |
| [`Name`](./XFont.cs/Свойства/Name.md) | *Описание* |
| [`Size`](./XFont.cs/Свойства/Size.md) | *Описание* |
| [`UniquID`](./XFont.cs/Свойства/UniquID.md) | *Описание* |





***  
***  
# Методы

## `GetFont`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static FontFamily GetFont(string fontName)
```

`fontName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`FontFamily` <mark style="color:red;">*`new`*</mark>  
 *Описание*  

`Uri` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `GetFontName`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string GetFontName(FontFamily fontFamily)
```
`fontFamily` <mark style="color:red;">*`FontFamily`*</mark>  
 *Описание*  


***  

## `GetHeight`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetHeight()
```

***  

## `GetWidth`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetWidth(string text)
```

`text` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ToString`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  

## `XFont`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XFont()
```

***  

## `XFont`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XFont()
public XFont(bool bold)
```

`bold` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `XFont`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XFont()
public XFont(bool bold)
public XFont(string fontName, double size)
```

`bold` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`fontName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`size` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  

## `XFont`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XFont()
public XFont(bool bold)
public XFont(string fontName, double size)
public XFont(string fontName, double size, bool bold)
```

`bold` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`fontName` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`size` <mark style="color:red;">*`double`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Bold`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Bold { get; }
```  
***

## `Fonts;`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<string> Fonts; {}
```  
***

## `Name`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `Size`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Size { get; }
```  
***

## `UniquID`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string UniquID { get; }
```  
***

