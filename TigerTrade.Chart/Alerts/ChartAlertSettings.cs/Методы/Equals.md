# Equals

`namespace` [TigerTrade.Chart](../../../../).[Alerts](../../../Alerts.md)\
`class` [ChartAlertSettings](../../ChartAlertSettings.cs.md)

Проверяет объекта [ChartAlertSettings](https://tigertrade.gitbook.io/doc/tekhnicheskaya-dokumentaciya/tigertrade.chart/alerts/chartalertsettings.cs), передаваемый в параметры метода, на равенство с текущим объектом [ChartAlertSettings](https://tigertrade.gitbook.io/doc/tekhnicheskaya-dokumentaciya/tigertrade.chart/alerts/chartalertsettings.cs)

### Синтаксис

```csharp
public bool Equals(ChartAlertSettings other)
```

<mark style="color:yellow;">`other`</mark> _<mark style="color:red;">`ChartAlertSettings`</mark>_\
Объект [ChartAlertSettings](https://tigertrade.gitbook.io/doc/tekhnicheskaya-dokumentaciya/tigertrade.chart/alerts/chartalertsettings.cs), который необходимо сравнить с текущим объектом

### Пример

```csharp
ChartAlertSettings alertA = new ChartAlertSettings{
    Active = true,
    Duration = ChartAlertPlayDuration.Once,
    Log = true,
    Message = "Test Message",
    PlaySound = false,
    ShowPopup = true
};

ChartAlertSettings alertB = new ChartAlertSettings{
    Active = true,
    Duration = ChartAlertPlayDuration.Once,
    Log = true,
    Message = "Test Message",
    PlaySound = false,
    ShowPopup = true
};
if(alertA.Equals(alertB))
    Debug.WriteLine("Objects are equal");
```
