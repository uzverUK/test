
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class LineGroupObjectBaseEx : LineGroupObjectBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CopyTemplate`](#CopyTemplate-m) | *Описание* |
| [`LineGroupObjectBaseEx`](#LineGroupObjectBaseEx-m) | *Описание* |
| [`OpenStartEnd`](#OpenStartEnd-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`OpenEnd`](#OpenEnd-p) | *Описание* |
| [`OpenStart`](#OpenStart-p) | *Описание* |





***  
***  
# Методы

## `CopyTemplate`<a href="OpenStartEnd-m" id="OpenStartEnd-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `LineGroupObjectBaseEx`<a href="OpenStartEnd-m" id="OpenStartEnd-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected LineGroupObjectBaseEx()
```

***  

## `OpenStartEnd`<a href="OpenStartEnd-m" id="OpenStartEnd-m"></a>
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

## `OpenEnd`<a href="OpenStart-p" id="OpenStart-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenEnd { get; set; }
```  
***

## `OpenStart`<a href="OpenStart-p" id="OpenStart-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenStart { get; set; }
```  
***

