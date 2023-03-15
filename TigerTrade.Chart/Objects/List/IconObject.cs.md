
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public class IconObject : ObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./IconObject.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./IconObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./IconObject.cs/Методы/Draw.md) | *Описание* |
| [`IconObject`](./IconObject.cs/Методы/IconObject.md) | *Описание* |
| [`InObject`](./IconObject.cs/Методы/InObject.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Brush`](./IconObject.cs/Свойства/Brush.md) | *Описание* |
| [`Color`](./IconObject.cs/Свойства/Color.md) | *Описание* |
| [`Icon`](./IconObject.cs/Свойства/Icon.md) | *Описание* |
| [`Size`](./IconObject.cs/Свойства/Size.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./IconObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |





# Методы

## `ApplyTheme`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  



## `CopyTemplate`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## `Draw`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`System` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  



## `IconObject`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public IconObject()
```


## `InObject`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


# Свойства

## `Brush`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected XBrush Brush { get; private set; }
```

## `Color`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor Color { get; set; }
```

## `Icon`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Icon { get; set; }
```

## `Size`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int Size { get; set; }
```

## `xsuJlZ3bylFkXacpNF53`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

