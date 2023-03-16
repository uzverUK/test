
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[UI](../../../TigerTrade.Core/UI.md).[Commands](../../../TigerTrade.Core/UI/Commands.md)


Описание

### Синтаксис
```csharp
public sealed class RelayCommand : ICommand
```


# Список методов
| Название | Описание |
| --- | --- |
| [`CanExecute`](#CanExecute-m) | *Описание* |
| [`Execute`](#Execute-m) | *Описание* |
| [`RelayCommand`](#RelayCommand-m) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`CanExecuteChanged`](#CanExecuteChanged-p) | *Описание* |





***  
***  
# Методы

## `CanExecute`<a href="RelayCommand-m" id="RelayCommand-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool CanExecute(object parameter)
```

`parameter` <mark style="color:red;">*`object`*</mark>  
 *Описание*  


***  

## `Execute`<a href="RelayCommand-m" id="RelayCommand-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Execute(object parameter)
```

***  

## `RelayCommand`<a href="RelayCommand-m" id="RelayCommand-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RelayCommand(Action<object> execute)
```

***  

## `RelayCommand`<a href="RelayCommand-m" id="RelayCommand-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public RelayCommand(Action<object> execute)
public RelayCommand(Action<object> execute, Predicate<object> canExecute)
```

***  
***  
 ***  
# События

## `CanExecuteChanged`<a href="CanExecuteChanged-p" id="CanExecuteChanged-p"></a>
Описание

```csharp
public event EventHandler CanExecuteChanged
```

