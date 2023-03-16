
`namespace` [TigerTrade.Dx](../TigerTrade.Dx.md)


Описание

### Синтаксис
```csharp
public sealed class XFont
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetFont`](#method-getfont) | *Описание* |
| [`GetFontName`](#method-getfontname) | *Описание* |
| [`GetHeight`](#method-getheight) | *Описание* |
| [`GetWidth`](#method-getwidth) | *Описание* |
| [`ToString`](#method-tostring) | *Описание* |
| [`XFont`](#method-xfont) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Bold`](#property-bold) | *Описание* |
| [`Fonts;`](#property-fonts;) | *Описание* |
| [`Name`](#property-name) | *Описание* |
| [`Size`](#property-size) | *Описание* |
| [`UniquID`](#property-uniquid) | *Описание* |





***  
***  
# Методы

## `GetFont`<a href="method-getfont" id="method-getfont"></a>
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

## `GetFontName`<a href="method-getfontname" id="method-getfontname"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static string GetFontName(FontFamily fontFamily)
```
`fontFamily` <mark style="color:red;">*`FontFamily`*</mark>  
 *Описание*  


***  

## `GetHeight`<a href="method-getheight" id="method-getheight"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetHeight()
```

***  

## `GetWidth`<a href="method-getwidth" id="method-getwidth"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public double GetWidth(string text)
```

`text` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override string ToString()
```

***  

## `XFont`<a href="method-xfont" id="method-xfont"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XFont()
```

***  

## `XFont`<a href="method-xfont" id="method-xfont"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XFont()
public XFont(bool bold)
```

`bold` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `XFont`<a href="method-xfont" id="method-xfont"></a>
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

## `XFont`<a href="method-xfont" id="method-xfont"></a>
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

## `Bold`<a href="property-bold" id="property-bold"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Bold { get; }
```  
***

## `Fonts;`<a href="property-fonts;" id="property-fonts;"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<string> Fonts; {}
```  
***

## `Name`<a href="property-name" id="property-name"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Name { get; }
```  
***

## `Size`<a href="property-size" id="property-size"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Size { get; }
```  
***

## `UniquID`<a href="property-uniquid" id="property-uniquid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string UniquID { get; }
```  
***

