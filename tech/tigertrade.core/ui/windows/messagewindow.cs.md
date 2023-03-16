# MessageWindow

`namespace` [TigerTrade.Core](../../).[UI](../).[Windows](./)

\===

#### Синтаксис

```csharp
public sealed class MessageWindow : Window, IComponentConnector
```

## Список методов

| Название                                                                | Описание |
| ----------------------------------------------------------------------- | -------- |
| [`InitializeComponent`](messagewindow.cs.md#method-initializecomponent) | _===_    |
| [`MessageWindow`](messagewindow.cs.md#method-messagewindow)             | _===_    |
| [`ShowWindow`](messagewindow.cs.md#method-showwindow)                   | _===_    |

## Список свойств

| Название                                          | Описание |
| ------------------------------------------------- | -------- |
| [`Message`](messagewindow.cs.md#property-message) | _===_    |

***

***

## Методы

### `InitializeComponent` <a href="#method-initializecomponent" id="method-initializecomponent"></a>

\===

```csharp
public void InitializeComponent()
```

***

### `MessageWindow` <a href="#method-messagewindow" id="method-messagewindow"></a>

\===

```csharp
public MessageWindow()
```

***

### `ShowWindow` <a href="#method-showwindow" id="method-showwindow"></a>

\===

```csharp
public static bool ShowWindow(Window owner, string title, string message)
```

`owner` _<mark style="color:red;">`Window`</mark>_\
_===_

`title` _<mark style="color:red;">`string`</mark>_\
_===_

`message` _<mark style="color:red;">`string`</mark>_\
_===_

***

***

***

## Свойства

### `Message` <a href="#property-message" id="property-message"></a>

\===

```csharp
public string Message { get; set; }
```

***
