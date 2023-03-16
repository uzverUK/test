
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class LineGroupObjectBase : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CalcPoint`](#method-calcpoint) | *Описание* |
| [`Draw`](#method-draw) | *Описание* |
| [`InObject`](#method-inobject) | *Описание* |
| [`LineGroupObjectBase`](#method-linegroupobjectbase) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`EndPoints;`](#property-endpoints;) | *Описание* |
| [`StartPoints;`](#property-startpoints;) | *Описание* |





***  
***  
# Методы

## `CalcPoint`<a href="method-calcpoint" id="method-calcpoint"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void CalcPoint()
```

***  

## `Draw`<a href="method-draw" id="method-draw"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`List` <mark style="color:red;">*`ref`*</mark>  
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

## `LineGroupObjectBase`<a href="method-linegroupobjectbase" id="method-linegroupobjectbase"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected LineGroupObjectBase()
```

***  
***  
 ***  
# Свойства

## `EndPoints;`<a href="property-endpoints;" id="property-endpoints;"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] EndPoints; {}
```  
***

## `StartPoints;`<a href="property-startpoints;" id="property-startpoints;"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] StartPoints; {}
```  
***

