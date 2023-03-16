
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


===

### Синтаксис
```csharp
public sealed class FibonacciRetracementObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#method-applytheme) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`Draw`](#method-draw) | *===* |
| [`FibonacciRetracementObject`](#method-fibonacciretracementobject) | *===* |
| [`InObject`](#method-inobject) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`CustomLevels`](#property-customlevels) | *===* |
| [`Levels`](#property-levels) | *===* |
| [`OpenEnd`](#property-openend) | *===* |
| [`OpenStart`](#property-openstart) | *===* |
| [`TextAlignment`](#property-textalignment) | *===* |
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

## `FibonacciRetracementObject`<a href="method-fibonacciretracementobject" id="method-fibonacciretracementobject"></a>
===
```csharp
public FibonacciRetracementObject()
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

## `CustomLevels`<a href="property-customlevels" id="property-customlevels"></a>
===
```csharp
public bool CustomLevels { get; set; }
```  
***

## `Levels`<a href="property-levels" id="property-levels"></a>
===
```csharp
public System.Collections.Generic.List<ObjectLine> Levels { get; set; }
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

