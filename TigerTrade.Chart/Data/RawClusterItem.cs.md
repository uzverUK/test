
# public sealed class RawClusterItem : IRawClusterItem
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class RawClusterItem : IRawClusterItem
```


## Методы
| Название | Описание |
| --- | --- |
| [`RawClusterItem`](./RawClusterItem.cs/metody/RawClusterItem.md) | *Описание* |
| [`RawClusterItem`](./RawClusterItem.cs/metody/RawClusterItem.md) | *Описание* |
| [`Add`](./RawClusterItem.cs/metody/Add.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Price`](./RawClusterItem.cs/svoistva/Price.md) | *Описание* |
| [`Bid`](./RawClusterItem.cs/svoistva/Bid.md) | *Описание* |
| [`Ask`](./RawClusterItem.cs/svoistva/Ask.md) | *Описание* |
| [`BidTrades`](./RawClusterItem.cs/svoistva/BidTrades.md) | *Описание* |
| [`AskTrades`](./RawClusterItem.cs/svoistva/AskTrades.md) | *Описание* |
| [`OpenPosBid`](./RawClusterItem.cs/svoistva/OpenPosBid.md) | *Описание* |
| [`OpenPosAsk`](./RawClusterItem.cs/svoistva/OpenPosAsk.md) | *Описание* |
| [`Volume`](./RawClusterItem.cs/svoistva/Volume.md) | *Описание* |
| [`Delta`](./RawClusterItem.cs/svoistva/Delta.md) | *Описание* |
| [`Trades`](./RawClusterItem.cs/svoistva/Trades.md) | *Описание* |
| [`OpenPos`](./RawClusterItem.cs/svoistva/OpenPos.md) | *Описание* |


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

