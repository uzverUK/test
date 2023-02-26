
# public sealed class ChartClusterItem : IChartClusterItem
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class ChartClusterItem : IChartClusterItem
```


## Методы
| Название | Описание |
| --- | --- |
| [`ChartClusterItem`](./ChartClusterItem.cs/metody/ChartClusterItem.md) | *Описание* |
| [`ChartClusterItem`](./ChartClusterItem.cs/metody/ChartClusterItem.md) | *Описание* |
| [`Add`](./ChartClusterItem.cs/metody/Add.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Price`](./ChartClusterItem.cs/svoistva/Price.md) | *Описание* |
| [`Bid`](./ChartClusterItem.cs/svoistva/Bid.md) | *Описание* |
| [`Ask`](./ChartClusterItem.cs/svoistva/Ask.md) | *Описание* |
| [`BidTrades`](./ChartClusterItem.cs/svoistva/BidTrades.md) | *Описание* |
| [`AskTrades`](./ChartClusterItem.cs/svoistva/AskTrades.md) | *Описание* |
| [`OpenPosBid`](./ChartClusterItem.cs/svoistva/OpenPosBid.md) | *Описание* |
| [`OpenPosAsk`](./ChartClusterItem.cs/svoistva/OpenPosAsk.md) | *Описание* |
| [`Delta`](./ChartClusterItem.cs/svoistva/Delta.md) | *Описание* |
| [`Trades`](./ChartClusterItem.cs/svoistva/Trades.md) | *Описание* |
| [`OpenPos`](./ChartClusterItem.cs/svoistva/OpenPos.md) | *Описание* |


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

