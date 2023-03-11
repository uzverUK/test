# Copy

`namespace` [TigerTrade.Chart](../../../../).[Alerts](../../../Alerts.md)\
`class` [ChartAlertSettings](../../ChartAlertSettings.cs.md)

Метод позволяет скопировать свойства из другого объекта [ChartAlertSettings](https://tigertrade.gitbook.io/doc/tekhnicheskaya-dokumentaciya/tigertrade.chart/alerts/chartalertsettings.cs)

### Синтаксис

```csharp
public void Copy(ChartAlertSettings alert, bool copyActive = false)
```

### Параметры

<mark style="color:yellow;">`alert`</mark> _<mark style="color:red;">`ChartAlertSettings`</mark>_\
Копируемый о_бъект_ [ChartAlertSettings](https://tigertrade.gitbook.io/doc/tekhnicheskaya-dokumentaciya/tigertrade.chart/alerts/chartalertsettings.cs)

<mark style="color:yellow;">`copyActive`</mark> _<mark style="color:red;">`bool`</mark>_\
_Копировать ли свойство_ [_Active_](https://tigertrade.gitbook.io/doc/tekhnicheskaya-dokumentaciya/tigertrade.chart/alerts/chartalertsettings.cs/svoistva/active) _из копируемого объекта_

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

ChartAlertSettings copiedAlert = new ChartAlertSettings();
copiedAlert.Copy(alert);
```
