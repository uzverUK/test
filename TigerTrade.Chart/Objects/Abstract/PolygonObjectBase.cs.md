
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class PolygonObjectBase : ObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#method-applytheme) | *Описание* |
| [`CopyTemplate`](#method-copytemplate) | *Описание* |
| [`PolygonObjectBase`](#method-polygonobjectbase) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`BackBrush`](#property-backbrush) | *Описание* |
| [`BackColor`](#property-backcolor) | *Описание* |
| [`DrawBack`](#property-drawback) | *Описание* |
| [`DrawBorder`](#property-drawborder) | *Описание* |
| [`LineBrush`](#property-linebrush) | *Описание* |
| [`LineColor`](#property-linecolor) | *Описание* |
| [`LinePen`](#property-linepen) | *Описание* |
| [`LineStyle`](#property-linestyle) | *Описание* |
| [`LineWidth`](#property-linewidth) | *Описание* |
| [`int`](#property-int) | *Описание* |





***  
***  
# Методы

## `ApplyTheme`<a href="method-applytheme" id="method-applytheme"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `CopyTemplate`<a href="method-copytemplate" id="method-copytemplate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `PolygonObjectBase`<a href="method-polygonobjectbase" id="method-polygonobjectbase"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected PolygonObjectBase()
```

***  
***  
 ***  
# Свойства

## `BackBrush`<a href="property-backbrush" id="property-backbrush"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XBrush BackBrush { get; private set; }
```  
***

## `BackColor`<a href="property-backcolor" id="property-backcolor"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor BackColor { get; set; }
```  
***

## `DrawBack`<a href="property-drawback" id="property-drawback"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool DrawBack { get; set; }
```  
***

## `DrawBorder`<a href="property-drawborder" id="property-drawborder"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool DrawBorder { get; set; }
```  
***

## `LineBrush`<a href="property-linebrush" id="property-linebrush"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XBrush LineBrush { get; private set; }
```  
***

## `LineColor`<a href="property-linecolor" id="property-linecolor"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor LineColor { get; set; }
```  
***

## `LinePen`<a href="property-linepen" id="property-linepen"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XPen LinePen { get; private set; }
```  
***

## `LineStyle`<a href="property-linestyle" id="property-linestyle"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle LineStyle { get; set; }
```  
***

## `LineWidth`<a href="property-linewidth" id="property-linewidth"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LineWidth { get; set; }
```  
***

## `int`<a href="property-int" id="property-int"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override int PenWidth { get; }
```  
***

