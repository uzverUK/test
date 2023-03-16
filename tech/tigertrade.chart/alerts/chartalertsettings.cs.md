# ChartAlertSettings

`namespace` [TigerTrade.Chart](../../../).[Alerts](./)

\===

#### Синтаксис

```csharp
public sealed class ChartAlertSettings : INotifyPropertyChanged
```

## Список методов

| Название                                                                   | Описание |
| -------------------------------------------------------------------------- | -------- |
| [`ChartAlertSettings`](chartalertsettings.cs.md#method-chartalertsettings) | _===_    |
| [`Copy`](chartalertsettings.cs.md#method-copy)                             | _===_    |
| [`Equals`](chartalertsettings.cs.md#method-equals)                         | _===_    |
| [`GetHashCode`](chartalertsettings.cs.md#method-gethashcode)               | _===_    |

## Список свойств

| Название                                                         | Описание |
| ---------------------------------------------------------------- | -------- |
| [`Active`](chartalertsettings.cs.md#property-active)             | _===_    |
| [`Duration`](chartalertsettings.cs.md#property-duration)         | _===_    |
| [`Execution`](chartalertsettings.cs.md#property-execution)       | _===_    |
| [`Expiration`](chartalertsettings.cs.md#property-expiration)     | _===_    |
| [`IsActive`](chartalertsettings.cs.md#property-isactive)         | _===_    |
| [`Log`](chartalertsettings.cs.md#property-log)                   | _===_    |
| [`Message`](chartalertsettings.cs.md#property-message)           | _===_    |
| [`PlaySound`](chartalertsettings.cs.md#property-playsound)       | _===_    |
| [`SendEmail`](chartalertsettings.cs.md#property-sendemail)       | _===_    |
| [`SendTelegram`](chartalertsettings.cs.md#property-sendtelegram) | _===_    |
| [`ShowPopup`](chartalertsettings.cs.md#property-showpopup)       | _===_    |
| [`Signal`](chartalertsettings.cs.md#property-signal)             | _===_    |

## Список событий

| Название                                                            | Описание |
| ------------------------------------------------------------------- | -------- |
| [`PropertyChanged`](chartalertsettings.cs.md#event-propertychanged) | _===_    |

***

***

## Методы

### `ChartAlertSettings` <a href="#method-chartalertsettings" id="method-chartalertsettings"></a>

\===

```csharp
public ChartAlertSettings()
```

***

### `Copy` <a href="#method-copy" id="method-copy"></a>

\===

```csharp
public void Copy(ChartAlertSettings alert, bool copyActive = false)
```

`alert` _<mark style="color:red;">`ChartAlertSettings`</mark>_\
_===_

`copyActive` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `Equals` <a href="#method-equals" id="method-equals"></a>

\===

```csharp
public bool Equals(ChartAlertSettings other)
```

`other` _<mark style="color:red;">`ChartAlertSettings`</mark>_\
_===_

***

### `GetHashCode` <a href="#method-gethashcode" id="method-gethashcode"></a>

\===

```csharp
public override int GetHashCode()
```

***

***

***

## Свойства

### `Active` <a href="#property-active" id="property-active"></a>

\===

```csharp
public bool Active { get; set; }
```

***

### `Duration` <a href="#property-duration" id="property-duration"></a>

\===

```csharp
public ChartAlertPlayDuration Duration { get; set; }
```

***

### `Execution` <a href="#property-execution" id="property-execution"></a>

\===

```csharp
public ChartAlertExecution Execution { get; set; }
```

***

### `Expiration` <a href="#property-expiration" id="property-expiration"></a>

\===

```csharp
public DateTime? Expiration { get; set; }
```

***

### `IsActive` <a href="#property-isactive" id="property-isactive"></a>

\===

```csharp
public bool IsActive { get; }
```

***

### `Log` <a href="#property-log" id="property-log"></a>

\===

```csharp
public bool Log { get; set; }
```

***

### `Message` <a href="#property-message" id="property-message"></a>

\===

```csharp
public string Message { get; set; }
```

***

### `PlaySound` <a href="#property-playsound" id="property-playsound"></a>

\===

```csharp
public bool PlaySound { get; set; }
```

***

### `SendEmail` <a href="#property-sendemail" id="property-sendemail"></a>

\===

```csharp
public bool SendEmail { get; set; }
```

***

### `SendTelegram` <a href="#property-sendtelegram" id="property-sendtelegram"></a>

\===

```csharp
public bool SendTelegram { get; set; }
```

***

### `ShowPopup` <a href="#property-showpopup" id="property-showpopup"></a>

\===

```csharp
public bool ShowPopup { get; set; }
```

***

### `Signal` <a href="#property-signal" id="property-signal"></a>

\===

```csharp
public string Signal { get; set; }
```

***

***

***

## События

### `PropertyChanged` <a href="#event-propertychanged" id="event-propertychanged"></a>

\===

```csharp
public event PropertyChangedEventHandler PropertyChanged
```
