
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class LineGroupObjectBase : LineObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CalcPoint`](./LineGroupObjectBase.cs/Методы/CalcPoint.md) | *Описание* |
| [`Draw`](./LineGroupObjectBase.cs/Методы/Draw.md) | *Описание* |
| [`InObject`](./LineGroupObjectBase.cs/Методы/InObject.md) | *Описание* |
| [`LineGroupObjectBase`](./LineGroupObjectBase.cs/Методы/LineGroupObjectBase.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`EndPoints;`](./LineGroupObjectBase.cs/Свойства/EndPoints;.md) | *Описание* |
| [`StartPoints;`](./LineGroupObjectBase.cs/Свойства/StartPoints;.md) | *Описание* |





# Методы

## *CalcPoint*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void CalcPoint()
```


## *Draw*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```

<mark style="color:yellow;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

<mark style="color:yellow;">`List`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  



## *InObject*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *LineGroupObjectBase*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected LineGroupObjectBase()
```

# Свойства

## *EndPoints;*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] EndPoints; {}
```

## *StartPoints;*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] StartPoints; {}
```

