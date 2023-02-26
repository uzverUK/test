
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
| [`GetItem`](./IChartCluster.cs/metody/GetItem.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Time`](./IChartCluster.cs/svoistva/Time.md) | *Описание* |
| [`OpenTime`](./IChartCluster.cs/svoistva/OpenTime.md) | *Описание* |
| [`CloseTime`](./IChartCluster.cs/svoistva/CloseTime.md) | *Описание* |
| [`Open`](./IChartCluster.cs/svoistva/Open.md) | *Описание* |
| [`High`](./IChartCluster.cs/svoistva/High.md) | *Описание* |
| [`Low`](./IChartCluster.cs/svoistva/Low.md) | *Описание* |
| [`Close`](./IChartCluster.cs/svoistva/Close.md) | *Описание* |
| [`Bid`](./IChartCluster.cs/svoistva/Bid.md) | *Описание* |
| [`Ask`](./IChartCluster.cs/svoistva/Ask.md) | *Описание* |
| [`Volume`](./IChartCluster.cs/svoistva/Volume.md) | *Описание* |
| [`Delta`](./IChartCluster.cs/svoistva/Delta.md) | *Описание* |
| [`BidTrades`](./IChartCluster.cs/svoistva/BidTrades.md) | *Описание* |
| [`AskTrades`](./IChartCluster.cs/svoistva/AskTrades.md) | *Описание* |
| [`Trades`](./IChartCluster.cs/svoistva/Trades.md) | *Описание* |
| [`OpenPos`](./IChartCluster.cs/svoistva/OpenPos.md) | *Описание* |
| [`OpenPosHigh`](./IChartCluster.cs/svoistva/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./IChartCluster.cs/svoistva/OpenPosLow.md) | *Описание* |
| [`OpenPosBidChg`](./IChartCluster.cs/svoistva/OpenPosBidChg.md) | *Описание* |
| [`OpenPosAskChg`](./IChartCluster.cs/svoistva/OpenPosAskChg.md) | *Описание* |
| [`OpenPosChg`](./IChartCluster.cs/svoistva/OpenPosChg.md) | *Описание* |
| [`DeltaHigh`](./IChartCluster.cs/svoistva/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./IChartCluster.cs/svoistva/DeltaLow.md) | *Описание* |
| [`IsUp`](./IChartCluster.cs/svoistva/IsUp.md) | *Описание* |
| [`MaxValues`](./IChartCluster.cs/svoistva/MaxValues.md) | *Описание* |


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

