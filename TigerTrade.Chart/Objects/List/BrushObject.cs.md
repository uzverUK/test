
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class BrushObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AddPoint`](#method-addpoint) | *Описание* |
| [`ApplyTheme`](#method-applytheme) | *Описание* |
| [`BrushObject`](#method-brushobject) | *Описание* |
| [`CopyTemplate`](#method-copytemplate) | *Описание* |
| [`Draw`](#method-draw) | *Описание* |
| [`GetMinDist`](#method-getmindist) | *Описание* |
| [`InObject`](#method-inobject) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Points`](#property-points) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](#property-xsujlz3bylfkxacpnf53) | *Описание* |





***  
***  
# Методы

## `AddPoint`<a href="method-addpoint" id="method-addpoint"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void AddPoint(ObjectPoint op)
```

`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***  

## `ApplyTheme`<a href="method-applytheme" id="method-applytheme"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```
`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `BrushObject`<a href="method-brushobject" id="method-brushobject"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public BrushObject()
```

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

## `GetMinDist`<a href="method-getmindist" id="method-getmindist"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override int GetMinDist(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `InObject`<a href="method-inobject" id="method-inobject"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```

***  
***  
 ***  
# Свойства

## `Points`<a href="property-points" id="property-points"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public System.Collections.Generic.List<ObjectPoint> Points { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="property-xsujlz3bylfkxacpnf53" id="property-xsujlz3bylfkxacpnf53"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

