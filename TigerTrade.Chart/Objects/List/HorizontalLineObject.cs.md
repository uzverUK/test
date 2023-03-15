
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public class HorizontalLineObject : LineObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CheckAlert`](./HorizontalLineObject.cs/Методы/CheckAlert.md) | *Описание* |
| [`CopyTemplate`](./HorizontalLineObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./HorizontalLineObject.cs/Методы/Draw.md) | *Описание* |
| [`DrawControlPoints`](./HorizontalLineObject.cs/Методы/DrawControlPoints.md) | *Описание* |
| [`DrawText`](./HorizontalLineObject.cs/Методы/DrawText.md) | *Описание* |
| [`HorizontalLineObject`](./HorizontalLineObject.cs/Методы/HorizontalLineObject.md) | *Описание* |
| [`InObject`](./HorizontalLineObject.cs/Методы/InObject.md) | *Описание* |
| [`IsObjectOnChart`](./HorizontalLineObject.cs/Методы/IsObjectOnChart.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Alert`](./HorizontalLineObject.cs/Свойства/Alert.md) | *Описание* |
| [`AlertMinDistance`](./HorizontalLineObject.cs/Свойства/AlertMinDistance.md) | *Описание* |
| [`FontSize`](./HorizontalLineObject.cs/Свойства/FontSize.md) | *Описание* |
| [`LineRect;`](./HorizontalLineObject.cs/Свойства/LineRect;.md) | *Описание* |
| [`Price`](./HorizontalLineObject.cs/Свойства/Price.md) | *Описание* |
| [`Text`](./HorizontalLineObject.cs/Свойства/Text.md) | *Описание* |
| [`TextAlignment`](./HorizontalLineObject.cs/Свойства/TextAlignment.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./HorizontalLineObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |





# Методы

## *CheckAlert*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CheckAlert(System.Collections.Generic.List<IndicatorBase> indicators)
```


## *CopyTemplate*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

<mark style="color:purple;">`objectBase`</mark> <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

<mark style="color:purple;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *Draw*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
<mark style="color:purple;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

<mark style="color:purple;">`System`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  



## *DrawControlPoints*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void DrawControlPoints(DxVisualQueue visual)
```


## *DrawText*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void DrawText(DxVisualQueue visual)
```

<mark style="color:purple;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  



## *HorizontalLineObject*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public HorizontalLineObject()
```


## *InObject*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```

<mark style="color:purple;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:purple;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *IsObjectOnChart*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool IsObjectOnChart()
```

# Свойства

## *Alert*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertSettings Alert { get; set; }
```

## *AlertMinDistance*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AlertMinDistance { get; set; }
```

## *FontSize*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int FontSize { get; set; }
```

## *LineRect;*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Rect LineRect; {}
```

## *Price*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Price { get; set; }
```

## *Text*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Text { get; set; }
```

## *TextAlignment*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectTextAlignment TextAlignment { get; set; }
```

## *xsuJlZ3bylFkXacpNF53*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

