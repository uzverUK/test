
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


===

### Синтаксис
```csharp
public abstract class ElliottWaveObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopyTemplate`](#method-copytemplate) | *===* |
| [`Draw`](#method-draw) | *===* |
| [`ElliottWaveObject`](#method-elliottwaveobject) | *===* |
| [`GetDegreeText`](#method-getdegreetext) | *===* |
| [`InObject`](#method-inobject) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Degree`](#property-degree) | *===* |
| [`ShowWave`](#property-showwave) | *===* |
| [`xsuJlZ3bylFkXacpNF53`](#property-xsujlz3bylfkxacpnf53) | *===* |





***  
***  
# Методы

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

## `ElliottWaveObject`<a href="method-elliottwaveobject" id="method-elliottwaveobject"></a>
===
```csharp
protected ElliottWaveObject()
```

***  

## `GetDegreeText`<a href="method-getdegreetext" id="method-getdegreetext"></a>
===
```csharp
protected abstract string GetDegreeText(int num)
```

`num` <mark style="color:red;">*`int`*</mark>  
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
***  
 ***  
# Свойства

## `Degree`<a href="property-degree" id="property-degree"></a>
===
```csharp
public ElliottWaveDegree Degree { get; set; }
```  
***

## `ShowWave`<a href="property-showwave" id="property-showwave"></a>
===
```csharp
public bool ShowWave { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>
===
```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

