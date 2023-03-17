# ChartAlertSettings

`namespace` [TigerTrade.Chart](../../../).[Alerts](./)

\===

#### Синтаксис

```csharp
public sealed class ChartAlertSettings : INotifyPropertyChanged
```

## Список методов

| Название                                                                   | Описание                              |
| -------------------------------------------------------------------------- | ------------------------------------- |
| [`ChartAlertSettings`](chartalertsettings.cs.md#method-chartalertsettings) | _Конструктор_                         |
| [`Copy`](chartalertsettings.cs.md#method-copy)                             | М_етод копирования объекта класса_    |
| [`Equals`](chartalertsettings.cs.md#method-equals)                         | М_етод сравнения объектов класса_     |
| [`GetHashCode`](chartalertsettings.cs.md#method-gethashcode)               | М_етод получения хэша объекта класса_ |

## Список свойств

| Название                                                         | Описание                                                                                                 |
| ---------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| [`Active`](chartalertsettings.cs.md#property-active)             | _Возвращает или задает активно ли оповещение_                                                            |
| [`Duration`](chartalertsettings.cs.md#property-duration)         | _Возвращает или задает длительность звукового оповещения_                                                |
| [`Execution`](chartalertsettings.cs.md#property-execution)       | _Возвращает или задает частоту срабатывания оповещения_                                                  |
| [`Expiration`](chartalertsettings.cs.md#property-expiration)     | _Возвращает или задает время экспирации оповещение_                                                      |
| [`IsActive`](chartalertsettings.cs.md#property-isactive)         | _Возвращает активно ли оповещения_                                                                       |
| [`Log`](chartalertsettings.cs.md#property-log)                   | _Возвращает или задает будет ли оповещение добавляться в лог_                                            |
| [`Message`](chartalertsettings.cs.md#property-message)           | _Возвращает или задает текст оповещения_                                                                 |
| [`PlaySound`](chartalertsettings.cs.md#property-playsound)       | _Возвращает или задает будет ли проигрываться звуковой файл во время срабатывания_                       |
| [`SendEmail`](chartalertsettings.cs.md#property-sendemail)       | _Возвращает или задает будет ли отправляться email во время срабатывания оповещения_                     |
| [`SendTelegram`](chartalertsettings.cs.md#property-sendtelegram) | _Возвращает или задает будет ли отправляться сообщение в Telegram во время срабатывания оповещения_      |
| [`ShowPopup`](chartalertsettings.cs.md#property-showpopup)       | Возвращает или задает будет ли отображаться всплывающее окно оповещения                                  |
| [`Signal`](chartalertsettings.cs.md#property-signal)             | <mark style="color:red;">\*уточнить\*</mark> Возвращает или задает путь к файлу для звукового оповещения |

## Список событий

| Название                                                            | Описание                             |
| ------------------------------------------------------------------- | ------------------------------------ |
| [`PropertyChanged`](chartalertsettings.cs.md#event-propertychanged) | Событие изменения значения свойства. |

***

***

## Методы

### `ChartAlertSettings` <a href="#method-chartalertsettings" id="method-chartalertsettings"></a>

_Конструктор_

```csharp
public ChartAlertSettings()
```

***

### `Copy` <a href="#method-copy" id="method-copy"></a>

М_етод копирования объекта класса_

```csharp
public void Copy(ChartAlertSettings alert, bool copyActive = false)
```

`alert` _<mark style="color:red;">`ChartAlertSettings`</mark>_\
_===_

`copyActive` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `Equals` <a href="#method-equals" id="method-equals"></a>

М_етод сравнения объектов класса_

```csharp
public bool Equals(ChartAlertSettings other)
```

`other` _<mark style="color:red;">`ChartAlertSettings`</mark>_\
_===_

***

### `GetHashCode` <a href="#method-gethashcode" id="method-gethashcode"></a>

М_етод получения хэша объекта класса_

```csharp
public override int GetHashCode()
```

***

***

***

## Свойства

### `Active` <a href="#property-active" id="property-active"></a>

_Возвращает или задает активно ли оповещение_

```csharp
public bool Active { get; set; }
```

***

### `Duration` <a href="#property-duration" id="property-duration"></a>

_Возвращает или задает длительность звукового оповещения_

```csharp
public ChartAlertPlayDuration Duration { get; set; }
```

***

### `Execution` <a href="#property-execution" id="property-execution"></a>

_Возвращает или задает частоту срабатывания оповещения_

```csharp
public ChartAlertExecution Execution { get; set; }
```

***

### `Expiration` <a href="#property-expiration" id="property-expiration"></a>

_Возвращает или задает время экспирации оповещение_

```csharp
public DateTime? Expiration { get; set; }
```

***

### `IsActive` <a href="#property-isactive" id="property-isactive"></a>

_Возвращает активно ли оповещения_

```csharp
public bool IsActive { get; }
```

***

### `Log` <a href="#property-log" id="property-log"></a>

_Возвращает или задает будет ли оповещение добавляться в лог_

```csharp
public bool Log { get; set; }
```

***

### `Message` <a href="#property-message" id="property-message"></a>

_Возвращает или задает текст оповещения_

```csharp
public string Message { get; set; }
```

***

### `PlaySound` <a href="#property-playsound" id="property-playsound"></a>

_Возвращает или задает будет ли проигрываться звуковой файл во время срабатывания_

```csharp
public bool PlaySound { get; set; }
```

***

### `SendEmail` <a href="#property-sendemail" id="property-sendemail"></a>

_Возвращает или задает будет ли отправляться email во время срабатывания оповещения_

```csharp
public bool SendEmail { get; set; }
```

***

### `SendTelegram` <a href="#property-sendtelegram" id="property-sendtelegram"></a>

_Возвращает или задает будет ли отправляться сообщение в Telegram во время срабатывания оповещения_

```csharp
public bool SendTelegram { get; set; }
```

***

### `ShowPopup` <a href="#property-showpopup" id="property-showpopup"></a>

Возвращает или задает будет ли отображаться всплывающее окно оповещения

```csharp
public bool ShowPopup { get; set; }
```

***

### `Signal` <a href="#property-signal" id="property-signal"></a>

<mark style="color:red;">\*уточнить\*</mark> Возвращает или задает путь к файлу для звукового оповещения

```csharp
public string Signal { get; set; }
```

***

***

***

## События

### `PropertyChanged` <a href="#event-propertychanged" id="event-propertychanged"></a>

Событие изменения значения свойства.

```csharp
public event PropertyChangedEventHandler PropertyChanged
```
