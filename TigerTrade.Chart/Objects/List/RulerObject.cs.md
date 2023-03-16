
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class RulerObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#method-applytheme) | *Описание* |
| [`CopyTemplate`](#method-copytemplate) | *Описание* |
| [`Draw`](#method-draw) | *Описание* |
| [`InObject`](#method-inobject) | *Описание* |
| [`PrettyFormatTimeSpan`](#method-prettyformattimespan) | *Описание* |
| [`RulerObject`](#method-rulerobject) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ShowInfoAsk`](#property-showinfoask) | *Описание* |
| [`ShowInfoBars`](#property-showinfobars) | *Описание* |
| [`ShowInfoBid`](#property-showinfobid) | *Описание* |
| [`ShowInfoChange`](#property-showinfochange) | *Описание* |
| [`ShowInfoDelta`](#property-showinfodelta) | *Описание* |
| [`ShowInfoPrice`](#property-showinfoprice) | *Описание* |
| [`ShowInfoTicks`](#property-showinfoticks) | *Описание* |
| [`ShowInfoTime`](#property-showinfotime) | *Описание* |
| [`ShowInfoTrades`](#property-showinfotrades) | *Описание* |
| [`ShowInfoVolume`](#property-showinfovolume) | *Описание* |
| [`TextColor`](#property-textcolor) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](#property-xsujlz3bylfkxacpnf53) | *Описание* |





***  
***  
# Методы

## `ApplyTheme`<a href="method-applytheme" id="method-applytheme"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


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

## `PrettyFormatTimeSpan`<a href="method-prettyformattimespan" id="method-prettyformattimespan"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PrettyFormatTimeSpan(TimeSpan span)
```
`span` <mark style="color:red;">*`TimeSpan`*</mark>  
 *Описание*  


***  

## `RulerObject`<a href="method-rulerobject" id="method-rulerobject"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RulerObject()
```

***  
***  
 ***  
# Свойства

## `ShowInfoAsk`<a href="property-showinfoask" id="property-showinfoask"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoAsk { get; set; }
```  
***

## `ShowInfoBars`<a href="property-showinfobars" id="property-showinfobars"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoBars { get; set; }
```  
***

## `ShowInfoBid`<a href="property-showinfobid" id="property-showinfobid"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoBid { get; set; }
```  
***

## `ShowInfoChange`<a href="property-showinfochange" id="property-showinfochange"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoChange { get; set; }
```  
***

## `ShowInfoDelta`<a href="property-showinfodelta" id="property-showinfodelta"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoDelta { get; set; }
```  
***

## `ShowInfoPrice`<a href="property-showinfoprice" id="property-showinfoprice"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoPrice { get; set; }
```  
***

## `ShowInfoTicks`<a href="property-showinfoticks" id="property-showinfoticks"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoTicks { get; set; }
```  
***

## `ShowInfoTime`<a href="property-showinfotime" id="property-showinfotime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoTime { get; set; }
```  
***

## `ShowInfoTrades`<a href="property-showinfotrades" id="property-showinfotrades"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoTrades { get; set; }
```  
***

## `ShowInfoVolume`<a href="property-showinfovolume" id="property-showinfovolume"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoVolume { get; set; }
```  
***

## `TextColor`<a href="property-textcolor" id="property-textcolor"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor TextColor { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

