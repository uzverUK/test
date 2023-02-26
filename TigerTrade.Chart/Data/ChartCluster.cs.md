
# public sealed class ChartCluster : IChartCluster
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class ChartCluster : IChartCluster
```


## Методы
| Название | Описание |
| --- | --- |
| [`ChartCluster`](./ChartCluster.cs/metody/ChartCluster.md) | *Описание* |
| [`AddTick`](./ChartCluster.cs/metody/AddTick.md) | *Описание* |
| [`AddItem`](./ChartCluster.cs/metody/AddItem.md) | *Описание* |
| [`AddCluster`](./ChartCluster.cs/metody/AddCluster.md) | *Описание* |
| [`UpdateData`](./ChartCluster.cs/metody/UpdateData.md) | *Описание* |
| [`GetItem`](./ChartCluster.cs/metody/GetItem.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Time`](./ChartCluster.cs/svoistva/Time.md) | *Описание* |
| [`OpenTime`](./ChartCluster.cs/svoistva/OpenTime.md) | *Описание* |
| [`CloseTime`](./ChartCluster.cs/svoistva/CloseTime.md) | *Описание* |
| [`Open`](./ChartCluster.cs/svoistva/Open.md) | *Описание* |
| [`High`](./ChartCluster.cs/svoistva/High.md) | *Описание* |
| [`Low`](./ChartCluster.cs/svoistva/Low.md) | *Описание* |
| [`Close`](./ChartCluster.cs/svoistva/Close.md) | *Описание* |
| [`Bid`](./ChartCluster.cs/svoistva/Bid.md) | *Описание* |
| [`Ask`](./ChartCluster.cs/svoistva/Ask.md) | *Описание* |
| [`BidTrades`](./ChartCluster.cs/svoistva/BidTrades.md) | *Описание* |
| [`AskTrades`](./ChartCluster.cs/svoistva/AskTrades.md) | *Описание* |
| [`OpenPos`](./ChartCluster.cs/svoistva/OpenPos.md) | *Описание* |
| [`OpenPosHigh`](./ChartCluster.cs/svoistva/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./ChartCluster.cs/svoistva/OpenPosLow.md) | *Описание* |
| [`OpenPosBidChg`](./ChartCluster.cs/svoistva/OpenPosBidChg.md) | *Описание* |
| [`OpenPosAskChg`](./ChartCluster.cs/svoistva/OpenPosAskChg.md) | *Описание* |
| [`Volume`](./ChartCluster.cs/svoistva/Volume.md) | *Описание* |
| [`Delta`](./ChartCluster.cs/svoistva/Delta.md) | *Описание* |
| [`Trades`](./ChartCluster.cs/svoistva/Trades.md) | *Описание* |
| [`OpenPosChg`](./ChartCluster.cs/svoistva/OpenPosChg.md) | *Описание* |
| [`DeltaHigh`](./ChartCluster.cs/svoistva/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./ChartCluster.cs/svoistva/DeltaLow.md) | *Описание* |
| [`MaxValues`](./ChartCluster.cs/svoistva/MaxValues.md) | *Описание* |
| [`IsUp`](./ChartCluster.cs/svoistva/IsUp.md) | *Описание* |
| [`Step`](./ChartCluster.cs/svoistva/Step.md) | *Описание* |
| [`Items`](./ChartCluster.cs/svoistva/Items.md) | *Описание* |


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

