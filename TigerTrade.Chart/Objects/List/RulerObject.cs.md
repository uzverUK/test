
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


===

### Синтаксис
```csharp
public sealed class RulerObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#method-applytheme) | *===* |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`Draw`](#method-draw) | *===* |
| [`InObject`](#method-inobject) | *===* |
| [`PrettyFormatTimeSpan`](#method-prettyformattimespan) | *===* |
| [`RulerObject`](#method-rulerobject) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ShowInfoAsk`](#property-showinfoask) | *===* |
| [`ShowInfoBars`](#property-showinfobars) | *===* |
| [`ShowInfoBid`](#property-showinfobid) | *===* |
| [`ShowInfoChange`](#property-showinfochange) | *===* |
| [`ShowInfoDelta`](#property-showinfodelta) | *===* |
| [`ShowInfoPrice`](#property-showinfoprice) | *===* |
| [`ShowInfoTicks`](#property-showinfoticks) | *===* |
| [`ShowInfoTime`](#property-showinfotime) | *===* |
| [`ShowInfoTrades`](#property-showinfotrades) | *===* |
| [`ShowInfoVolume`](#property-showinfovolume) | *===* |
| [`TextColor`](#property-textcolor) | *===* |
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

## `PrettyFormatTimeSpan`<a href="method-prettyformattimespan" id="method-prettyformattimespan"></a>
===
```csharp
public string PrettyFormatTimeSpan(TimeSpan span)
```
`span` <mark style="color:red;">*`TimeSpan`*</mark>  
 *===*  


***  

## `RulerObject`<a href="method-rulerobject" id="method-rulerobject"></a>
===
```csharp
public RulerObject()
```

***  
***  
 ***  
# Свойства

## `ShowInfoAsk`<a href="property-showinfoask" id="property-showinfoask"></a>
===
```csharp
public bool ShowInfoAsk { get; set; }
```  
***

## `ShowInfoBars`<a href="property-showinfobars" id="property-showinfobars"></a>
===
```csharp
public bool ShowInfoBars { get; set; }
```  
***

## `ShowInfoBid`<a href="property-showinfobid" id="property-showinfobid"></a>
===
```csharp
public bool ShowInfoBid { get; set; }
```  
***

## `ShowInfoChange`<a href="property-showinfochange" id="property-showinfochange"></a>
===
```csharp
public bool ShowInfoChange { get; set; }
```  
***

## `ShowInfoDelta`<a href="property-showinfodelta" id="property-showinfodelta"></a>
===
```csharp
public bool ShowInfoDelta { get; set; }
```  
***

## `ShowInfoPrice`<a href="property-showinfoprice" id="property-showinfoprice"></a>
===
```csharp
public bool ShowInfoPrice { get; set; }
```  
***

## `ShowInfoTicks`<a href="property-showinfoticks" id="property-showinfoticks"></a>
===
```csharp
public bool ShowInfoTicks { get; set; }
```  
***

## `ShowInfoTime`<a href="property-showinfotime" id="property-showinfotime"></a>
===
```csharp
public bool ShowInfoTime { get; set; }
```  
***

## `ShowInfoTrades`<a href="property-showinfotrades" id="property-showinfotrades"></a>
===
```csharp
public bool ShowInfoTrades { get; set; }
```  
***

## `ShowInfoVolume`<a href="property-showinfovolume" id="property-showinfovolume"></a>
===
```csharp
public bool ShowInfoVolume { get; set; }
```  
***

## `TextColor`<a href="property-textcolor" id="property-textcolor"></a>
===
```csharp
public XColor TextColor { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>
===
```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

