
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Alerts](../../TigerTrade.Chart/Alerts.md)


===

### Синтаксис
```csharp
public sealed class ChartAlertSettings : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartAlertSettings`](#method-chartalertsettings) | *===* |
| [`Copy`](#method-copy) | *===* |
| [`Equals`](#method-equals) | *===* |
| [`GetHashCode`](#method-gethashcode) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Active`](#property-active) | *===* |
| [`Duration`](#property-duration) | *===* |
| [`Execution`](#property-execution) | *===* |
| [`Expiration`](#property-expiration) | *===* |
| [`IsActive`](#property-isactive) | *===* |
| [`Log`](#property-log) | *===* |
| [`Message`](#property-message) | *===* |
| [`PlaySound`](#property-playsound) | *===* |
| [`SendEmail`](#property-sendemail) | *===* |
| [`SendTelegram`](#property-sendtelegram) | *===* |
| [`ShowPopup`](#property-showpopup) | *===* |
| [`Signal`](#property-signal) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *===* |





***  
***  
# Методы

## `ChartAlertSettings`<a href="method-chartalertsettings" id="method-chartalertsettings"></a>
===
```csharp
public ChartAlertSettings()
```

***  

## `Copy`<a href="method-copy" id="method-copy"></a>
===
```csharp
public void Copy(ChartAlertSettings alert, bool copyActive = false)
```

`alert` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *===*  

`copyActive` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `Equals`<a href="method-equals" id="method-equals"></a>
===
```csharp
public bool Equals(ChartAlertSettings other)
```
`other` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *===*  


***  

## `GetHashCode`<a href="method-gethashcode" id="method-gethashcode"></a>
===
```csharp
public override int GetHashCode()
```

***  
***  
 ***  
# Свойства

## `Active`<a href="property-active" id="property-active"></a>
===
```csharp
public bool Active { get; set; }
```  
***

## `Duration`<a href="property-duration" id="property-duration"></a>
===
```csharp
public ChartAlertPlayDuration Duration { get; set; }
```  
***

## `Execution`<a href="property-execution" id="property-execution"></a>
===
```csharp
public ChartAlertExecution Execution { get; set; }
```  
***

## `Expiration`<a href="property-expiration" id="property-expiration"></a>
===
```csharp
public DateTime? Expiration { get; set; }
```  
***

## `IsActive`<a href="property-isactive" id="property-isactive"></a>
===
```csharp
public bool IsActive { get; }
```  
***

## `Log`<a href="property-log" id="property-log"></a>
===
```csharp
public bool Log { get; set; }
```  
***

## `Message`<a href="property-message" id="property-message"></a>
===
```csharp
public string Message { get; set; }
```  
***

## `PlaySound`<a href="property-playsound" id="property-playsound"></a>
===
```csharp
public bool PlaySound { get; set; }
```  
***

## `SendEmail`<a href="property-sendemail" id="property-sendemail"></a>
===
```csharp
public bool SendEmail { get; set; }
```  
***

## `SendTelegram`<a href="property-sendtelegram" id="property-sendtelegram"></a>
===
```csharp
public bool SendTelegram { get; set; }
```  
***

## `ShowPopup`<a href="property-showpopup" id="property-showpopup"></a>
===
```csharp
public bool ShowPopup { get; set; }
```  
***

## `Signal`<a href="property-signal" id="property-signal"></a>
===
```csharp
public string Signal { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

