# ChartAlertExecution

`namespace` [TigerTrade.Chart](../../).[Alerts](../Alerts.md)

Перечисление, которое используется при выставлении частоты срабатывания оповещение в [ChartAlertSettings](https://tigertrade.gitbook.io/doc/tech/tigertrade.chart/alerts/chartalertsettings.cs)

### Синтаксис

```csharp
public enum ChartAlertExecution
```

### Значения

| Название    | Описание                                                      |
| ----------- | ------------------------------------------------------------- |
| `EveryTime` | _Оповещение будет срабатывать каждый раз_                     |
| `OnlyOnce`  | _Оповещение сработает единожды, после чего станет неактивным_ |

### Пример

```csharp
ChartAlertSettings alert = new ChartAlertSettings();
alert.Execution = ChartAlertExecution.EveryTime;
```
