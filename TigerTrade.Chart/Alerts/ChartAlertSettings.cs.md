
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Alerts](../../TigerTrade.Chart/Alerts.md)


Описание

### Синтаксис
```csharp
public sealed class ChartAlertSettings : INotifyPropertyChanged
```


# Таблица методов
| Название | Описание |
| --- | --- |
| [`ChartAlertSettings`](./ChartAlertSettings.cs/Методы/ChartAlertSettings.md) | *Описание* |
| [`Copy`](./ChartAlertSettings.cs/Методы/Copy.md) | *Описание* |
| [`Equals`](./ChartAlertSettings.cs/Методы/Equals.md) | *Описание* |
| [`GetHashCode`](./ChartAlertSettings.cs/Методы/GetHashCode.md) | *Описание* |

# Таблица свойств
| Название | Описание |
| --- | --- |
| [`Active`](./ChartAlertSettings.cs/Свойства/Active.md) | *Описание* |
| [`Duration`](./ChartAlertSettings.cs/Свойства/Duration.md) | *Описание* |
| [`Execution`](./ChartAlertSettings.cs/Свойства/Execution.md) | *Описание* |
| [`Expiration`](./ChartAlertSettings.cs/Свойства/Expiration.md) | *Описание* |
| [`IsActive`](./ChartAlertSettings.cs/Свойства/IsActive.md) | *Описание* |
| [`Log`](./ChartAlertSettings.cs/Свойства/Log.md) | *Описание* |
| [`Message`](./ChartAlertSettings.cs/Свойства/Message.md) | *Описание* |
| [`PlaySound`](./ChartAlertSettings.cs/Свойства/PlaySound.md) | *Описание* |
| [`SendEmail`](./ChartAlertSettings.cs/Свойства/SendEmail.md) | *Описание* |
| [`SendTelegram`](./ChartAlertSettings.cs/Свойства/SendTelegram.md) | *Описание* |
| [`ShowPopup`](./ChartAlertSettings.cs/Свойства/ShowPopup.md) | *Описание* |
| [`Signal`](./ChartAlertSettings.cs/Свойства/Signal.md) | *Описание* |

# Таблица событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ChartAlertSettings.cs/События/PropertyChanged.md) | *Описание* |





***  
***  
# Методы

## `ChartAlertSettings`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertSettings()
```

***  

## `Copy`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Copy(ChartAlertSettings alert, bool copyActive = false)
```

`alert` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

`copyActive` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Equals`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Equals(ChartAlertSettings other)
```
`other` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  


***  

## `GetHashCode`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override int GetHashCode()
```

***  
***  
 ***  
# Свойства

## `Active`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Active { get; set; }
```  
***

## `Duration`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertPlayDuration Duration { get; set; }
```  
***

## `Execution`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertExecution Execution { get; set; }
```  
***

## `Expiration`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime? Expiration { get; set; }
```  
***

## `IsActive`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsActive { get; }
```  
***

## `Log`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Log { get; set; }
```  
***

## `Message`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Message { get; set; }
```  
***

## `PlaySound`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool PlaySound { get; set; }
```  
***

## `SendEmail`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool SendEmail { get; set; }
```  
***

## `SendTelegram`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool SendTelegram { get; set; }
```  
***

## `ShowPopup`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowPopup { get; set; }
```  
***

## `Signal`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Signal { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

