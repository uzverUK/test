
# public sealed class Portfolio
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class Portfolio
```


## Методы
| Название | Описание |
| --- | --- |
| [`Portfolio`](./Portfolio.cs/Методы/Portfolio.md) | *Описание* |
| [`ToString`](./Portfolio.cs/Методы/ToString.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Connection`](./Portfolio.cs/Свойства/Connection.md) | *Описание* |
| [`ConnectionID`](./Portfolio.cs/Свойства/ConnectionID.md) | *Описание* |
| [`Name`](./Portfolio.cs/Свойства/Name.md) | *Описание* |
| [`Currency`](./Portfolio.cs/Свойства/Currency.md) | *Описание* |
| [`Register`](./Portfolio.cs/Свойства/Register.md) | *Описание* |
| [`Leverage`](./Portfolio.cs/Свойства/Leverage.md) | *Описание* |
| [`Balance`](./Portfolio.cs/Свойства/Balance.md) | *Описание* |
| [`UsedMargin`](./Portfolio.cs/Свойства/UsedMargin.md) | *Описание* |
| [`FreeMargin`](./Portfolio.cs/Свойства/FreeMargin.md) | *Описание* |
| [`UnrealizedPnl`](./Portfolio.cs/Свойства/UnrealizedPnl.md) | *Описание* |
| [`RealizedPnl`](./Portfolio.cs/Свойства/RealizedPnl.md) | *Описание* |
| [`Comission`](./Portfolio.cs/Свойства/Comission.md) | *Описание* |
| [`Precision`](./Portfolio.cs/Свойства/Precision.md) | *Описание* |
| [`PortfolioID`](./Portfolio.cs/Свойства/PortfolioID.md) | *Описание* |


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

