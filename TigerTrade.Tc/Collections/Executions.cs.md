
# internal sealed class Executions
## Расположение
```csharp
namespace TigerTrade.Tc.Collections
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
internal sealed class Executions
```


## Методы
| Название | Описание |
| --- | --- |
| [`dUlwtptFJQi`](./Executions.cs/Методы/dUlwtptFJQi.md) | *Описание* |
| [`KSBwtKDnkq2`](./Executions.cs/Методы/KSBwtKDnkq2.md) | *Описание* |
| [`dJOwtlbjkxN`](./Executions.cs/Методы/dJOwtlbjkxN.md) | *Описание* |
| [`oQfwt5Huf1s`](./Executions.cs/Методы/oQfwt5Huf1s.md) | *Описание* |
| [`FggwtLlyXjX`](./Executions.cs/Методы/FggwtLlyXjX.md) | *Описание* |
| [`Clear`](./Executions.cs/Методы/Clear.md) | *Описание* |
| [`Executions`](./Executions.cs/Методы/Executions.md) | *Описание* |


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

