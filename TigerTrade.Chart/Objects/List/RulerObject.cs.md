
`namespace` [TigerTrade.Chart](../../../TigerTrade.Chart.md).[Objects](../../../TigerTrade.Chart/Objects.md).[List](../../../TigerTrade.Chart/Objects/List.md)


Описание

### Синтаксис
```csharp
public sealed class RulerObject : LineObjectBase
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ApplyTheme`](./RulerObject.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./RulerObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`Draw`](./RulerObject.cs/Методы/Draw.md) | *Описание* |
| [`InObject`](./RulerObject.cs/Методы/InObject.md) | *Описание* |
| [`PrettyFormatTimeSpan`](./RulerObject.cs/Методы/PrettyFormatTimeSpan.md) | *Описание* |
| [`RulerObject`](./RulerObject.cs/Методы/RulerObject.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`ShowInfoAsk`](./RulerObject.cs/Свойства/ShowInfoAsk.md) | *Описание* |
| [`ShowInfoBars`](./RulerObject.cs/Свойства/ShowInfoBars.md) | *Описание* |
| [`ShowInfoBid`](./RulerObject.cs/Свойства/ShowInfoBid.md) | *Описание* |
| [`ShowInfoChange`](./RulerObject.cs/Свойства/ShowInfoChange.md) | *Описание* |
| [`ShowInfoDelta`](./RulerObject.cs/Свойства/ShowInfoDelta.md) | *Описание* |
| [`ShowInfoPrice`](./RulerObject.cs/Свойства/ShowInfoPrice.md) | *Описание* |
| [`ShowInfoTicks`](./RulerObject.cs/Свойства/ShowInfoTicks.md) | *Описание* |
| [`ShowInfoTime`](./RulerObject.cs/Свойства/ShowInfoTime.md) | *Описание* |
| [`ShowInfoTrades`](./RulerObject.cs/Свойства/ShowInfoTrades.md) | *Описание* |
| [`ShowInfoVolume`](./RulerObject.cs/Свойства/ShowInfoVolume.md) | *Описание* |
| [`TextColor`](./RulerObject.cs/Свойства/TextColor.md) | *Описание* |
| [`xsuJlZ3bylFkXacpNF53`](./RulerObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |





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



## `InObject`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override bool InObject(int x, int y)
```
`x` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`y` <mark style="color:red;">*`int`*</mark>  
 *Описание*  



## `PrettyFormatTimeSpan`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string PrettyFormatTimeSpan(TimeSpan span)
```
`span` <mark style="color:red;">*`TimeSpan`*</mark>  
 *Описание*  



## `RulerObject`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RulerObject()
```

# Свойства

## `ShowInfoAsk`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoAsk { get; set; }
```

## `ShowInfoBars`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoBars { get; set; }
```

## `ShowInfoBid`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoBid { get; set; }
```

## `ShowInfoChange`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoChange { get; set; }
```

## `ShowInfoDelta`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoDelta { get; set; }
```

## `ShowInfoPrice`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoPrice { get; set; }
```

## `ShowInfoTicks`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoTicks { get; set; }
```

## `ShowInfoTime`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoTime { get; set; }
```

## `ShowInfoTrades`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoTrades { get; set; }
```

## `ShowInfoVolume`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowInfoVolume { get; set; }
```

## `TextColor`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public XColor TextColor { get; set; }
```

## `xsuJlZ3bylFkXacpNF53`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override xsuJlZ3bylFkXacpNF53 ChartDataType { get; }
```

