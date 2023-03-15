
# public abstract class ElliottWaveObject : LineObjectBase
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)



Описаниеt

### Синтаксис
```csharp
public abstract class ElliottWaveObject : LineObjectBase
```


### Таблица методов
| Название | Описание |
| --- | --- |
| [`CopyTemplate`](./ElliottWaveObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./ElliottWaveObject.cs/Методы/Draw.md) | *Описание* |
| [`ElliottWaveObject`](./ElliottWaveObject.cs/Методы/ElliottWaveObject.md) | *Описание* |
| [`GetDegreeText`](./ElliottWaveObject.cs/Методы/GetDegreeText.md) | *Описание* |
| [`InObject`](./ElliottWaveObject.cs/Методы/InObject.md) | *Описание* |

### Свойства
| Название | Описание |
| --- | --- |
| [`Degree`](./ElliottWaveObject.cs/Свойства/Degree.md) | *Описание* |
| [`ShowWave`](./ElliottWaveObject.cs/Свойства/ShowWave.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./ElliottWaveObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |




            ***
  ***
  # Методы

## CopyTemplate
Описание

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

<mark style="color:yellow;">`objectBase`</mark> <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***                

## Draw
Описание

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
<mark style="color:yellow;">`visual`</mark> <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

<mark style="color:yellow;">`System`</mark> <mark style="color:red;">*`ref`*</mark>  
 *Описание*  


***                

## ElliottWaveObject
Описание

```csharp
protected ElliottWaveObject()
```

***                

## GetDegreeText
Описание

```csharp
protected abstract string GetDegreeText(int num)
```

<mark style="color:yellow;">`num`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                

## InObject
Описание

```csharp
protected override bool InObject(int x, int y)
```
<mark style="color:yellow;">`x`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  

<mark style="color:yellow;">`y`</mark> <mark style="color:red;">*`int`*</mark>  
 *Описание*  


***                
                ***
  ***
  # Свойства

## Degree
Описание

```csharp
public ElliottWaveDegree Degree { get; set; }
```
***

## ShowWave
Описание

```csharp
public bool ShowWave { get; set; }
```
***

## xsuJlZ3bylFkXacpNF53
Описание

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```
***

