
# public interface IChartClusterItem
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public interface IChartClusterItem
```


## Свойства
| Название | Описание |
| --- | --- |
| [`Price`](./IChartClusterItem.cs/Свойства/Price.md) | *Описание* |
| [`Bid`](./IChartClusterItem.cs/Свойства/Bid.md) | *Описание* |
| [`Ask`](./IChartClusterItem.cs/Свойства/Ask.md) | *Описание* |
| [`Volume`](./IChartClusterItem.cs/Свойства/Volume.md) | *Описание* |
| [`Delta`](./IChartClusterItem.cs/Свойства/Delta.md) | *Описание* |
| [`BidTrades`](./IChartClusterItem.cs/Свойства/BidTrades.md) | *Описание* |
| [`AskTrades`](./IChartClusterItem.cs/Свойства/AskTrades.md) | *Описание* |
| [`Trades`](./IChartClusterItem.cs/Свойства/Trades.md) | *Описание* |
| [`OpenPosBid`](./IChartClusterItem.cs/Свойства/OpenPosBid.md) | *Описание* |
| [`OpenPosAsk`](./IChartClusterItem.cs/Свойства/OpenPosAsk.md) | *Описание* |
| [`OpenPos`](./IChartClusterItem.cs/Свойства/OpenPos.md) | *Описание* |


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

