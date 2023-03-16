
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class FibonacciExtensionsObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](#ApplyTheme-m) | *Описание* |
| [`CopyTemplate`](#CopyTemplate-m) | *Описание* |
| [`Draw`](#Draw-m) | *Описание* |
| [`FibonacciExtensionsObject`](#FibonacciExtensionsObject-m) | *Описание* |
| [`InObject`](#InObject-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`CustomLevels`](#CustomLevels-p) | *Описание* |
| [`Levels`](#Levels-p) | *Описание* |
| [`LevelsLineColor`](#LevelsLineColor-p) | *Описание* |
| [`LevelsLineStyle`](#LevelsLineStyle-p) | *Описание* |
| [`LevelsLineWidth`](#LevelsLineWidth-p) | *Описание* |
| [`LevelsWidth`](#LevelsWidth-p) | *Описание* |
| [`OpenEnd`](#OpenEnd-p) | *Описание* |
| [`OpenStart`](#OpenStart-p) | *Описание* |
| [`TextAlignment`](#TextAlignment-p) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](#xsuJlZ3bylFkXacpNF53-p) | *Описание* |





***  
***  
# Методы

## `ApplyTheme`<a href="InObject-m" id="InObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  


***  

## `CopyTemplate`<a href="InObject-m" id="InObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Draw`<a href="InObject-m" id="InObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`System` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `FibonacciExtensionsObject`<a href="InObject-m" id="InObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public FibonacciExtensionsObject()
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

## `CustomLevels`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CustomLevels { get; set; }
```  
***

## `Levels`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public System.Collections.Generic.List<ObjectLine> Levels { get; set; }
```  
***

## `LevelsLineColor`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor LevelsLineColor { get; set; }
```  
***

## `LevelsLineStyle`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle LevelsLineStyle { get; set; }
```  
***

## `LevelsLineWidth`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LevelsLineWidth { get; set; }
```  
***

## `LevelsWidth`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LevelsWidth { get; set; }
```  
***

## `OpenEnd`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenEnd { get; set; }
```  
***

## `OpenStart`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenStart { get; set; }
```  
***

## `TextAlignment`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
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

