
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class RulerObject : LineObjectBase
```


## Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./RulerObject.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./RulerObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./RulerObject.cs/Методы/Draw.md) | *Описание* |
| [`InObject`](./RulerObject.cs/Методы/InObject.md) | *Описание* |
| [`PrettyFormatTimeSpan`](./RulerObject.cs/Методы/PrettyFormatTimeSpan.md) | *Описание* |
| [`RulerObject`](./RulerObject.cs/Методы/RulerObject.md) | *Описание* |

## Таблица свойств
| Название | Описание |
| --- | --- |
| [`ShowInfoAsk`](./RulerObject.cs/Свойства/ShowInfoAsk.md) | *Описание* |
| [`ShowInfoBars`](./RulerObject.cs/Свойства/ShowInfoBars.md) | *Описание* |
| [`ShowInfoBid`](./RulerObject.cs/Свойства/ShowInfoBid.md) | *Описание* |
| [`ShowInfoChange`](./RulerObject.cs/Свойства/ShowInfoChange.md) | *Описание* |
| [`ShowInfoDelta`](./RulerObject.cs/Свойства/ShowInfoDelta.md) | *Описание* |
| [`ShowInfoPrice`](./RulerObject.cs/Свойства/ShowInfoPrice.md) | *Описание* |
| [`ShowInfoTicks`](./RulerObject.cs/Свойства/ShowInfoTicks.md) | *Описание* |
| [`ShowInfoTime`](./RulerObject.cs/Свойства/ShowInfoTime.md) | *Описание* |
| [`ShowInfoTrades`](./RulerObject.cs/Свойства/ShowInfoTrades.md) | *Описание* |
| [`ShowInfoVolume`](./RulerObject.cs/Свойства/ShowInfoVolume.md) | *Описание* |
| [`TextColor`](./RulerObject.cs/Свойства/TextColor.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./RulerObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |




            ***
  ***
  # Методы

## ApplyTheme
Описание

```csharp
public override void ApplyTheme(IChartTheme theme)
```

<mark style="color:yellow;">`theme`</mark> <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***                

## CopyTemplate
Описание

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
<mark style="color:yellow;">`objectBase`</mark> <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***                

## Draw
Описание

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
<mark style="color:yellow;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

<mark style="color:yellow;">`System`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***                

## InObject
Описание

```csharp
protected override bool InObject(int x, int y)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## PrettyFormatTimeSpan
Описание

```csharp
public string PrettyFormatTimeSpan(TimeSpan span)
```
<mark style="color:yellow;">`span`</mark> <mark style="color:red;">*`TimeSpan`*</mark>  
 *Описание*  


***                

## RulerObject
Описание

```csharp
public RulerObject()
```

***                
                ***
  ***
  # Свойства

## ShowInfoAsk
Описание

```csharp
public bool ShowInfoAsk { get; set; }
```
***

## ShowInfoBars
Описание

```csharp
public bool ShowInfoBars { get; set; }
```
***

## ShowInfoBid
Описание

```csharp
public bool ShowInfoBid { get; set; }
```
***

## ShowInfoChange
Описание

```csharp
public bool ShowInfoChange { get; set; }
```
***

## ShowInfoDelta
Описание

```csharp
public bool ShowInfoDelta { get; set; }
```
***

## ShowInfoPrice
Описание

```csharp
public bool ShowInfoPrice { get; set; }
```
***

## ShowInfoTicks
Описание

```csharp
public bool ShowInfoTicks { get; set; }
```
***

## ShowInfoTime
Описание

```csharp
public bool ShowInfoTime { get; set; }
```
***

## ShowInfoTrades
Описание

```csharp
public bool ShowInfoTrades { get; set; }
```
***

## ShowInfoVolume
Описание

```csharp
public bool ShowInfoVolume { get; set; }
```
***

## TextColor
Описание

```csharp
public XColor TextColor { get; set; }
```
***

## xsuJlZ3bylFkXacpNF53
Описание

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```
***

