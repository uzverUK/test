
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

## `Dispose`<a href="StartTimer-m" id="StartTimer-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Dispose(bool disposing)
```

`disposing` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `DxHwndHost`<a href="StartTimer-m" id="StartTimer-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DxHwndHost()
```

***  

## `InvalidateSecondVisual`<a href="StartTimer-m" id="StartTimer-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InvalidateSecondVisual()
```

***  

## `InvalidateVisual`<a href="StartTimer-m" id="StartTimer-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InvalidateVisual(bool full = false)
```

`full` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `OnPaintBackground`<a href="StartTimer-m" id="StartTimer-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void OnPaintBackground()
```

***  

## `OnRenderSizeChanged`<a href="StartTimer-m" id="StartTimer-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void OnRenderSizeChanged(SizeChangedInfo sizeInfo)
```

`sizeInfo` <mark style="color:red;">*`SizeChangedInfo`*</mark>  
 *Описание*  


***  

## `Render`<a href="StartTimer-m" id="StartTimer-m"></a>
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

## `ClientRect`<a href="WaitRedraw-p" id="WaitRedraw-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Rect ClientRect { get; private set; }
```  
***

## `IsDisposed`<a href="WaitRedraw-p" id="WaitRedraw-p"></a>
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

## `OnRenderVisual;`<a href="OnTimerTick-p" id="OnTimerTick-p"></a>
Описание

```csharp
public event Action<bool> OnRenderVisual;
```

## `OnTimerTick`<a href="OnTimerTick-p" id="OnTimerTick-p"></a>
Описание

```csharp
public event Action OnTimerTick
```

