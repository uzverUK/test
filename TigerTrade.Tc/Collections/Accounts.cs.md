
# internal sealed class Accounts
## Расположение
```csharp
namespace TigerTrade.Tc.Collections
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
internal sealed class Accounts
```


## Методы
| Название | Описание |
| --- | --- |
| [`L5YwAeGr3rl`](./Accounts.cs/metody/L5YwAeGr3rl.md) | *Описание* |
| [`k1hwA8704AJ`](./Accounts.cs/metody/k1hwA8704AJ.md) | *Описание* |
| [`xY2wAurG7xy`](./Accounts.cs/metody/xY2wAurG7xy.md) | *Описание* |
| [`qH5wAaiBWl0`](./Accounts.cs/metody/qH5wAaiBWl0.md) | *Описание* |
| [`Accounts`](./Accounts.cs/metody/Accounts.md) | *Описание* |


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

