
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public class RectangleObject : PolygonObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Draw`](#Draw-m) | *Описание* |
| [`DrawControlPoints`](#DrawControlPoints-m) | *Описание* |
| [`ExtraPointChanged`](#ExtraPointChanged-m) | *Описание* |
| [`GetControlPoint`](#GetControlPoint-m) | *Описание* |
| [`GetExtraPoint`](#GetExtraPoint-m) | *Описание* |
| [`GetMinDist`](#GetMinDist-m) | *Описание* |
| [`InObject`](#InObject-m) | *Описание* |
| [`IsObjectInArea`](#IsObjectInArea-m) | *Описание* |
| [`Prepare`](#Prepare-m) | *Описание* |
| [`RectangleObject`](#RectangleObject-m) | *Описание* |
| [`x9Yyrp3RfkGdCbNTXU4b`](#x9Yyrp3RfkGdCbNTXU4b-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`RectInfo`](#RectInfo-p) | *Описание* |
| [`Rectangle;`](#Rectangle;-p) | *Описание* |
| [`cTQ3RQ5sOeg;`](#cTQ3RQ5sOeg;-p) | *Описание* |
| [`mrI3RMYxIFC;`](#mrI3RMYxIFC;-p) | *Описание* |
| [`mtO3Rj6ZJ6t;`](#mtO3Rj6ZJ6t;-p) | *Описание* |
| [`qX73RVVvfB0;`](#qX73RVVvfB0;-p) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](#xsuJlZ3bylFkXacpNF53-p) | *Описание* |





***  
***  
# Методы

## `Draw`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`System` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `DrawControlPoints`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void DrawControlPoints(DxVisualQueue visual)
```

***  

## `ExtraPointChanged`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ExtraPointChanged(int index, ObjectPoint op)
```

`index` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`op` <mark style="color:red;">*`ObjectPoint`*</mark>  
 *Описание*  


***  

## `GetControlPoint`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override int GetControlPoint(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `GetExtraPoint`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override int GetExtraPoint(int x, int y)
```

***  

## `GetMinDist`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override int GetMinDist(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `InObject`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```

***  

## `IsObjectInArea`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool IsObjectInArea()
```

***  

## `Prepare`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Prepare()
```

***  

## `RectangleObject`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RectangleObject()
```

***  

## `x9Yyrp3RfkGdCbNTXU4b`<a href="x9Yyrp3RfkGdCbNTXU4b-m" id="x9Yyrp3RfkGdCbNTXU4b-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public x9Yyrp3RfkGdCbNTXU4b()
```

***  
***  
 ***  
# Свойства

## `RectInfo`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RectangleObject.x9Yyrp3RfkGdCbNTXU4b RectInfo { get; private set; }
```  
***

## `Rectangle;`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Rect Rectangle; {}
```  
***

## `cTQ3RQ5sOeg;`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Point cTQ3RQ5sOeg; {}
```  
***

## `mrI3RMYxIFC;`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Point mrI3RMYxIFC; {}
```  
***

## `mtO3Rj6ZJ6t;`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Point mtO3Rj6ZJ6t; {}
```  
***

## `qX73RVVvfB0;`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Point qX73RVVvfB0; {}
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

