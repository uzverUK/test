
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
| [`ChartCluster`](./ChartCluster.cs/Методы/ChartCluster.md) | *Описание* |
| [`AddTick`](./ChartCluster.cs/Методы/AddTick.md) | *Описание* |
| [`AddItem`](./ChartCluster.cs/Методы/AddItem.md) | *Описание* |
| [`AddCluster`](./ChartCluster.cs/Методы/AddCluster.md) | *Описание* |
| [`UpdateData`](./ChartCluster.cs/Методы/UpdateData.md) | *Описание* |
| [`GetItem`](./ChartCluster.cs/Методы/GetItem.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Time`](./ChartCluster.cs/Свойства/Time.md) | *Описание* |
| [`OpenTime`](./ChartCluster.cs/Свойства/OpenTime.md) | *Описание* |
| [`CloseTime`](./ChartCluster.cs/Свойства/CloseTime.md) | *Описание* |
| [`Open`](./ChartCluster.cs/Свойства/Open.md) | *Описание* |
| [`High`](./ChartCluster.cs/Свойства/High.md) | *Описание* |
| [`Low`](./ChartCluster.cs/Свойства/Low.md) | *Описание* |
| [`Close`](./ChartCluster.cs/Свойства/Close.md) | *Описание* |
| [`Bid`](./ChartCluster.cs/Свойства/Bid.md) | *Описание* |
| [`Ask`](./ChartCluster.cs/Свойства/Ask.md) | *Описание* |
| [`BidTrades`](./ChartCluster.cs/Свойства/BidTrades.md) | *Описание* |
| [`AskTrades`](./ChartCluster.cs/Свойства/AskTrades.md) | *Описание* |
| [`OpenPos`](./ChartCluster.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosHigh`](./ChartCluster.cs/Свойства/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./ChartCluster.cs/Свойства/OpenPosLow.md) | *Описание* |
| [`OpenPosBidChg`](./ChartCluster.cs/Свойства/OpenPosBidChg.md) | *Описание* |
| [`OpenPosAskChg`](./ChartCluster.cs/Свойства/OpenPosAskChg.md) | *Описание* |
| [`Volume`](./ChartCluster.cs/Свойства/Volume.md) | *Описание* |
| [`Delta`](./ChartCluster.cs/Свойства/Delta.md) | *Описание* |
| [`Trades`](./ChartCluster.cs/Свойства/Trades.md) | *Описание* |
| [`OpenPosChg`](./ChartCluster.cs/Свойства/OpenPosChg.md) | *Описание* |
| [`DeltaHigh`](./ChartCluster.cs/Свойства/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./ChartCluster.cs/Свойства/DeltaLow.md) | *Описание* |
| [`MaxValues`](./ChartCluster.cs/Свойства/MaxValues.md) | *Описание* |
| [`IsUp`](./ChartCluster.cs/Свойства/IsUp.md) | *Описание* |
| [`Step`](./ChartCluster.cs/Свойства/Step.md) | *Описание* |
| [`Items`](./ChartCluster.cs/Свойства/Items.md) | *Описание* |


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

