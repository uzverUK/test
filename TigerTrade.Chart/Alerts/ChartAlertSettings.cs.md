
`namespace` [TigerTrade.Chart](../../TigerTrade.Chart.md).[Alerts](../../TigerTrade.Chart/Alerts.md)


Описание

### Синтаксис
```csharp
public sealed class ChartAlertSettings : INotifyPropertyChanged
```


## Таблица методов
| Название | Описание |
| --- | --- |
| [`ChartAlertSettings`](./ChartAlertSettings.cs/Методы/ChartAlertSettings.md) | *Описание* |
| [`Copy`](./ChartAlertSettings.cs/Методы/Copy.md) | *Описание* |
| [`Equals`](./ChartAlertSettings.cs/Методы/Equals.md) | *Описание* |
| [`GetHashCode`](./ChartAlertSettings.cs/Методы/GetHashCode.md) | *Описание* |

## Таблица свойств
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

## Таблица событий
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ChartAlertSettings.cs/События/PropertyChanged.md) | *Описание* |




            ***
  ***
  # Методы

## ChartAlertSettings
Описание

```csharp
public ChartAlertSettings()
```

***                

## Copy
Описание

```csharp
public void Copy(ChartAlertSettings alert, bool copyActive = false)
```

<mark style="color:yellow;">`alert`</mark> <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  

<mark style="color:yellow;">`copyActive`</mark> <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***                

## Equals
Описание

```csharp
public bool Equals(ChartAlertSettings other)
```
<mark style="color:yellow;">`other`</mark> <mark style="color:red;">*`ChartAlertSettings`*</mark>  
 *Описание*  


***                

## GetHashCode
Описание

```csharp
public override int GetHashCode()
```

***                
                ***
  ***
  # Свойства

## Active
Описание

```csharp
public bool Active { get; set; }
```
***

## Duration
Описание

```csharp
public ChartAlertPlayDuration Duration { get; set; }
```
***

## Execution
Описание

```csharp
public ChartAlertExecution Execution { get; set; }
```
***

## Expiration
Описание

```csharp
public DateTime? Expiration { get; set; }
```
***

## IsActive
Описание

```csharp
public bool IsActive { get; }
```
***

## Log
Описание

```csharp
public bool Log { get; set; }
```
***

## Message
Описание

```csharp
public string Message { get; set; }
```
***

## PlaySound
Описание

```csharp
public bool PlaySound { get; set; }
```
***

## SendEmail
Описание

```csharp
public bool SendEmail { get; set; }
```
***

## SendTelegram
Описание

```csharp
public bool SendTelegram { get; set; }
```
***

## ShowPopup
Описание

```csharp
public bool ShowPopup { get; set; }
```
***

## Signal
Описание

```csharp
public string Signal { get; set; }
```
***
***
  ***
  # События

## PropertyChanged
Описание

```csharp
public event PropertyChangedEventHandler PropertyChanged
```
***

