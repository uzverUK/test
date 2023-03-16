
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class LineObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CheckAlert`](#test) | *Описание* |
| [`CopyTemplate`](#test) | *Описание* |
| [`Draw`](#test) | *Описание* |
| [`InObject`](#test) | *Описание* |
| [`LineObject`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Alert`](./LineObject.cs/Свойства/Alert.md) | *Описание* |
| [`AlertMinDistance`](./LineObject.cs/Свойства/AlertMinDistance.md) | *Описание* |
| [`OpenEnd`](./LineObject.cs/Свойства/OpenEnd.md) | *Описание* |
| [`OpenStart`](./LineObject.cs/Свойства/OpenStart.md) | *Описание* |
| [`RefPoint`](./LineObject.cs/Свойства/RefPoint.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./LineObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |





***  
***  
# Методы

## `CheckAlert`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CheckAlert(System.Collections.Generic.List<IndicatorBase> indicators)
```

***  

## `CopyTemplate`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Draw`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`System` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `InObject`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `LineObject`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public LineObject()
```

***  
***  
 ***  
# Свойства

## `Alert`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertSettings Alert { get; set; }
```  
***

## `AlertMinDistance`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int AlertMinDistance { get; set; }
```  
***

## `OpenEnd`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenEnd { get; set; }
```  
***

## `OpenStart`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenStart { get; set; }
```  
***

## `RefPoint`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectPoint? RefPoint { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

