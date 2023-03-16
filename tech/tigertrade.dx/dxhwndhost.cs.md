# DxHwndHost

`namespace` [TigerTrade.Dx](./)

\===

#### Синтаксис

```csharp
public sealed class DxHwndHost : DxHwndHostBase
```

## Список методов

| Название                                                                   | Описание |
| -------------------------------------------------------------------------- | -------- |
| [`Dispose`](dxhwndhost.cs.md#method-dispose)                               | _===_    |
| [`DxHwndHost`](dxhwndhost.cs.md#method-dxhwndhost)                         | _===_    |
| [`InvalidateSecondVisual`](dxhwndhost.cs.md#method-invalidatesecondvisual) | _===_    |
| [`InvalidateVisual`](dxhwndhost.cs.md#method-invalidatevisual)             | _===_    |
| [`OnPaintBackground`](dxhwndhost.cs.md#method-onpaintbackground)           | _===_    |
| [`OnRenderSizeChanged`](dxhwndhost.cs.md#method-onrendersizechanged)       | _===_    |
| [`Render`](dxhwndhost.cs.md#method-render)                                 | _===_    |
| [`StartTimer`](dxhwndhost.cs.md#method-starttimer)                         | _===_    |

## Список свойств

| Название                                             | Описание |
| ---------------------------------------------------- | -------- |
| [`ClientRect`](dxhwndhost.cs.md#property-clientrect) | _===_    |
| [`IsDisposed`](dxhwndhost.cs.md#property-isdisposed) | _===_    |
| [`WaitRedraw`](dxhwndhost.cs.md#property-waitredraw) | _===_    |

## Список событий

| Название                                                    | Описание |
| ----------------------------------------------------------- | -------- |
| [`OnRenderVisual;`](dxhwndhost.cs.md#event-onrendervisual;) | _===_    |
| [`OnTimerTick`](dxhwndhost.cs.md#event-ontimertick)         | _===_    |

***

***

## Методы

### `Dispose` <a href="#method-dispose" id="method-dispose"></a>

\===

```csharp
protected override void Dispose(bool disposing)
```

`disposing` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `DxHwndHost` <a href="#method-dxhwndhost" id="method-dxhwndhost"></a>

\===

```csharp
public DxHwndHost()
```

***

### `InvalidateSecondVisual` <a href="#method-invalidatesecondvisual" id="method-invalidatesecondvisual"></a>

\===

```csharp
public void InvalidateSecondVisual()
```

***

### `InvalidateVisual` <a href="#method-invalidatevisual" id="method-invalidatevisual"></a>

\===

```csharp
public void InvalidateVisual(bool full = false)
```

`full` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `OnPaintBackground` <a href="#method-onpaintbackground" id="method-onpaintbackground"></a>

\===

```csharp
protected override void OnPaintBackground()
```

***

### `OnRenderSizeChanged` <a href="#method-onrendersizechanged" id="method-onrendersizechanged"></a>

\===

```csharp
protected override void OnRenderSizeChanged(SizeChangedInfo sizeInfo)
```

`sizeInfo` _<mark style="color:red;">`SizeChangedInfo`</mark>_\
_===_

***

### `Render` <a href="#method-render" id="method-render"></a>

\===

```csharp
public void Render(DxVisualQueue queue1, DxVisualQueue queue2)
```

`queue1` _<mark style="color:red;">`DxVisualQueue`</mark>_\
_===_

`queue2` _<mark style="color:red;">`DxVisualQueue`</mark>_\
_===_

***

### `StartTimer` <a href="#method-starttimer" id="method-starttimer"></a>

\===

```csharp
public void StartTimer(int interval)
```

`interval` _<mark style="color:red;">`int`</mark>_\
_===_

`DispatcherTimer` _<mark style="color:red;">`new`</mark>_\
_===_

***

***

***

## Свойства

### `ClientRect` <a href="#property-clientrect" id="property-clientrect"></a>

\===

```csharp
public Rect ClientRect { get; private set; }
```

***

### `IsDisposed` <a href="#property-isdisposed" id="property-isdisposed"></a>

\===

```csharp
public bool IsDisposed { get; private set; }
```

***

### `WaitRedraw` <a href="#property-waitredraw" id="property-waitredraw"></a>

\===

```csharp
public bool WaitRedraw { get; set; }
```

***

***

***

## События

### `OnRenderVisual;` <a href="#event-onrendervisual" id="event-onrendervisual"></a>

\===

```csharp
public event Action<bool> OnRenderVisual;
```

### `OnTimerTick` <a href="#event-ontimertick" id="event-ontimertick"></a>

\===

```csharp
public event Action OnTimerTick
```
