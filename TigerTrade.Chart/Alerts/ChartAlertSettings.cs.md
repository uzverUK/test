
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Alerts](../../TigerTrade.Chart/Alerts.md)


Описание

### Синтаксис
```csharp
public sealed class ChartAlertSettings : INotifyPropertyChanged
```


# Список методов
| Название | Описание |
| --- | --- |
| [`ChartAlertSettings`](#ChartAlertSettings-m) | *Описание* |
| [`Copy`](#Copy-m) | *Описание* |
| [`Equals`](#Equals-m) | *Описание* |
| [`GetHashCode`](#GetHashCode-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Active`](#Active-p) | *Описание* |
| [`Duration`](#Duration-p) | *Описание* |
| [`Execution`](#Execution-p) | *Описание* |
| [`Expiration`](#Expiration-p) | *Описание* |
| [`IsActive`](#IsActive-p) | *Описание* |
| [`Log`](#Log-p) | *Описание* |
| [`Message`](#Message-p) | *Описание* |
| [`PlaySound`](#PlaySound-p) | *Описание* |
| [`SendEmail`](#SendEmail-p) | *Описание* |
| [`SendTelegram`](#SendTelegram-p) | *Описание* |
| [`ShowPopup`](#ShowPopup-p) | *Описание* |
| [`Signal`](#Signal-p) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](#PropertyChanged-p) | *Описание* |





***  
***  
# Методы

## `ChartAlertSettings`<a href="GetHashCode-m" id="GetHashCode-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertSettings()
```

***  

## `Copy`<a href="GetHashCode-m" id="GetHashCode-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Copy(ChartAlertSettings alert, bool copyActive = false)
```

`alert` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

`copyActive` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Equals`<a href="GetHashCode-m" id="GetHashCode-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Equals(ChartAlertSettings other)
```
`other` <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  


***  

## `GetHashCode`<a href="GetHashCode-m" id="GetHashCode-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public override int GetHashCode()
```

***  
***  
 ***  
# Свойства

## `Active`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Active { get; set; }
```  
***

## `Duration`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertPlayDuration Duration { get; set; }
```  
***

## `Execution`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ChartAlertExecution Execution { get; set; }
```  
***

## `Expiration`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime? Expiration { get; set; }
```  
***

## `IsActive`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsActive { get; }
```  
***

## `Log`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool Log { get; set; }
```  
***

## `Message`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Message { get; set; }
```  
***

## `PlaySound`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool PlaySound { get; set; }
```  
***

## `SendEmail`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool SendEmail { get; set; }
```  
***

## `SendTelegram`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool SendTelegram { get; set; }
```  
***

## `ShowPopup`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool ShowPopup { get; set; }
```  
***

## `Signal`<a href="Signal-p" id="Signal-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public string Signal { get; set; }
```  
***
***  
 ***  
# События

## `PropertyChanged`<a href="PropertyChanged-p" id="PropertyChanged-p"></a>
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

