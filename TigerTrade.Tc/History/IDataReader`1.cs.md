
# public interface IDataReader<out T>
## Расположение
```csharp
namespace TigerTrade.Tc.History
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public interface IDataReader<out T>
```


## Методы
| Название | Описание |
| --- | --- |
| [`Read`](./IDataReader`1.cs/Методы/Read.md) | *Описание* |
| [`Reset`](./IDataReader`1.cs/Методы/Reset.md) | *Описание* |
| [`Dispose`](./IDataReader`1.cs/Методы/Dispose.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`IsEmpty`](./IDataReader`1.cs/Свойства/IsEmpty.md) | *Описание* |
| [`LastItem`](./IDataReader`1.cs/Свойства/LastItem.md) | *Описание* |
| [`PrevItem`](./IDataReader`1.cs/Свойства/PrevItem.md) | *Описание* |


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

