
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public class HorizontalLineObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckAlert`](#method-checkalert) | *Описание* |
| [`CopyTemplate`](#method-copytemplate) | *Описание* |
| [`Draw`](#method-draw) | *Описание* |
| [`DrawControlPoints`](#method-drawcontrolpoints) | *Описание* |
| [`DrawText`](#method-drawtext) | *Описание* |
| [`HorizontalLineObject`](#method-horizontallineobject) | *Описание* |
| [`InObject`](#method-inobject) | *Описание* |
| [`IsObjectOnChart`](#method-isobjectonchart) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Alert`](#property-alert) | *Описание* |
| [`AlertMinDistance`](#property-alertmindistance) | *Описание* |
| [`FontSize`](#property-fontsize) | *Описание* |
| [`LineRect;`](#property-linerect;) | *Описание* |
| [`Price`](#property-price) | *Описание* |
| [`Text`](#property-text) | *Описание* |
| [`TextAlignment`](#property-textalignment) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](#property-xsujlz3bylfkxacpnf53) | *Описание* |





***  
***  
# Методы

## `CheckAlert`<a href="method-checkalert" id="method-checkalert"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CheckAlert(System.Collections.Generic.List<IndicatorBase> indicators)
```

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

## `Draw`<a href="method-draw" id="method-draw"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`System` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `DrawControlPoints`<a href="method-drawcontrolpoints" id="method-drawcontrolpoints"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void DrawControlPoints(DxVisualQueue visual)
```

***  

## `DrawText`<a href="method-drawtext" id="method-drawtext"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void DrawText(DxVisualQueue visual)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `HorizontalLineObject`<a href="method-horizontallineobject" id="method-horizontallineobject"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public HorizontalLineObject()
```

***  

## `InObject`<a href="method-inobject" id="method-inobject"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `IsObjectOnChart`<a href="method-isobjectonchart" id="method-isobjectonchart"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool IsObjectOnChart()
```

***  
***  
 ***  
# Свойства

## `Alert`<a href="property-alert" id="property-alert"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertSettings Alert { get; set; }
```  
***

## `AlertMinDistance`<a href="property-alertmindistance" id="property-alertmindistance"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AlertMinDistance { get; set; }
```  
***

## `FontSize`<a href="property-fontsize" id="property-fontsize"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int FontSize { get; set; }
```  
***

## `LineRect;`<a href="property-linerect;" id="property-linerect;"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Rect LineRect; {}
```  
***

## `Price`<a href="property-price" id="property-price"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Decimal Price { get; set; }
```  
***

## `Text`<a href="property-text" id="property-text"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Text { get; set; }
```  
***

## `TextAlignment`<a href="property-textalignment" id="property-textalignment"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectTextAlignment TextAlignment { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

