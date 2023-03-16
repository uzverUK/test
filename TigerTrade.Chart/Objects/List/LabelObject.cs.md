
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


===

### Синтаксис
```csharp
public sealed class LabelObject : PolygonObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#method-applytheme) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`Draw`](#method-draw) | *===* |
| [`InObject`](#method-inobject) | *===* |
| [`LabelObject`](#method-labelobject) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`FontSize`](#property-fontsize) | *===* |
| [`LabelColor`](#property-labelcolor) | *===* |
| [`LabelText`](#property-labeltext) | *===* |
| [`xsuJlZ3bylFkXacpNF53`](#property-xsujlz3bylfkxacpnf53) | *===* |





***  
***  
# Методы

## `ApplyTheme`<a href="method-applytheme" id="method-applytheme"></a>
===
```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *===*  


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

## `LabelObject`<a href="method-labelobject" id="method-labelobject"></a>
===
```csharp
public LabelObject()
```

***  
***  
 ***  
# Свойства

## `FontSize`<a href="property-fontsize" id="property-fontsize"></a>
===
```csharp
public int FontSize { get; set; }
```  
***

## `LabelColor`<a href="property-labelcolor" id="property-labelcolor"></a>
===
```csharp
public XColor LabelColor { get; set; }
```  
***

## `LabelText`<a href="property-labeltext" id="property-labeltext"></a>
===
```csharp
public string LabelText { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>
===
```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

