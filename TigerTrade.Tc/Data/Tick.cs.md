
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
| [`Tick`](./Tick.cs/Методы/Tick.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Symbol`](./Tick.cs/Свойства/Symbol.md) | *Описание* |
| [`Time`](./Tick.cs/Свойства/Time.md) | *Описание* |
| [`Price`](./Tick.cs/Свойства/Price.md) | *Описание* |
| [`Size`](./Tick.cs/Свойства/Size.md) | *Описание* |
| [`Bid`](./Tick.cs/Свойства/Bid.md) | *Описание* |
| [`BidSize`](./Tick.cs/Свойства/BidSize.md) | *Описание* |
| [`Ask`](./Tick.cs/Свойства/Ask.md) | *Описание* |
| [`AskSize`](./Tick.cs/Свойства/AskSize.md) | *Описание* |
| [`Side`](./Tick.cs/Свойства/Side.md) | *Описание* |
| [`OpenInterest`](./Tick.cs/Свойства/OpenInterest.md) | *Описание* |
| [`MarketCenter`](./Tick.cs/Свойства/MarketCenter.md) | *Описание* |
| [`Market`](./Tick.cs/Свойства/Market.md) | *Описание* |
| [`Conditions`](./Tick.cs/Свойства/Conditions.md) | *Описание* |
| [`NotQualified`](./Tick.cs/Свойства/NotQualified.md) | *Описание* |


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

