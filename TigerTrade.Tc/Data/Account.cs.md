
# public sealed class Account
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class Account
```


## Методы
| Название | Описание |
| --- | --- |
| [`Account`](./Account.cs/metody/Account.md) | *Описание* |
| [`GetUniqueID`](./Account.cs/metody/GetUniqueID.md) | *Описание* |
| [`GetConnectionID`](./Account.cs/metody/GetConnectionID.md) | *Описание* |
| [`ToString`](./Account.cs/metody/ToString.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Connection`](./Account.cs/svoistva/Connection.md) | *Описание* |
| [`ConnectionID`](./Account.cs/svoistva/ConnectionID.md) | *Описание* |
| [`Name`](./Account.cs/svoistva/Name.md) | *Описание* |
| [`Currency`](./Account.cs/svoistva/Currency.md) | *Описание* |
| [`Union`](./Account.cs/svoistva/Union.md) | *Описание* |
| [`Simulator`](./Account.cs/svoistva/Simulator.md) | *Описание* |
| [`Trust`](./Account.cs/svoistva/Trust.md) | *Описание* |
| [`IsLive`](./Account.cs/svoistva/IsLive.md) | *Описание* |


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

