
`namespace` [TigerTrade.Core](../../../TigerTrade.Core.md).[UI](../../../TigerTrade.Core/UI.md).[Windows](../../../TigerTrade.Core/UI/Windows.md)


===

### Синтаксис
```csharp
public sealed class MessageWindow : Window, IComponentConnector
```


# Список методов
| Название | Описание |
| --- | --- |
| [`InitializeComponent`](#method-initializecomponent) | *===* |
| [`MessageWindow`](#method-messagewindow) | *===* |
| [`ShowWindow`](#method-showwindow) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Message`](#property-message) | *===* |





***  
***  
# Методы

## `InitializeComponent`<a href="method-initializecomponent" id="method-initializecomponent"></a>
===
```csharp
public void InitializeComponent()
```

***  

## `MessageWindow`<a href="method-messagewindow" id="method-messagewindow"></a>
===
```csharp
public MessageWindow()
```

***  

## `ShowWindow`<a href="method-showwindow" id="method-showwindow"></a>
===
```csharp
public static bool ShowWindow(Window owner, string title, string message)
```

`owner` <mark style="color:red;">*`Window`*</mark>  
 *===*  

`title` <mark style="color:red;">*`string`*</mark>  
 *===*  

`message` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Message`<a href="property-message" id="property-message"></a>
===
```csharp
public string Message { get; set; }
```  
***

