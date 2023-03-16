
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[UI](../../../TigerTrade.Core/UI.md).[Windows](../../../TigerTrade.Core/UI/Windows.md)


Описание

### Синтаксис
```csharp
public sealed class MessageWindow : Window, IComponentConnector
```


# Список методов
| Название | Описание |
| --- | --- |
| [`InitializeComponent`](#test) | *Описание* |
| [`MessageWindow`](#test) | *Описание* |
| [`ShowWindow`](#test) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Message`](./MessageWindow.cs/Свойства/Message.md) | *Описание* |





***  
***  
# Методы

## `InitializeComponent`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InitializeComponent()
```

***  

## `MessageWindow`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public MessageWindow()
```

***  

## `ShowWindow`<a href="test" id="test"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool ShowWindow(Window owner, string title, string message)
```

`owner` <mark style="color:red;">*`Window`*</mark>  
 *Описание*  

`title` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`message` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Message`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Message { get; set; }
```  
***

