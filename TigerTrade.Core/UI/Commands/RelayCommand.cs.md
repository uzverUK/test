
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[UI](../../../TigerTrade.Core/UI.md).[Commands](../../../TigerTrade.Core/UI/Commands.md)


Описание

### Синтаксис
```csharp
public sealed class RelayCommand : ICommand
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CanExecute`](#method-canexecute) | *Описание* |
| [`Execute`](#method-execute) | *Описание* |
| [`RelayCommand`](#method-relaycommand) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`CanExecuteChanged`](#event-canexecutechanged) | *Описание* |





***  
***  
# Методы

## `CanExecute`<a href="method-canexecute" id="method-canexecute"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CanExecute(object parameter)
```

`parameter` <mark style="color:red;">*`object`*</mark>  
 *Описание*  


***  

## `Execute`<a href="method-execute" id="method-execute"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Execute(object parameter)
```

***  

## `RelayCommand`<a href="method-relaycommand" id="method-relaycommand"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RelayCommand(Action<object> execute)
```

***  

## `RelayCommand`<a href="method-relaycommand" id="method-relaycommand"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RelayCommand(Action<object> execute)
public RelayCommand(Action<object> execute, Predicate<object> canExecute)
```

***  
***  
 ***  
# События

## `CanExecuteChanged`<a href="event-canexecutechanged" id="event-canexecutechanged"></a>
Описание

```csharp
public event EventHandler CanExecuteChanged
```

