
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class PolygonObjectBase : ObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./PolygonObjectBase.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./PolygonObjectBase.cs/Методы/CopyTemplate.md) | *Описание* |
| [`PolygonObjectBase`](./PolygonObjectBase.cs/Методы/PolygonObjectBase.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`BackBrush`](./PolygonObjectBase.cs/Свойства/BackBrush.md) | *Описание* |
| [`BackColor`](./PolygonObjectBase.cs/Свойства/BackColor.md) | *Описание* |
| [`DrawBack`](./PolygonObjectBase.cs/Свойства/DrawBack.md) | *Описание* |
| [`DrawBorder`](./PolygonObjectBase.cs/Свойства/DrawBorder.md) | *Описание* |
| [`LineBrush`](./PolygonObjectBase.cs/Свойства/LineBrush.md) | *Описание* |
| [`LineColor`](./PolygonObjectBase.cs/Свойства/LineColor.md) | *Описание* |
| [`LinePen`](./PolygonObjectBase.cs/Свойства/LinePen.md) | *Описание* |
| [`LineStyle`](./PolygonObjectBase.cs/Свойства/LineStyle.md) | *Описание* |
| [`LineWidth`](./PolygonObjectBase.cs/Свойства/LineWidth.md) | *Описание* |
| [`int`](./PolygonObjectBase.cs/Свойства/int.md) | *Описание* |





# Методы

## `ApplyTheme`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  



## `CopyTemplate`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## `PolygonObjectBase`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected PolygonObjectBase()
```

# Свойства

## `BackBrush`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XBrush BackBrush { get; private set; }
```

## `BackColor`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor BackColor { get; set; }
```

## `DrawBack`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool DrawBack { get; set; }
```

## `DrawBorder`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool DrawBorder { get; set; }
```

## `LineBrush`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XBrush LineBrush { get; private set; }
```

## `LineColor`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor LineColor { get; set; }
```

## `LinePen`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XPen LinePen { get; private set; }
```

## `LineStyle`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle LineStyle { get; set; }
```

## `LineWidth`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LineWidth { get; set; }
```

## `int`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override int PenWidth { get; }
```

