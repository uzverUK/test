
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class LineGroupObjectBase : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CalcPoint`](#CalcPoint-m) | *Описание* |
| [`Draw`](#Draw-m) | *Описание* |
| [`InObject`](#InObject-m) | *Описание* |
| [`LineGroupObjectBase`](#LineGroupObjectBase-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`EndPoints;`](#EndPoints;-p) | *Описание* |
| [`StartPoints;`](#StartPoints;-p) | *Описание* |





***  
***  
# Методы

## `CalcPoint`<a href="LineGroupObjectBase-m" id="LineGroupObjectBase-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected virtual void CalcPoint()
```

***  

## `Draw`<a href="LineGroupObjectBase-m" id="LineGroupObjectBase-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref List<ObjectLabelInfo> labels)
```

`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`List` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***  

## `InObject`<a href="LineGroupObjectBase-m" id="LineGroupObjectBase-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***  

## `LineGroupObjectBase`<a href="LineGroupObjectBase-m" id="LineGroupObjectBase-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected LineGroupObjectBase()
```

***  
***  
 ***  
# Свойства

## `EndPoints;`<a href="StartPoints;-p" id="StartPoints;-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] EndPoints; {}
```  
***

## `StartPoints;`<a href="StartPoints;-p" id="StartPoints;-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected Point[] StartPoints; {}
```  
***

