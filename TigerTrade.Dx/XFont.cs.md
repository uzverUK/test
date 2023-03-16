
`namespace` [TigerTrade.Dx](../TigerTrade.Dx.md)


===

### Синтаксис
```csharp
public sealed class XFont
```


# Список методов
| Название | Описание |
| --- | --- |
| [`GetFont`](#method-getfont) | *===* |
| [`GetFontName`](#method-getfontname) | *===* |
| [`GetHeight`](#method-getheight) | *===* |
| [`GetWidth`](#method-getwidth) | *===* |
| [`ToString`](#method-tostring) | *===* |
| [`XFont`](#method-xfont) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Bold`](#property-bold) | *===* |
| [`Fonts;`](#property-fonts;) | *===* |
| [`Name`](#property-name) | *===* |
| [`Size`](#property-size) | *===* |
| [`UniquID`](#property-uniquid) | *===* |





***  
***  
# Методы

## `GetFont`<a href="method-getfont" id="method-getfont"></a>
===
```csharp
public static FontFamily GetFont(string fontName)
```

`fontName` <mark style="color:red;">*`string`*</mark>  
 *===*  

`FontFamily` <mark style="color:red;">*`new`*</mark>  
 *===*  

`Uri` <mark style="color:red;">*`new`*</mark>  
 *===*  


***  

## `GetFontName`<a href="method-getfontname" id="method-getfontname"></a>
===
```csharp
public static string GetFontName(FontFamily fontFamily)
```
`fontFamily` <mark style="color:red;">*`FontFamily`*</mark>  
 *===*  


***  

## `GetHeight`<a href="method-getheight" id="method-getheight"></a>
===
```csharp
public double GetHeight()
```

***  

## `GetWidth`<a href="method-getwidth" id="method-getwidth"></a>
===
```csharp
public double GetWidth(string text)
```

`text` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `ToString`<a href="method-tostring" id="method-tostring"></a>
===
```csharp
public override string ToString()
```

***  

## `XFont`<a href="method-xfont" id="method-xfont"></a>
===
```csharp
public XFont()
```

***  

## `XFont`<a href="method-xfont" id="method-xfont"></a>
===
```csharp
public XFont()
public XFont(bool bold)
```

`bold` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `XFont`<a href="method-xfont" id="method-xfont"></a>
===
```csharp
public XFont()
public XFont(bool bold)
public XFont(string fontName, double size)
```

`bold` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`fontName` <mark style="color:red;">*`string`*</mark>  
 *===*  

`size` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  

## `XFont`<a href="method-xfont" id="method-xfont"></a>
===
```csharp
public XFont()
public XFont(bool bold)
public XFont(string fontName, double size)
public XFont(string fontName, double size, bool bold)
```

`bold` <mark style="color:red;">*`bool`*</mark>  
 *===*  

`fontName` <mark style="color:red;">*`string`*</mark>  
 *===*  

`size` <mark style="color:red;">*`double`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Bold`<a href="property-bold" id="property-bold"></a>
===
```csharp
public bool Bold { get; }
```  
***

## `Fonts;`<a href="property-fonts;" id="property-fonts;"></a>
===
```csharp
public static List<string> Fonts; {}
```  
***

## `Name`<a href="property-name" id="property-name"></a>
===
```csharp
public string Name { get; }
```  
***

## `Size`<a href="property-size" id="property-size"></a>
===
```csharp
public int Size { get; }
```  
***

## `UniquID`<a href="property-uniquid" id="property-uniquid"></a>
===
```csharp
public string UniquID { get; }
```  
***

