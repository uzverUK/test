
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class FibonacciExtensionsObject : LineObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./FibonacciExtensionsObject.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./FibonacciExtensionsObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./FibonacciExtensionsObject.cs/Методы/Draw.md) | *Описание* |
| [`FibonacciExtensionsObject`](./FibonacciExtensionsObject.cs/Методы/FibonacciExtensionsObject.md) | *Описание* |
| [`InObject`](./FibonacciExtensionsObject.cs/Методы/InObject.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`CustomLevels`](./FibonacciExtensionsObject.cs/Свойства/CustomLevels.md) | *Описание* |
| [`Levels`](./FibonacciExtensionsObject.cs/Свойства/Levels.md) | *Описание* |
| [`LevelsLineColor`](./FibonacciExtensionsObject.cs/Свойства/LevelsLineColor.md) | *Описание* |
| [`LevelsLineStyle`](./FibonacciExtensionsObject.cs/Свойства/LevelsLineStyle.md) | *Описание* |
| [`LevelsLineWidth`](./FibonacciExtensionsObject.cs/Свойства/LevelsLineWidth.md) | *Описание* |
| [`LevelsWidth`](./FibonacciExtensionsObject.cs/Свойства/LevelsWidth.md) | *Описание* |
| [`OpenEnd`](./FibonacciExtensionsObject.cs/Свойства/OpenEnd.md) | *Описание* |
| [`OpenStart`](./FibonacciExtensionsObject.cs/Свойства/OpenStart.md) | *Описание* |
| [`TextAlignment`](./FibonacciExtensionsObject.cs/Свойства/TextAlignment.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./FibonacciExtensionsObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |





# Методы

## `ApplyTheme`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void ApplyTheme(IChartTheme theme)
```

`theme` <mark style="color:red;">*`IChartTheme`*</mark>  
 *Описание*  



## `CopyTemplate`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override void CopyTemplate(ObjectBase objectBase, bool style)
```
`objectBase` <mark style="color:red;">*`ObjectBase`*</mark>  
 *Описание*  

`style` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  



## `Draw`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Draw(DxVisualQueue visual, ref System.Collections.Generic.List<ObjectLabelInfo> labels)
```
`visual` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`System` <mark style="color:red;">*`ref`*</mark>  
 *Описание*  



## `FibonacciExtensionsObject`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public FibonacciExtensionsObject()
```


## `InObject`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```

`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  


# Свойства

## `CustomLevels`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CustomLevels { get; set; }
```

## `Levels`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public System.Collections.Generic.List<ObjectLine> Levels { get; set; }
```

## `LevelsLineColor`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor LevelsLineColor { get; set; }
```

## `LevelsLineStyle`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XDashStyle LevelsLineStyle { get; set; }
```

## `LevelsLineWidth`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LevelsLineWidth { get; set; }
```

## `LevelsWidth`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public int LevelsWidth { get; set; }
```

## `OpenEnd`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenEnd { get; set; }
```

## `OpenStart`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool OpenStart { get; set; }
```

## `TextAlignment`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ObjectTextAlignment TextAlignment { get; set; }
```

## `xsuJlZ3bylFkXacpNF53`
> Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

