
# VolumeProfileType.cs
## Расположение
```csharp
namespace TigerTrade.Chart.Objects.List
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public enum VolumeProfileType
```


## Значения
| Название | Описание |
| --- | --- |
| ` Volume` | *Описание* |
| ` Trades` | *Описание* |
| ` Delta` | *Описание* |
| ` BidAsk` | *Описание* |


## Пример
```csharp
public enum Weekday
{
    Monday,
    Tuesday,
    Wednesday,
    Thursday,
    Friday,
    Saturday,sssss
    Sunday
}
Weekday today = Weekday.Tuesday;
Console.WriteLine("Today is {0}.", today);
```

