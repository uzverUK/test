# ChartAlertSettings

`namespace` [TigerTrade.Chart](../../../../).[Alerts](../../../Alerts.md)\
`class` [ChartAlertSettings](../../ChartAlertSettings.cs.md)

Конструктор объекта класса ChartAlertSettings.

### Синтаксис

```csharp
public ChartAlertSettings()
```

### Пример

```csharp
ChartAlertSettings alert = new ChartAlertSettings{
    Active = true,
    Duration = ChartAlertPlayDuration.Once,
    Log = true,
    Message = "Test Message",
    PlaySound = false,
    ShowPopup = true
};
```
