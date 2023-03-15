
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class LabelObject : PolygonObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./LabelObject.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./LabelObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./LabelObject.cs/Методы/Draw.md) | *Описание* |
| [`InObject`](./LabelObject.cs/Методы/InObject.md) | *Описание* |
| [`LabelObject`](./LabelObject.cs/Методы/LabelObject.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`FontSize`](./LabelObject.cs/Свойства/FontSize.md) | *Описание* |
| [`LabelColor`](./LabelObject.cs/Свойства/LabelColor.md) | *Описание* |
| [`LabelText`](./LabelObject.cs/Свойства/LabelText.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./LabelObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |





# Методы

## *ApplyTheme*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```

<mark style="color:yellow;">`theme`</mark> <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  



## *CopyTemplate*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
<mark style="color:yellow;">`objectBase`</mark> <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *Draw*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
<mark style="color:yellow;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

<mark style="color:yellow;">`System`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  



## *InObject*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *LabelObject*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public LabelObject()
```

# Свойства

## *FontSize*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int FontSize { get; set; }
```

## *LabelColor*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor LabelColor { get; set; }
```

## *LabelText*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string LabelText { get; set; }
```

## *xsuJlZ3bylFkXacpNF53*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

