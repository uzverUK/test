
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


===

### Синтаксис
```csharp
public class HorizontalLineObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckAlert`](#method-checkalert) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`Draw`](#method-draw) | *===* |
| [`DrawControlPoints`](#method-drawcontrolpoints) | *===* |
| [`DrawText`](#method-drawtext) | *===* |
| [`HorizontalLineObject`](#method-horizontallineobject) | *===* |
| [`InObject`](#method-inobject) | *===* |
| [`IsObjectOnChart`](#method-isobjectonchart) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Alert`](#property-alert) | *===* |
| [`AlertMinDistance`](#property-alertmindistance) | *===* |
| [`FontSize`](#property-fontsize) | *===* |
| [`LineRect;`](#property-linerect;) | *===* |
| [`Price`](#property-price) | *===* |
| [`Text`](#property-text) | *===* |
| [`TextAlignment`](#property-textalignment) | *===* |
| [`xsuJlZ3bylFkXacpNF53`](#property-xsujlz3bylfkxacpnf53) | *===* |





***  
***  
# Методы

## `CheckAlert`<a href="method-checkalert" id="method-checkalert"></a>
===
```csharp
public override void CheckAlert(System.Collections.Generic.List<IndicatorBase> indicators)
```

***  

## `CopyTemplate`<a href="method-copytemplate" id="method-copytemplate"></a>
===
```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *===*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `Draw`<a href="method-draw" id="method-draw"></a>
===
```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *===*  

`System` <mark style="color:red;">*`ref`*</mark>  
 *===*  


***  

## `DrawControlPoints`<a href="method-drawcontrolpoints" id="method-drawcontrolpoints"></a>
===
```csharp
public override void DrawControlPoints(DxVisualQueue visual)
```

***  

## `DrawText`<a href="method-drawtext" id="method-drawtext"></a>
===
```csharp
protected void DrawText(DxVisualQueue visual)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *===*  


***  

## `HorizontalLineObject`<a href="method-horizontallineobject" id="method-horizontallineobject"></a>
===
```csharp
public HorizontalLineObject()
```

***  

## `InObject`<a href="method-inobject" id="method-inobject"></a>
===
```csharp
protected override bool InObject(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *===*  

`y` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `IsObjectOnChart`<a href="method-isobjectonchart" id="method-isobjectonchart"></a>
===
```csharp
protected override bool IsObjectOnChart()
```

***  
***  
 ***  
# Свойства

## `Alert`<a href="property-alert" id="property-alert"></a>
===
```csharp
public ChartAlertSettings Alert { get; set; }
```  
***

## `AlertMinDistance`<a href="property-alertmindistance" id="property-alertmindistance"></a>
===
```csharp
public int AlertMinDistance { get; set; }
```  
***

## `FontSize`<a href="property-fontsize" id="property-fontsize"></a>
===
```csharp
public int FontSize { get; set; }
```  
***

## `LineRect;`<a href="property-linerect;" id="property-linerect;"></a>
===
```csharp
protected Rect LineRect; {}
```  
***

## `Price`<a href="property-price" id="property-price"></a>
===
```csharp
public Decimal Price { get; set; }
```  
***

## `Text`<a href="property-text" id="property-text"></a>
===
```csharp
public string Text { get; set; }
```  
***

## `TextAlignment`<a href="property-textalignment" id="property-textalignment"></a>
===
```csharp
public ObjectTextAlignment TextAlignment { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>
===
```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

