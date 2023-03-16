
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[UI](../../../TigerTrade.Core/UI.md).[Windows](../../../TigerTrade.Core/UI/Windows.md)


Описание

### Синтаксис
```csharp
public sealed class MessageWindow : Window, IComponentConnector
```


# Список методов
| Название | Описание |
| --- | --- |
| [`InitializeComponent`](#method-initializecomponent) | *Описание* |
| [`MessageWindow`](#method-messagewindow) | *Описание* |
| [`ShowWindow`](#method-showwindow) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Message`](#property-message) | *Описание* |





***  
***  
# Методы

## `InitializeComponent`<a href="method-initializecomponent" id="method-initializecomponent"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void InitializeComponent()
```

***  

## `MessageWindow`<a href="method-messagewindow" id="method-messagewindow"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public MessageWindow()
```

***  

## `ShowWindow`<a href="method-showwindow" id="method-showwindow"></a>
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

## `Message`<a href="property-message" id="property-message"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Message { get; set; }
```  
***

