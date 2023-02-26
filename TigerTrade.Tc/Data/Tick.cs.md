
# public sealed class Tick
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class Tick
```


## Методы
| Название | Описание |
| --- | --- |
| [`Tick`](./Tick.cs/metody/Tick.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Symbol`](./Tick.cs/svoistva/Symbol.md) | *Описание* |
| [`Time`](./Tick.cs/svoistva/Time.md) | *Описание* |
| [`Price`](./Tick.cs/svoistva/Price.md) | *Описание* |
| [`Size`](./Tick.cs/svoistva/Size.md) | *Описание* |
| [`Bid`](./Tick.cs/svoistva/Bid.md) | *Описание* |
| [`BidSize`](./Tick.cs/svoistva/BidSize.md) | *Описание* |
| [`Ask`](./Tick.cs/svoistva/Ask.md) | *Описание* |
| [`AskSize`](./Tick.cs/svoistva/AskSize.md) | *Описание* |
| [`Side`](./Tick.cs/svoistva/Side.md) | *Описание* |
| [`OpenInterest`](./Tick.cs/svoistva/OpenInterest.md) | *Описание* |
| [`MarketCenter`](./Tick.cs/svoistva/MarketCenter.md) | *Описание* |
| [`Market`](./Tick.cs/svoistva/Market.md) | *Описание* |
| [`Conditions`](./Tick.cs/svoistva/Conditions.md) | *Описание* |
| [`NotQualified`](./Tick.cs/svoistva/NotQualified.md) | *Описание* |


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

