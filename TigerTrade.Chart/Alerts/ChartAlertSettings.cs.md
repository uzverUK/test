# ChartAlertSettings

`namespace` [TigerTrade.Chart](../../).[Alerts](../Alerts.md)

Описание

### Синтаксис

```csharp
public sealed class ChartAlertSettings : INotifyPropertyChanged
```

### Методы

| Название                                                                   | Описание                              |
| -------------------------------------------------------------------------- | ------------------------------------- |
| [`ChartAlertSettings`](ChartAlertSettings.cs/Методы/ChartAlertSettings.md) | _Конструктор_                         |
| [`Copy`](ChartAlertSettings.cs/Методы/Copy.md)                             | М_етод копирования объекта класса_    |
| [`Equals`](ChartAlertSettings.cs/Методы/Equals.md)                         | М_етод сравнения объектов класса_     |
| [`GetHashCode`](ChartAlertSettings.cs/Методы/GetHashCode.md)               | М_етод получения хэша объекта класса_ |

### Свойства

| Название                                                         | Описание                                                                                      |
| ---------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| [`Active`](ChartAlertSettings.cs/Свойства/Active.md)             | _Определяет, активно ли оповещение_                                                           |
| [`Duration`](ChartAlertSettings.cs/Свойства/Duration.md)         | _Определяет длительность звукового оповещения_                                                |
| [`Execution`](ChartAlertSettings.cs/Свойства/Execution.md)       | _Определяет частоту срабатывания оповещения_                                                  |
| [`Expiration`](ChartAlertSettings.cs/Свойства/Expiration.md)     | _Определяет время экспирации оповещение_                                                      |
| [`IsActive`](ChartAlertSettings.cs/Свойства/IsActive.md)         | _Передаёт состояние активности оповещения_                                                    |
| [`Log`](ChartAlertSettings.cs/Свойства/Log.md)                   | _Определяет, будет ли вестись лог срабатываний оповещения_                                    |
| [`Message`](ChartAlertSettings.cs/Свойства/Message.md)           | _Определяет сообщение оповещения_                                                             |
| [`PlaySound`](ChartAlertSettings.cs/Свойства/PlaySound.md)       | _Определяет, будет ли проигрываться звуковой файл во время срабатывания_                      |
| [`SendEmail`](ChartAlertSettings.cs/Свойства/SendEmail.md)       | _Определяет, будет ли отправляться email во время срабатывания оповещения_                    |
| [`SendTelegram`](ChartAlertSettings.cs/Свойства/SendTelegram.md) | _Определяет, будет ли отправляться сообщение в Telegram во время срабатывания оповещения_     |
| [`ShowPopup`](ChartAlertSettings.cs/Свойства/ShowPopup.md)       | Определяет, будет ли отображаться всплывающее окно оповещения                                 |
| [`Signal`](ChartAlertSettings.cs/Свойства/Signal.md)             | <mark style="color:red;">\*уточнить\*</mark> Определяет путь к файлу для звукового оповещения |

### События

| Название                                                              | Описание                             |
| --------------------------------------------------------------------- | ------------------------------------ |
| [`PropertyChanged`](ChartAlertSettings.cs/События/PropertyChanged.md) | Событие изменения значения свойства. |
