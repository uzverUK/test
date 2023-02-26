
# public sealed class TicksRequest
## Расположение
```csharp
namespace TigerTrade.Tc.History
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class TicksRequest
```


## Методы
| Название | Описание |
| --- | --- |
| [`TicksRequest`](./TicksRequest.cs/metody/TicksRequest.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Symbol`](./TicksRequest.cs/svoistva/Symbol.md) | *Описание* |
| [`RequestID`](./TicksRequest.cs/svoistva/RequestID.md) | *Описание* |
| [`TargetID`](./TicksRequest.cs/svoistva/TargetID.md) | *Описание* |
| [`CustomData`](./TicksRequest.cs/svoistva/CustomData.md) | *Описание* |


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

