# YesNoWindow

`namespace` [TigerTrade.Core](../../).[UI](../).[Windows](./)

\===

#### Синтаксис

```csharp
public sealed class YesNoWindow : Window, IComponentConnector
```

## Список методов

| Название                                                              | Описание |
| --------------------------------------------------------------------- | -------- |
| [`InitializeComponent`](yesnowindow.cs.md#method-initializecomponent) | _===_    |
| [`ShowWindow`](yesnowindow.cs.md#method-showwindow)                   | _===_    |
| [`YesNoWindow`](yesnowindow.cs.md#method-yesnowindow)                 | _===_    |

## Список свойств

| Название                                        | Описание |
| ----------------------------------------------- | -------- |
| [`Message`](yesnowindow.cs.md#property-message) | _===_    |

***

***

## Методы

### `InitializeComponent` <a href="#method-initializecomponent" id="method-initializecomponent"></a>

\===

```csharp
public void InitializeComponent()
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

### `YesNoWindow` <a href="#method-yesnowindow" id="method-yesnowindow"></a>

\===

```csharp
public YesNoWindow()
```

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
