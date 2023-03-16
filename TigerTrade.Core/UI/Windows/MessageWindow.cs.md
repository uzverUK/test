
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[UI](../../../TigerTrade.Core/UI.md).[Windows](../../../TigerTrade.Core/UI/Windows.md)


Описание

### Синтаксис
```csharp
public sealed class MessageWindow : Window, IComponentConnector
```


# Список методов
| Название | Описание |
| --- | --- |
| [`InitializeComponent`](#InitializeComponent-m) | *Описание* |
| [`MessageWindow`](#MessageWindow-m) | *Описание* |
| [`ShowWindow`](#ShowWindow-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Message`](#Message-p) | *Описание* |





***  
***  
# Методы

## `InitializeComponent`<a href="InitializeComponent-m" id="InitializeComponent-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InitializeComponent()
```

***  

## `MessageWindow`<a href="MessageWindow-m" id="MessageWindow-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public MessageWindow()
```

***  

## `ShowWindow`<a href="ShowWindow-m" id="ShowWindow-m"></a>
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

## `Message`<a href="Message-p" id="Message-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Message { get; set; }
```  
***

