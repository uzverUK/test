
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[UI](../../../TigerTrade.Core/UI.md).[Commands](../../../TigerTrade.Core/UI/Commands.md)


Описание

### Синтаксис
```csharp
public sealed class RelayCommand : ICommand
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CanExecute`](./RelayCommand.cs/Методы/CanExecute.md) | *Описание* |
| [`Execute`](./RelayCommand.cs/Методы/Execute.md) | *Описание* |
| [`RelayCommand`](./RelayCommand.cs/Методы/RelayCommand.md) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`CanExecuteChanged`](./RelayCommand.cs/События/CanExecuteChanged.md) | *Описание* |





***  
***  
# Методы

## `CanExecute<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CanExecute(object parameter)
```

`parameter` <mark style="color:red;">*`object`*</mark>  
 *Описание*  


***  

## `Execute<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Execute(object parameter)
```

***  

## `RelayCommand<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RelayCommand(Action<object> execute)
```

***  

## `RelayCommand<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RelayCommand(Action<object> execute)
public RelayCommand(Action<object> execute, Predicate<object> canExecute)
```

***  
***  
 ***  
# События

## `CanExecuteChanged`
Описание

```csharp
public event EventHandler CanExecuteChanged
```

