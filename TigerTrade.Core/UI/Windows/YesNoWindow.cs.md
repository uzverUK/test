
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[UI](../../../TigerTrade.Core/UI.md).[Windows](../../../TigerTrade.Core/UI/Windows.md)


Описание

### Синтаксис
```csharp
public sealed class YesNoWindow : Window, IComponentConnector
```


# Список методов
| Название | Описание |
| --- | --- |
| [`InitializeComponent`](#method-initializecomponent) | *Описание* |
| [`ShowWindow`](#method-showwindow) | *Описание* |
| [`YesNoWindow`](#method-yesnowindow) | *Описание* |

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

## `YesNoWindow`<a href="method-yesnowindow" id="method-yesnowindow"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public YesNoWindow()
```

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

