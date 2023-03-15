
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[Abstract](../../../TigerTrade.Chart/Objects/Abstract.md)


Описание

### Синтаксис
```csharp
public abstract class LineGroupObjectBaseEx : LineGroupObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`CopyTemplate`](./LineGroupObjectBaseEx.cs/Методы/CopyTemplate.md) | *Описание* |
| [`LineGroupObjectBaseEx`](./LineGroupObjectBaseEx.cs/Методы/LineGroupObjectBaseEx.md) | *Описание* |
| [`OpenStartEnd`](./LineGroupObjectBaseEx.cs/Методы/OpenStartEnd.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`OpenEnd`](./LineGroupObjectBaseEx.cs/Свойства/OpenEnd.md) | *Описание* |
| [`OpenStart`](./LineGroupObjectBaseEx.cs/Свойства/OpenStart.md) | *Описание* |





# Методы

## *CopyTemplate*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```

<mark style="color:yellow;">`objectBase`</mark> <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

<mark style="color:yellow;">`style`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## *LineGroupObjectBaseEx*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected LineGroupObjectBaseEx()
```


## *OpenStartEnd*
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected void OpenStartEnd(bool openStart, bool openEnd)
```

<mark style="color:yellow;">`openStart`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  

<mark style="color:yellow;">`openEnd`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


# Свойства

## *OpenEnd*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenEnd { get; set; }
```

## *OpenStart*
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenStart { get; set; }
```

