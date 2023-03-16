
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class PolygonObjectBase : ObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#ApplyTheme-m) | *Описание* |
| [`CopyTemplate`](#CopyTemplate-m) | *Описание* |
| [`PolygonObjectBase`](#PolygonObjectBase-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`BackBrush`](#BackBrush-p) | *Описание* |
| [`BackColor`](#BackColor-p) | *Описание* |
| [`DrawBack`](#DrawBack-p) | *Описание* |
| [`DrawBorder`](#DrawBorder-p) | *Описание* |
| [`LineBrush`](#LineBrush-p) | *Описание* |
| [`LineColor`](#LineColor-p) | *Описание* |
| [`LinePen`](#LinePen-p) | *Описание* |
| [`LineStyle`](#LineStyle-p) | *Описание* |
| [`LineWidth`](#LineWidth-p) | *Описание* |
| [`int`](#int-p) | *Описание* |





***  
***  
# Методы

## `ApplyTheme`<a href="PolygonObjectBase-m" id="PolygonObjectBase-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `CopyTemplate`<a href="PolygonObjectBase-m" id="PolygonObjectBase-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `PolygonObjectBase`<a href="PolygonObjectBase-m" id="PolygonObjectBase-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected PolygonObjectBase()
```

***  
***  
 ***  
# Свойства

## `BackBrush`<a href="int-p" id="int-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XBrush BackBrush { get; private set; }
```  
***

## `BackColor`<a href="int-p" id="int-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor BackColor { get; set; }
```  
***

## `DrawBack`<a href="int-p" id="int-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool DrawBack { get; set; }
```  
***

## `DrawBorder`<a href="int-p" id="int-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool DrawBorder { get; set; }
```  
***

## `LineBrush`<a href="int-p" id="int-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XBrush LineBrush { get; private set; }
```  
***

## `LineColor`<a href="int-p" id="int-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor LineColor { get; set; }
```  
***

## `LinePen`<a href="int-p" id="int-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XPen LinePen { get; private set; }
```  
***

## `LineStyle`<a href="int-p" id="int-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle LineStyle { get; set; }
```  
***

## `LineWidth`<a href="int-p" id="int-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LineWidth { get; set; }
```  
***

## `int`<a href="int-p" id="int-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override int PenWidth { get; }
```  
***

