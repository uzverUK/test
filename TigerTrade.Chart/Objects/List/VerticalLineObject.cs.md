
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class VerticalLineObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckAlert`](#CheckAlert-m) | *Описание* |
| [`CopyTemplate`](#CopyTemplate-m) | *Описание* |
| [`Draw`](#Draw-m) | *Описание* |
| [`DrawControlPoints`](#DrawControlPoints-m) | *Описание* |
| [`InObject`](#InObject-m) | *Описание* |
| [`VerticalLineObject`](#VerticalLineObject-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Alert`](#Alert-p) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](#xsuJlZ3bylFkXacpNF53-p) | *Описание* |





***  
***  
# Методы

## `CheckAlert`<a href="CheckAlert-m" id="CheckAlert-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CheckAlert(System.Collections.Generic.List<IndicatorBase> indicators)
```

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

## `Draw`<a href="Draw-m" id="Draw-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`System` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `DrawControlPoints`<a href="DrawControlPoints-m" id="DrawControlPoints-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void DrawControlPoints(DxVisualQueue visual)
```

***  

## `InObject`<a href="InObject-m" id="InObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `VerticalLineObject`<a href="VerticalLineObject-m" id="VerticalLineObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public VerticalLineObject()
```

***  
***  
 ***  
# Свойства

## `Alert`<a href="Alert-p" id="Alert-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertSettings Alert { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

