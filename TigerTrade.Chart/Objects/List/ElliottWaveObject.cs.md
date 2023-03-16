
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public abstract class ElliottWaveObject : LineObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopyTemplate`](#CopyTemplate-m) | *Описание* |
| [`Draw`](#Draw-m) | *Описание* |
| [`ElliottWaveObject`](#ElliottWaveObject-m) | *Описание* |
| [`GetDegreeText`](#GetDegreeText-m) | *Описание* |
| [`InObject`](#InObject-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Degree`](#Degree-p) | *Описание* |
| [`ShowWave`](#ShowWave-p) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](#xsuJlZ3bylFkXacpNF53-p) | *Описание* |





***  
***  
# Методы

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

## `ElliottWaveObject`<a href="InObject-m" id="InObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected ElliottWaveObject()
```

***  

## `GetDegreeText`<a href="InObject-m" id="InObject-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected abstract string GetDegreeText(int num)
```

`num` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


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

## `Degree`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ElliottWaveDegree Degree { get; set; }
```  
***

## `ShowWave`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowWave { get; set; }
```  
***

## `xsuJlZ3bylFkXacpNF53`<a href="xsuJlZ3bylFkXacpNF53-p" id="xsuJlZ3bylFkXacpNF53-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```  
***

