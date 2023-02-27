
# public interface IChartCluster
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public interface IChartCluster
```


## Методы
| Название | Описание |
| --- | --- |
| [`GetItem`](./IChartCluster.cs/Методы/GetItem.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Time`](./IChartCluster.cs/Свойства/Time.md) | *Описание* |
| [`OpenTime`](./IChartCluster.cs/Свойства/OpenTime.md) | *Описание* |
| [`CloseTime`](./IChartCluster.cs/Свойства/CloseTime.md) | *Описание* |
| [`Open`](./IChartCluster.cs/Свойства/Open.md) | *Описание* |
| [`High`](./IChartCluster.cs/Свойства/High.md) | *Описание* |
| [`Low`](./IChartCluster.cs/Свойства/Low.md) | *Описание* |
| [`Close`](./IChartCluster.cs/Свойства/Close.md) | *Описание* |
| [`Bid`](./IChartCluster.cs/Свойства/Bid.md) | *Описание* |
| [`Ask`](./IChartCluster.cs/Свойства/Ask.md) | *Описание* |
| [`Volume`](./IChartCluster.cs/Свойства/Volume.md) | *Описание* |
| [`Delta`](./IChartCluster.cs/Свойства/Delta.md) | *Описание* |
| [`BidTrades`](./IChartCluster.cs/Свойства/BidTrades.md) | *Описание* |
| [`AskTrades`](./IChartCluster.cs/Свойства/AskTrades.md) | *Описание* |
| [`Trades`](./IChartCluster.cs/Свойства/Trades.md) | *Описание* |
| [`OpenPos`](./IChartCluster.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosHigh`](./IChartCluster.cs/Свойства/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./IChartCluster.cs/Свойства/OpenPosLow.md) | *Описание* |
| [`OpenPosBidChg`](./IChartCluster.cs/Свойства/OpenPosBidChg.md) | *Описание* |
| [`OpenPosAskChg`](./IChartCluster.cs/Свойства/OpenPosAskChg.md) | *Описание* |
| [`OpenPosChg`](./IChartCluster.cs/Свойства/OpenPosChg.md) | *Описание* |
| [`DeltaHigh`](./IChartCluster.cs/Свойства/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./IChartCluster.cs/Свойства/DeltaLow.md) | *Описание* |
| [`IsUp`](./IChartCluster.cs/Свойства/IsUp.md) | *Описание* |
| [`MaxValues`](./IChartCluster.cs/Свойства/MaxValues.md) | *Описание* |


## Пример
```csharp
using System;

class Program
{
    static void Main()
    {
        // Create a new instance of the Person class.
        Person person = new Person("John", "Doe", new DateTime(1990, 1, 1));

        // Display the person's full name and age.
        Console.WriteLine("Name: {0}", person.GetFullName());
        Console.WriteLine("Age: {0}", person.GetAge());
    }
}

class Person
{
    private string firstName;
    private string lastName;
    private DateTime dateOfBirth;

    public Person(string firstName, string lastName, DateTime dateOfBirth)
    {
        this.firstName = firstName;
        this.lastName = lastName;
        this.dateOfBirth = dateOfBirth;
    }

    public string GetFullName()
    {
        return firstName + " " + lastName;
    }

    public int GetAge()
    {
        TimeSpan span = DateTime.Now - dateOfBirth;
        int years = (int)(span.Days / 365.25);
        return years;
    }
}
```

