
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


===

### Синтаксис
```csharp
public sealed class LineObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckAlert`](#method-checkalert) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`Draw`](#method-draw) | *===* |
| [`InObject`](#method-inobject) | *===* |
| [`LineObject`](#method-lineobject) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Alert`](#property-alert) | *===* |
| [`AlertMinDistance`](#property-alertmindistance) | *===* |
| [`OpenEnd`](#property-openend) | *===* |
| [`OpenStart`](#property-openstart) | *===* |
| [`RefPoint`](#property-refpoint) | *===* |
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

## `LineObject`<a href="method-lineobject" id="method-lineobject"></a>
===
```csharp
public LineObject()
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

## `OpenEnd`<a href="property-openend" id="property-openend"></a>
===
```csharp
public bool OpenEnd { get; set; }
```  
***

## `OpenStart`<a href="property-openstart" id="property-openstart"></a>
===
```csharp
public bool OpenStart { get; set; }
```  
***

## `RefPoint`<a href="property-refpoint" id="property-refpoint"></a>
===
```csharp
public ObjectPoint? RefPoint { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>
===
```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

