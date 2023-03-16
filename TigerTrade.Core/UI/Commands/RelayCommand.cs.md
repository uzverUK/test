
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[UI](../../../TigerTrade.Core/UI.md).[Commands](../../../TigerTrade.Core/UI/Commands.md)


===

### Синтаксис
```csharp
public sealed class RelayCommand : ICommand
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CanExecute`](#method-canexecute) | *===* |
| [`Execute`](#method-execute) | *===* |
| [`RelayCommand`](#method-relaycommand) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`CanExecuteChanged`](#event-canexecutechanged) | *===* |





***  
***  
# Методы

## `CanExecute`<a href="method-canexecute" id="method-canexecute"></a>
===
```csharp
public bool CanExecute(object parameter)
```

`parameter` <mark style="color:red;">*`object`*</mark>  
 *===*  


***  

## `Execute`<a href="method-execute" id="method-execute"></a>
===
```csharp
public void Execute(object parameter)
```

***  

## `RelayCommand`<a href="method-relaycommand" id="method-relaycommand"></a>
===
```csharp
public RelayCommand(Action<object> execute)
```

***  

## `RelayCommand`<a href="method-relaycommand" id="method-relaycommand"></a>
===
```csharp
public RelayCommand(Action<object> execute)
public RelayCommand(Action<object> execute, Predicate<object> canExecute)
```

***  
***  
 ***  
# События

## `CanExecuteChanged`<a href="event-canexecutechanged" id="event-canexecutechanged"></a>
===

```csharp
public event EventHandler CanExecuteChanged
```

