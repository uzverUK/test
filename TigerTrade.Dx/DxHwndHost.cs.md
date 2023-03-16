
`namespace` [TigerTrade.Dx](../TigerTrade.Dx.md)


Описание

### Синтаксис
```csharp
public sealed class DxHwndHost : DxHwndHostBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Dispose`](./DxHwndHost.cs/Методы/Dispose.md) | *Описание* |
| [`DxHwndHost`](./DxHwndHost.cs/Методы/DxHwndHost.md) | *Описание* |
| [`InvalidateSecondVisual`](./DxHwndHost.cs/Методы/InvalidateSecondVisual.md) | *Описание* |
| [`InvalidateVisual`](./DxHwndHost.cs/Методы/InvalidateVisual.md) | *Описание* |
| [`OnPaintBackground`](./DxHwndHost.cs/Методы/OnPaintBackground.md) | *Описание* |
| [`OnRenderSizeChanged`](./DxHwndHost.cs/Методы/OnRenderSizeChanged.md) | *Описание* |
| [`Render`](./DxHwndHost.cs/Методы/Render.md) | *Описание* |
| [`StartTimer`](./DxHwndHost.cs/Методы/StartTimer.md) | *Описание* |

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

## `Dispose`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Dispose(bool disposing)
```

`disposing` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `DxHwndHost`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DxHwndHost()
```

***  

## `InvalidateSecondVisual`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InvalidateSecondVisual()
```

***  

## `InvalidateVisual`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InvalidateVisual(bool full = false)
```

`full` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `OnPaintBackground`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void OnPaintBackground()
```

***  

## `OnRenderSizeChanged`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void OnRenderSizeChanged(SizeChangedInfo sizeInfo)
```

`sizeInfo` <mark style="color:red;">*`SizeChangedInfo`*</mark>  
 *Описание*  


***  

## `Render`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Render(DxVisualQueue queue1, DxVisualQueue queue2)
```
`queue1` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`queue2` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `StartTimer`
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

