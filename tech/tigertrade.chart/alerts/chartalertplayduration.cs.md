# ChartAlertPlayDuration

`namespace` [TigerTrade.Chart](../../../).[Alerts](./)

Перечисление, которое используется для определения длительности проигрывания звукового оповещения в [ChartAlertSettings](https://tigertrade.gitbook.io/doc/tech/tigertrade.chart/alerts/chartalertsettings.cs). Естественно, только в том случае, когда значение [PlaySound](https://tigertrade.gitbook.io/doc/tech/tigertrade.chart/alerts/chartalertsettings.cs/svoistva/playsound) равно true.

### Синтаксис

```csharp
public enum ChartAlertPlayDuration
```

### Значения

| Название    | Описание                                   |
| ----------- | ------------------------------------------ |
| `Once`      | _Проиграть звук единожды_                  |
| `Seconds5`  | _Проигрывать звук на протяжении 5 секунд_  |
| `Seconds10` | _Проигрывать звук на протяжении 10 секунд_ |
| `Seconds30` | _Проигрывать звук на протяжении 30 секунд_ |
| `Minute`    | _Проигрывать звук на протяжении 1 минуты_  |
