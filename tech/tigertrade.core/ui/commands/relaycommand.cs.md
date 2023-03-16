# RelayCommand

`namespace` [TigerTrade.Core](../../).[UI](../).[Commands](./)

\===

#### Синтаксис

```csharp
public sealed class RelayCommand : ICommand
```

## Список методов

| Название                                                 | Описание |
| -------------------------------------------------------- | -------- |
| [`CanExecute`](relaycommand.cs.md#method-canexecute)     | _===_    |
| [`Execute`](relaycommand.cs.md#method-execute)           | _===_    |
| [`RelayCommand`](relaycommand.cs.md#method-relaycommand) | _===_    |

## Список событий

| Название                                                          | Описание |
| ----------------------------------------------------------------- | -------- |
| [`CanExecuteChanged`](relaycommand.cs.md#event-canexecutechanged) | _===_    |

***

***

## Методы

### `CanExecute` <a href="#method-canexecute" id="method-canexecute"></a>

\===

```csharp
public bool CanExecute(object parameter)
```

`parameter` _<mark style="color:red;">`object`</mark>_\
_===_

***

### `Execute` <a href="#method-execute" id="method-execute"></a>

\===

```csharp
public void Execute(object parameter)
```

***

### `RelayCommand` <a href="#method-relaycommand" id="method-relaycommand"></a>

\===

```csharp
public RelayCommand(Action<object> execute)
```

***

### `RelayCommand` <a href="#method-relaycommand" id="method-relaycommand"></a>

\===

```csharp
public RelayCommand(Action<object> execute)
public RelayCommand(Action<object> execute, Predicate<object> canExecute)
```

***

***

***

## События

### `CanExecuteChanged` <a href="#event-canexecutechanged" id="event-canexecutechanged"></a>

\===

```csharp
public event EventHandler CanExecuteChanged
```
