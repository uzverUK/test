
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class LineObjectBase : ObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#ApplyTheme-m) | *Описание* |
| [`CopyTemplate`](#CopyTemplate-m) | *Описание* |
| [`LineObjectBase`](#LineObjectBase-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`LineBrush`](#LineBrush-p) | *Описание* |
| [`LineColor`](#LineColor-p) | *Описание* |
| [`LinePen`](#LinePen-p) | *Описание* |
| [`LineStyle`](#LineStyle-p) | *Описание* |
| [`LineWidth`](#LineWidth-p) | *Описание* |
| [`int`](#int-p) | *Описание* |





***  
***  
# Методы

## `ApplyTheme`<a href="ApplyTheme-m" id="ApplyTheme-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `CopyTemplate`<a href="CopyTemplate-m" id="CopyTemplate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `LineObjectBase`<a href="LineObjectBase-m" id="LineObjectBase-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected LineObjectBase()
```

***  
***  
 ***  
# Свойства

## `LineBrush`<a href="LineBrush-p" id="LineBrush-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XBrush LineBrush { get; private set; }
```  
***

## `LineColor`<a href="LineColor-p" id="LineColor-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor LineColor { get; set; }
```  
***

## `LinePen`<a href="LinePen-p" id="LinePen-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XPen LinePen { get; private set; }
```  
***

## `LineStyle`<a href="LineStyle-p" id="LineStyle-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle LineStyle { get; set; }
```  
***

## `LineWidth`<a href="LineWidth-p" id="LineWidth-p"></a>
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

