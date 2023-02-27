
# public sealed class Execution
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class Execution
```


## Методы
| Название | Описание |
| --- | --- |
| [`Execution`](./Execution.cs/Методы/Execution.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`ID`](./Execution.cs/Свойства/ID.md) | *Описание* |
| [`ExecutionID`](./Execution.cs/Свойства/ExecutionID.md) | *Описание* |
| [`OrderID`](./Execution.cs/Свойства/OrderID.md) | *Описание* |
| [`Symbol`](./Execution.cs/Свойства/Symbol.md) | *Описание* |
| [`Account`](./Execution.cs/Свойства/Account.md) | *Описание* |
| [`Currency`](./Execution.cs/Свойства/Currency.md) | *Описание* |
| [`Time`](./Execution.cs/Свойства/Time.md) | *Описание* |
| [`Price`](./Execution.cs/Свойства/Price.md) | *Описание* |
| [`Quantity`](./Execution.cs/Свойства/Quantity.md) | *Описание* |
| [`Side`](./Execution.cs/Свойства/Side.md) | *Описание* |
| [`Comission`](./Execution.cs/Свойства/Comission.md) | *Описание* |
| [`RealizedPnl`](./Execution.cs/Свойства/RealizedPnl.md) | *Описание* |
| [`Connection`](./Execution.cs/Свойства/Connection.md) | *Описание* |


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

