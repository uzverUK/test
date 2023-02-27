
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
| [`Position`](./Position.cs/Методы/Position.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Symbol`](./Position.cs/Свойства/Symbol.md) | *Описание* |
| [`Account`](./Position.cs/Свойства/Account.md) | *Описание* |
| [`Register`](./Position.cs/Свойства/Register.md) | *Описание* |
| [`Quantity`](./Position.cs/Свойства/Quantity.md) | *Описание* |
| [`AvgPrice`](./Position.cs/Свойства/AvgPrice.md) | *Описание* |
| [`Liquidation`](./Position.cs/Свойства/Liquidation.md) | *Описание* |
| [`UnrealizedPnl`](./Position.cs/Свойства/UnrealizedPnl.md) | *Описание* |
| [`RealizedPnl`](./Position.cs/Свойства/RealizedPnl.md) | *Описание* |
| [`Comission`](./Position.cs/Свойства/Comission.md) | *Описание* |
| [`TpPrice`](./Position.cs/Свойства/TpPrice.md) | *Описание* |
| [`SlPrice`](./Position.cs/Свойства/SlPrice.md) | *Описание* |
| [`PosNumID`](./Position.cs/Свойства/PosNumID.md) | *Описание* |


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

