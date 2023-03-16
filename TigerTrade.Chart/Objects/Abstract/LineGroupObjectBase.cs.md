
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class LineGroupObjectBase : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CalcPoint`](./LineGroupObjectBase.cs/Методы/CalcPoint.md) | *Описание* |
| [`Draw`](./LineGroupObjectBase.cs/Методы/Draw.md) | *Описание* |
| [`InObject`](./LineGroupObjectBase.cs/Методы/InObject.md) | *Описание* |
| [`LineGroupObjectBase`](./LineGroupObjectBase.cs/Методы/LineGroupObjectBase.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`EndPoints;`](./LineGroupObjectBase.cs/Свойства/EndPoints;.md) | *Описание* |
| [`StartPoints;`](./LineGroupObjectBase.cs/Свойства/StartPoints;.md) | *Описание* |





***  
***  
# Методы

## `CalcPoint<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void CalcPoint()
```

***  

## `Draw<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `InObject<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `LineGroupObjectBase<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected LineGroupObjectBase()
```

***  
***  
 ***  
# Свойства

## `EndPoints;`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] EndPoints; {}
```  
***

## `StartPoints;`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] StartPoints; {}
```  
***

