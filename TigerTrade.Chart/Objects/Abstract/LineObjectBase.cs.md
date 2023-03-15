
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class LineObjectBase : ObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./LineObjectBase.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./LineObjectBase.cs/Методы/CopyTemplate.md) | *Описание* |
| [`LineObjectBase`](./LineObjectBase.cs/Методы/LineObjectBase.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`LineBrush`](./LineObjectBase.cs/Свойства/LineBrush.md) | *Описание* |
| [`LineColor`](./LineObjectBase.cs/Свойства/LineColor.md) | *Описание* |
| [`LinePen`](./LineObjectBase.cs/Свойства/LinePen.md) | *Описание* |
| [`LineStyle`](./LineObjectBase.cs/Свойства/LineStyle.md) | *Описание* |
| [`LineWidth`](./LineObjectBase.cs/Свойства/LineWidth.md) | *Описание* |
| [`int`](./LineObjectBase.cs/Свойства/int.md) | *Описание* |





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



## `LineObjectBase`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected LineObjectBase()
```

# Свойства

## `LineBrush`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XBrush LineBrush { get; private set; }
```

## `LineColor`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor LineColor { get; set; }
```

## `LinePen`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XPen LinePen { get; private set; }
```

## `LineStyle`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle LineStyle { get; set; }
```

## `LineWidth`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LineWidth { get; set; }
```

## `int`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override int PenWidth { get; }
```

