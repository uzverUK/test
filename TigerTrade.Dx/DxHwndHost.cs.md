
`namespace` [TigerTrade.Dx](../TigerTrade.Dx.md)


Описание

### Синтаксис
```csharp
public sealed class DxHwndHost : DxHwndHostBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Dispose`](#test) | *Описание* |
| [`DxHwndHost`](#test) | *Описание* |
| [`InvalidateSecondVisual`](#test) | *Описание* |
| [`InvalidateVisual`](#test) | *Описание* |
| [`OnPaintBackground`](#test) | *Описание* |
| [`OnRenderSizeChanged`](#test) | *Описание* |
| [`Render`](#test) | *Описание* |
| [`StartTimer`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ClientRect`](./DxHwndHost.cs/Свойства/ClientRect.md) | *Описание* |
| [`IsDisposed`](./DxHwndHost.cs/Свойства/IsDisposed.md) | *Описание* |
| [`WaitRedraw`](./DxHwndHost.cs/Свойства/WaitRedraw.md) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`OnRenderVisual;`](./DxHwndHost.cs/События/OnRenderVisual;.md) | *Описание* |
| [`OnTimerTick`](./DxHwndHost.cs/События/OnTimerTick.md) | *Описание* |





***  
***  
# Методы

## `Dispose`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Dispose(bool disposing)
```

`disposing` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `DxHwndHost`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DxHwndHost()
```

***  

## `InvalidateSecondVisual`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InvalidateSecondVisual()
```

***  

## `InvalidateVisual`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InvalidateVisual(bool full = false)
```

`full` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `OnPaintBackground`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void OnPaintBackground()
```

***  

## `OnRenderSizeChanged`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void OnRenderSizeChanged(SizeChangedInfo sizeInfo)
```

`sizeInfo` <mark style="color:red;">*`SizeChangedInfo`*</mark>  
 *Описание*  


***  

## `Render`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Render(DxVisualQueue queue1, DxVisualQueue queue2)
```
`queue1` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`queue2` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `StartTimer`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void StartTimer(int interval)
```
`interval` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`DispatcherTimer` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `ClientRect`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Rect ClientRect { get; private set; }
```  
***

## `IsDisposed`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsDisposed { get; private set; }
```  
***

## `WaitRedraw`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool WaitRedraw { get; set; }
```  
***
***  
 ***  
# События

## `OnRenderVisual;`
Описание

```csharp
public event Action<bool> OnRenderVisual;
```

## `OnTimerTick`
Описание

```csharp
public event Action OnTimerTick
```

