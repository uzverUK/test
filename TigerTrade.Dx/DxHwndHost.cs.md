
`namespace` [TigerTrade.Dx](../TigerTrade.Dx.md)


===

### Синтаксис
```csharp
public sealed class DxHwndHost : DxHwndHostBase
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Dispose`](#method-dispose) | *===* |
| [`DxHwndHost`](#method-dxhwndhost) | *===* |
| [`InvalidateSecondVisual`](#method-invalidatesecondvisual) | *===* |
| [`InvalidateVisual`](#method-invalidatevisual) | *===* |
| [`OnPaintBackground`](#method-onpaintbackground) | *===* |
| [`OnRenderSizeChanged`](#method-onrendersizechanged) | *===* |
| [`Render`](#method-render) | *===* |
| [`StartTimer`](#method-starttimer) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`ClientRect`](#property-clientrect) | *===* |
| [`IsDisposed`](#property-isdisposed) | *===* |
| [`WaitRedraw`](#property-waitredraw) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`OnRenderVisual;`](#event-onrendervisual;) | *===* |
| [`OnTimerTick`](#event-ontimertick) | *===* |





***  
***  
# Методы

## `Dispose`<a href="method-dispose" id="method-dispose"></a>
===
```csharp
protected override void Dispose(bool disposing)
```

`disposing` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `DxHwndHost`<a href="method-dxhwndhost" id="method-dxhwndhost"></a>
===
```csharp
public DxHwndHost()
```

***  

## `InvalidateSecondVisual`<a href="method-invalidatesecondvisual" id="method-invalidatesecondvisual"></a>
===
```csharp
public void InvalidateSecondVisual()
```

***  

## `InvalidateVisual`<a href="method-invalidatevisual" id="method-invalidatevisual"></a>
===
```csharp
public void InvalidateVisual(bool full = false)
```

`full` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `OnPaintBackground`<a href="method-onpaintbackground" id="method-onpaintbackground"></a>
===
```csharp
protected override void OnPaintBackground()
```

***  

## `OnRenderSizeChanged`<a href="method-onrendersizechanged" id="method-onrendersizechanged"></a>
===
```csharp
protected override void OnRenderSizeChanged(SizeChangedInfo sizeInfo)
```

`sizeInfo` <mark style="color:red;">*`SizeChangedInfo`*</mark>  
 *===*  


***  

## `Render`<a href="method-render" id="method-render"></a>
===
```csharp
public void Render(DxVisualQueue queue1, DxVisualQueue queue2)
```
`queue1` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *===*  

`queue2` <mark style="color:red;">*`DxVisualQueue`*</mark>  
 *===*  


***  

## `StartTimer`<a href="method-starttimer" id="method-starttimer"></a>
===
```csharp
public void StartTimer(int interval)
```
`interval` <mark style="color:red;">*`int`*</mark>  
 *===*  

`DispatcherTimer` <mark style="color:red;">*`new`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `ClientRect`<a href="property-clientrect" id="property-clientrect"></a>
===
```csharp
public Rect ClientRect { get; private set; }
```  
***

## `IsDisposed`<a href="property-isdisposed" id="property-isdisposed"></a>
===
```csharp
public bool IsDisposed { get; private set; }
```  
***

## `WaitRedraw`<a href="property-waitredraw" id="property-waitredraw"></a>
===
```csharp
public bool WaitRedraw { get; set; }
```  
***
***  
 ***  
# События

## `OnRenderVisual;`<a href="event-onrendervisual;" id="event-onrendervisual;"></a>
===

```csharp
public event Action<bool> OnRenderVisual;
```

## `OnTimerTick`<a href="event-ontimertick" id="event-ontimertick"></a>
===

```csharp
public event Action OnTimerTick
```

