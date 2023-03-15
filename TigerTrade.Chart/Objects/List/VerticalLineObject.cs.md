
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class VerticalLineObject : LineObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CheckAlert`](./VerticalLineObject.cs/Методы/CheckAlert.md) | *Описание* |
| [`CopyTemplate`](./VerticalLineObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./VerticalLineObject.cs/Методы/Draw.md) | *Описание* |
| [`DrawControlPoints`](./VerticalLineObject.cs/Методы/DrawControlPoints.md) | *Описание* |
| [`InObject`](./VerticalLineObject.cs/Методы/InObject.md) | *Описание* |
| [`VerticalLineObject`](./VerticalLineObject.cs/Методы/VerticalLineObject.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Alert`](./VerticalLineObject.cs/Свойства/Alert.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./VerticalLineObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |





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


## *InObject*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```

<mark style="color:purple;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:purple;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *VerticalLineObject*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public VerticalLineObject()
```

# Свойства

## *Alert*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertSettings Alert { get; set; }
```

## *xsuJlZ3bylFkXacpNF53*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

