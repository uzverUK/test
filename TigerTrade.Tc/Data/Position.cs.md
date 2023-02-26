
# public sealed class Position
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class Position
```


## Методы
| Название | Описание |
| --- | --- |
| [`Position`](./Position.cs/metody/Position.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Symbol`](./Position.cs/svoistva/Symbol.md) | *Описание* |
| [`Account`](./Position.cs/svoistva/Account.md) | *Описание* |
| [`Register`](./Position.cs/svoistva/Register.md) | *Описание* |
| [`Quantity`](./Position.cs/svoistva/Quantity.md) | *Описание* |
| [`AvgPrice`](./Position.cs/svoistva/AvgPrice.md) | *Описание* |
| [`Liquidation`](./Position.cs/svoistva/Liquidation.md) | *Описание* |
| [`UnrealizedPnl`](./Position.cs/svoistva/UnrealizedPnl.md) | *Описание* |
| [`RealizedPnl`](./Position.cs/svoistva/RealizedPnl.md) | *Описание* |
| [`Comission`](./Position.cs/svoistva/Comission.md) | *Описание* |
| [`TpPrice`](./Position.cs/svoistva/TpPrice.md) | *Описание* |
| [`SlPrice`](./Position.cs/svoistva/SlPrice.md) | *Описание* |
| [`PosNumID`](./Position.cs/svoistva/PosNumID.md) | *Описание* |


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

