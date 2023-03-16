
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


===

### Синтаксис
```csharp
public class IconObject : ObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#method-applytheme) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`Draw`](#method-draw) | *===* |
| [`IconObject`](#method-iconobject) | *===* |
| [`InObject`](#method-inobject) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Brush`](#property-brush) | *===* |
| [`Color`](#property-color) | *===* |
| [`Icon`](#property-icon) | *===* |
| [`Size`](#property-size) | *===* |
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

## `IconObject`<a href="method-iconobject" id="method-iconobject"></a>
===
```csharp
public IconObject()
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
***  
 ***  
# Свойства

## `Brush`<a href="property-brush" id="property-brush"></a>
===
```csharp
protected XBrush Brush { get; private set; }
```  
***

## `Color`<a href="property-color" id="property-color"></a>
===
```csharp
public XColor Color { get; set; }
```  
***

## `Icon`<a href="property-icon" id="property-icon"></a>
===
```csharp
public string Icon { get; set; }
```  
***

## `Size`<a href="property-size" id="property-size"></a>
===
```csharp
public int Size { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>
===
```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

