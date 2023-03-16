
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class LineGroupObjectBaseEx : LineGroupObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopyTemplate`](#method-copytemplate) | *Описание* |
| [`LineGroupObjectBaseEx`](#method-linegroupobjectbaseex) | *Описание* |
| [`OpenStartEnd`](#method-openstartend) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`OpenEnd`](#property-openend) | *Описание* |
| [`OpenStart`](#property-openstart) | *Описание* |





***  
***  
# Методы

## `CopyTemplate`<a href="method-copytemplate" id="method-copytemplate"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `LineGroupObjectBaseEx`<a href="method-linegroupobjectbaseex" id="method-linegroupobjectbaseex"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected LineGroupObjectBaseEx()
```

***  

## `OpenStartEnd`<a href="method-openstartend" id="method-openstartend"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void OpenStartEnd(bool openStart, bool openEnd)
```

`openStart` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

`openEnd` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `OpenEnd`<a href="property-openend" id="property-openend"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenEnd { get; set; }
```  
***

## `OpenStart`<a href="property-openstart" id="property-openstart"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenStart { get; set; }
```  
***

