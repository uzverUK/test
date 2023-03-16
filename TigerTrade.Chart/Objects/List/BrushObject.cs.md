
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


===

### Синтаксис
```csharp
public sealed class BrushObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddPoint`](#method-addpoint) | *===* |
| [`ApplyTheme`](#method-applytheme) | *===* |
| [`BrushObject`](#method-brushobject) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`Draw`](#method-draw) | *===* |
| [`GetMinDist`](#method-getmindist) | *===* |
| [`InObject`](#method-inobject) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Points`](#property-points) | *===* |
| [`xsuJlZ3bylFkXacpNF53`](#property-xsujlz3bylfkxacpnf53) | *===* |





***  
***  
# Методы

## `AddPoint`<a href="method-addpoint" id="method-addpoint"></a>
===
```csharp
public void AddPoint(ObjectPoint op)
```

`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *===*  


***  

## `ApplyTheme`<a href="method-applytheme" id="method-applytheme"></a>
===
```csharp
public override void ApplyTheme(IChartTheme theme)
```
`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *===*  


***  

## `BrushObject`<a href="method-brushobject" id="method-brushobject"></a>
===
```csharp
public BrushObject()
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

## `GetMinDist`<a href="method-getmindist" id="method-getmindist"></a>
===
```csharp
protected override int GetMinDist(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *===*  

`y` <mark style="color:red;">*`int`*</mark>  
 *===*  


***  

## `InObject`<a href="method-inobject" id="method-inobject"></a>
===
```csharp
protected override bool InObject(int x, int y)
```

***  
***  
 ***  
# Свойства

## `Points`<a href="property-points" id="property-points"></a>
===
```csharp
public System.Collections.Generic.List<ObjectPoint> Points { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>
===
```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

