
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public abstract class ElliottWaveObject : LineObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopyTemplate`](./ElliottWaveObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./ElliottWaveObject.cs/Методы/Draw.md) | *Описание* |
| [`ElliottWaveObject`](./ElliottWaveObject.cs/Методы/ElliottWaveObject.md) | *Описание* |
| [`GetDegreeText`](./ElliottWaveObject.cs/Методы/GetDegreeText.md) | *Описание* |
| [`InObject`](./ElliottWaveObject.cs/Методы/InObject.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Degree`](./ElliottWaveObject.cs/Свойства/Degree.md) | *Описание* |
| [`ShowWave`](./ElliottWaveObject.cs/Свойства/ShowWave.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./ElliottWaveObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |





# Методы

## *CopyTemplate*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

<mark style="color:purple;">`objectBase`</mark> <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

<mark style="color:purple;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *Draw*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
<mark style="color:purple;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

<mark style="color:purple;">`System`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  



## *ElliottWaveObject*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected ElliottWaveObject()
```


## *GetDegreeText*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract string GetDegreeText(int num)
```

<mark style="color:purple;">`num`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## *InObject*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```
<mark style="color:purple;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:purple;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


# Свойства

## *Degree*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ElliottWaveDegree Degree { get; set; }
```

## *ShowWave*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowWave { get; set; }
```

## *xsuJlZ3bylFkXacpNF53*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

