# XFont

`namespace` [TigerTrade.Dx](./)

\===

#### Синтаксис

```csharp
public sealed class XFont
```

## Список методов

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`GetFont`](xfont.cs.md#method-getfont)         | _===_    |
| [`GetFontName`](xfont.cs.md#method-getfontname) | _===_    |
| [`GetHeight`](xfont.cs.md#method-getheight)     | _===_    |
| [`GetWidth`](xfont.cs.md#method-getwidth)       | _===_    |
| [`ToString`](xfont.cs.md#method-tostring)       | _===_    |
| [`XFont`](xfont.cs.md#method-xfont)             | _===_    |

## Список свойств

| Название                                  | Описание |
| ----------------------------------------- | -------- |
| [`Bold`](xfont.cs.md#property-bold)       | _===_    |
| [`Fonts;`](xfont.cs.md#property-fonts;)   | _===_    |
| [`Name`](xfont.cs.md#property-name)       | _===_    |
| [`Size`](xfont.cs.md#property-size)       | _===_    |
| [`UniquID`](xfont.cs.md#property-uniquid) | _===_    |

***

***

## Методы

### `GetFont` <a href="#method-getfont" id="method-getfont"></a>

\===

```csharp
public static FontFamily GetFont(string fontName)
```

`fontName` _<mark style="color:red;">`string`</mark>_\
_===_

`FontFamily` _<mark style="color:red;">`new`</mark>_\
_===_

`Uri` _<mark style="color:red;">`new`</mark>_\
_===_

***

### `GetFontName` <a href="#method-getfontname" id="method-getfontname"></a>

\===

```csharp
public static string GetFontName(FontFamily fontFamily)
```

`fontFamily` _<mark style="color:red;">`FontFamily`</mark>_\
_===_

***

### `GetHeight` <a href="#method-getheight" id="method-getheight"></a>

\===

```csharp
public double GetHeight()
```

***

### `GetWidth` <a href="#method-getwidth" id="method-getwidth"></a>

\===

```csharp
public double GetWidth(string text)
```

`text` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `ToString` <a href="#method-tostring" id="method-tostring"></a>

\===

```csharp
public override string ToString()
```

***

### `XFont` <a href="#method-xfont" id="method-xfont"></a>

\===

```csharp
public XFont()
```

***

### `XFont` <a href="#method-xfont" id="method-xfont"></a>

\===

```csharp
public XFont()
public XFont(bool bold)
```

`bold` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `XFont` <a href="#method-xfont" id="method-xfont"></a>

\===

```csharp
public XFont()
public XFont(bool bold)
public XFont(string fontName, double size)
```

`bold` _<mark style="color:red;">`bool`</mark>_\
_===_

`fontName` _<mark style="color:red;">`string`</mark>_\
_===_

`size` _<mark style="color:red;">`double`</mark>_\
_===_

***

### `XFont` <a href="#method-xfont" id="method-xfont"></a>

\===

```csharp
public XFont()
public XFont(bool bold)
public XFont(string fontName, double size)
public XFont(string fontName, double size, bool bold)
```

`bold` _<mark style="color:red;">`bool`</mark>_\
_===_

`fontName` _<mark style="color:red;">`string`</mark>_\
_===_

`size` _<mark style="color:red;">`double`</mark>_\
_===_

***

***

***

## Свойства

### `Bold` <a href="#property-bold" id="property-bold"></a>

\===

```csharp
public bool Bold { get; }
```

***

### `Fonts;` <a href="#property-fonts" id="property-fonts"></a>

\===

```csharp
public static List<string> Fonts; {}
```

***

### `Name` <a href="#property-name" id="property-name"></a>

\===

```csharp
public string Name { get; }
```

***

### `Size` <a href="#property-size" id="property-size"></a>

\===

```csharp
public int Size { get; }
```

***

### `UniquID` <a href="#property-uniquid" id="property-uniquid"></a>

\===

```csharp
public string UniquID { get; }
```

***
