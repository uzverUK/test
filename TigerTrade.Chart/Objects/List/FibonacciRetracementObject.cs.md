
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class FibonacciRetracementObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#ApplyTheme-m) | *Описание* |
| [`CopyTemplate`](#CopyTemplate-m) | *Описание* |
| [`Draw`](#Draw-m) | *Описание* |
| [`FibonacciRetracementObject`](#FibonacciRetracementObject-m) | *Описание* |
| [`InObject`](#InObject-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`CustomLevels`](#CustomLevels-p) | *Описание* |
| [`Levels`](#Levels-p) | *Описание* |
| [`OpenEnd`](#OpenEnd-p) | *Описание* |
| [`OpenStart`](#OpenStart-p) | *Описание* |
| [`TextAlignment`](#TextAlignment-p) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](#xsuJlZ3bylFkXacpNF53-p) | *Описание* |





***  
***  
# Методы

## `ApplyTheme`<a href="ApplyTheme-m" id="ApplyTheme-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `CopyTemplate`<a href="CopyTemplate-m" id="CopyTemplate-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Draw`<a href="Draw-m" id="Draw-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`System` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `FibonacciRetracementObject`<a href="FibonacciRetracementObject-m" id="FibonacciRetracementObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public FibonacciRetracementObject()
```

***  

## `InObject`<a href="InObject-m" id="InObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `CustomLevels`<a href="CustomLevels-p" id="CustomLevels-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CustomLevels { get; set; }
```  
***

## `Levels`<a href="Levels-p" id="Levels-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public System.Collections.Generic.List<ObjectLine> Levels { get; set; }
```  
***

## `OpenEnd`<a href="OpenEnd-p" id="OpenEnd-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenEnd { get; set; }
```  
***

## `OpenStart`<a href="OpenStart-p" id="OpenStart-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenStart { get; set; }
```  
***

## `TextAlignment`<a href="TextAlignment-p" id="TextAlignment-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectTextAlignment TextAlignment { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

