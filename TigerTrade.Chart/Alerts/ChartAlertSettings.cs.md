
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Alerts](../../TigerTrade.Chart/Alerts.md)


Описание

### Синтаксис
```csharp
public sealed class ChartAlertSettings : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartAlertSettings`](#method-chartalertsettings) | *Описание* |
| [`Copy`](#method-copy) | *Описание* |
| [`Equals`](#method-equals) | *Описание* |
| [`GetHashCode`](#method-gethashcode) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Active`](#property-active) | *Описание* |
| [`Duration`](#property-duration) | *Описание* |
| [`Execution`](#property-execution) | *Описание* |
| [`Expiration`](#property-expiration) | *Описание* |
| [`IsActive`](#property-isactive) | *Описание* |
| [`Log`](#property-log) | *Описание* |
| [`Message`](#property-message) | *Описание* |
| [`PlaySound`](#property-playsound) | *Описание* |
| [`SendEmail`](#property-sendemail) | *Описание* |
| [`SendTelegram`](#property-sendtelegram) | *Описание* |
| [`ShowPopup`](#property-showpopup) | *Описание* |
| [`Signal`](#property-signal) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#event-propertychanged) | *Описание* |





***  
***  
# Методы

## `ChartAlertSettings`<a href="method-chartalertsettings" id="method-chartalertsettings"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertSettings()
```

***  

## `Copy`<a href="method-copy" id="method-copy"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Copy(ChartAlertSettings alert, bool copyActive = false)
```

`alert` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

`copyActive` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Equals`<a href="method-equals" id="method-equals"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Equals(ChartAlertSettings other)
```
`other` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  


***  

## `GetHashCode`<a href="method-gethashcode" id="method-gethashcode"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override int GetHashCode()
```

***  
***  
 ***  
# Свойства

## `Active`<a href="property-active" id="property-active"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Active { get; set; }
```  
***

## `Duration`<a href="property-duration" id="property-duration"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertPlayDuration Duration { get; set; }
```  
***

## `Execution`<a href="property-execution" id="property-execution"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertExecution Execution { get; set; }
```  
***

## `Expiration`<a href="property-expiration" id="property-expiration"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime? Expiration { get; set; }
```  
***

## `IsActive`<a href="property-isactive" id="property-isactive"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsActive { get; }
```  
***

## `Log`<a href="property-log" id="property-log"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Log { get; set; }
```  
***

## `Message`<a href="property-message" id="property-message"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Message { get; set; }
```  
***

## `PlaySound`<a href="property-playsound" id="property-playsound"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool PlaySound { get; set; }
```  
***

## `SendEmail`<a href="property-sendemail" id="property-sendemail"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool SendEmail { get; set; }
```  
***

## `SendTelegram`<a href="property-sendtelegram" id="property-sendtelegram"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool SendTelegram { get; set; }
```  
***

## `ShowPopup`<a href="property-showpopup" id="property-showpopup"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowPopup { get; set; }
```  
***

## `Signal`<a href="property-signal" id="property-signal"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Signal { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="event-propertychanged" id="event-propertychanged"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

