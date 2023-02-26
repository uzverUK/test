
# internal sealed class Orders
## Расположение
```csharp
namespace TigerTrade.Tc.Collections
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
internal sealed class Orders
```


## Методы
| Название | Описание |
| --- | --- |
| [`JJ1wAJvhyTr`](./Orders.cs/metody/JJ1wAJvhyTr.md) | *Описание* |
| [`xZdwAF7myFo`](./Orders.cs/metody/xZdwAF7myFo.md) | *Описание* |
| [`Ot1wAdHTLdT`](./Orders.cs/metody/Ot1wAdHTLdT.md) | *Описание* |
| [`drqwAC3LEfb`](./Orders.cs/metody/drqwAC3LEfb.md) | *Описание* |
| [`SV6wAzQYsNW`](./Orders.cs/metody/SV6wAzQYsNW.md) | *Описание* |
| [`J5awtySnmrG`](./Orders.cs/metody/J5awtySnmrG.md) | *Описание* |
| [`oUJwtqko1TX`](./Orders.cs/metody/oUJwtqko1TX.md) | *Описание* |
| [`Clear`](./Orders.cs/metody/Clear.md) | *Описание* |
| [`Orders`](./Orders.cs/metody/Orders.md) | *Описание* |


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

