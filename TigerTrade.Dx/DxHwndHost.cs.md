
`namespace` [TigerTrade.Dx](../TigerTrade.Dx.md)


Описание

### Синтаксис
```csharp
public sealed class DxHwndHost : DxHwndHostBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Dispose`](#Dispose-m) | *Описание* |
| [`DxHwndHost`](#DxHwndHost-m) | *Описание* |
| [`InvalidateSecondVisual`](#InvalidateSecondVisual-m) | *Описание* |
| [`InvalidateVisual`](#InvalidateVisual-m) | *Описание* |
| [`OnPaintBackground`](#OnPaintBackground-m) | *Описание* |
| [`OnRenderSizeChanged`](#OnRenderSizeChanged-m) | *Описание* |
| [`Render`](#Render-m) | *Описание* |
| [`StartTimer`](#StartTimer-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ClientRect`](#ClientRect-p) | *Описание* |
| [`IsDisposed`](#IsDisposed-p) | *Описание* |
| [`WaitRedraw`](#WaitRedraw-p) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`OnRenderVisual;`](#OnRenderVisual;-p) | *Описание* |
| [`OnTimerTick`](#OnTimerTick-p) | *Описание* |





***  
***  
# Методы

## `Dispose`<a href="Dispose-m" id="Dispose-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Dispose(bool disposing)
```

`disposing` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `DxHwndHost`<a href="DxHwndHost-m" id="DxHwndHost-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DxHwndHost()
```

***  

## `InvalidateSecondVisual`<a href="InvalidateSecondVisual-m" id="InvalidateSecondVisual-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InvalidateSecondVisual()
```

***  

## `InvalidateVisual`<a href="InvalidateVisual-m" id="InvalidateVisual-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InvalidateVisual(bool full = false)
```

`full` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `OnPaintBackground`<a href="OnPaintBackground-m" id="OnPaintBackground-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void OnPaintBackground()
```

***  

## `OnRenderSizeChanged`<a href="OnRenderSizeChanged-m" id="OnRenderSizeChanged-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void OnRenderSizeChanged(SizeChangedInfo sizeInfo)
```

`sizeInfo` <mark style="color:red;">*`SizeChangedInfo`*</mark>  
 *Описание*  


***  

## `Render`<a href="Render-m" id="Render-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Render(DxVisualQueue queue1, DxVisualQueue queue2)
```
`queue1` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`queue2` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `StartTimer`<a href="StartTimer-m" id="StartTimer-m"></a>
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

## `ClientRect`<a href="ClientRect-p" id="ClientRect-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Rect ClientRect { get; private set; }
```  
***

## `IsDisposed`<a href="IsDisposed-p" id="IsDisposed-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsDisposed { get; private set; }
```  
***

## `WaitRedraw`<a href="WaitRedraw-p" id="WaitRedraw-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool WaitRedraw { get; set; }
```  
***
***  
 ***  
# События

## `OnRenderVisual;`<a href="OnRenderVisual;-p" id="OnRenderVisual;-p"></a>
Описание

```csharp
public event Action<bool> OnRenderVisual;
```

## `OnTimerTick`<a href="OnTimerTick-p" id="OnTimerTick-p"></a>
Описание

```csharp
public event Action OnTimerTick
```

