
`namespace` [TigerTrade.Dx](../TigerTrade.Dx.md)


Описание

### Синтаксис
```csharp
public sealed class DxHwndHost : DxHwndHostBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Dispose`](#method-dispose) | *Описание* |
| [`DxHwndHost`](#method-dxhwndhost) | *Описание* |
| [`InvalidateSecondVisual`](#method-invalidatesecondvisual) | *Описание* |
| [`InvalidateVisual`](#method-invalidatevisual) | *Описание* |
| [`OnPaintBackground`](#method-onpaintbackground) | *Описание* |
| [`OnRenderSizeChanged`](#method-onrendersizechanged) | *Описание* |
| [`Render`](#method-render) | *Описание* |
| [`StartTimer`](#method-starttimer) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ClientRect`](#property-clientrect) | *Описание* |
| [`IsDisposed`](#property-isdisposed) | *Описание* |
| [`WaitRedraw`](#property-waitredraw) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`OnRenderVisual;`](#event-onrendervisual;) | *Описание* |
| [`OnTimerTick`](#event-ontimertick) | *Описание* |





***  
***  
# Методы

## `Dispose`<a href="method-dispose" id="method-dispose"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void Dispose(bool disposing)
```

`disposing` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `DxHwndHost`<a href="method-dxhwndhost" id="method-dxhwndhost"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DxHwndHost()
```

***  

## `InvalidateSecondVisual`<a href="method-invalidatesecondvisual" id="method-invalidatesecondvisual"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InvalidateSecondVisual()
```

***  

## `InvalidateVisual`<a href="method-invalidatevisual" id="method-invalidatevisual"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InvalidateVisual(bool full = false)
```

`full` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `OnPaintBackground`<a href="method-onpaintbackground" id="method-onpaintbackground"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void OnPaintBackground()
```

***  

## `OnRenderSizeChanged`<a href="method-onrendersizechanged" id="method-onrendersizechanged"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
protected override void OnRenderSizeChanged(SizeChangedInfo sizeInfo)
```

`sizeInfo` <mark style="color:red;">*`SizeChangedInfo`*</mark>  
 *Описание*  


***  

## `Render`<a href="method-render" id="method-render"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Render(DxVisualQueue queue1, DxVisualQueue queue2)
```
`queue1` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  

`queue2` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *Описание*  


***  

## `StartTimer`<a href="method-starttimer" id="method-starttimer"></a>
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

## `ClientRect`<a href="property-clientrect" id="property-clientrect"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public Rect ClientRect { get; private set; }
```  
***

## `IsDisposed`<a href="property-isdisposed" id="property-isdisposed"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsDisposed { get; private set; }
```  
***

## `WaitRedraw`<a href="property-waitredraw" id="property-waitredraw"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool WaitRedraw { get; set; }
```  
***
***  
 ***  
# События

## `OnRenderVisual;`<a href="event-onrendervisual;" id="event-onrendervisual;"></a>
Описание

```csharp
public event Action<bool> OnRenderVisual;
```

## `OnTimerTick`<a href="event-ontimertick" id="event-ontimertick"></a>
Описание

```csharp
public event Action OnTimerTick
```

