
# public static class LogManager
## Расположение
```csharp
namespace TigerTrade.Core.Utils.Logging
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public static class LogManager
```


## Методы
| Название | Описание |
| --- | --- |
| [`Init`](./LogManager.cs/Методы/Init.md) | *Описание* |
| [`WriteError`](./LogManager.cs/Методы/WriteError.md) | *Описание* |
| [`WriteError`](./LogManager.cs/Методы/WriteError.md) | *Описание* |
| [`WriteError`](./LogManager.cs/Методы/WriteError.md) | *Описание* |
| [`WriteInfo`](./LogManager.cs/Методы/WriteInfo.md) | *Описание* |
| [`WriteFake`](./LogManager.cs/Методы/WriteFake.md) | *Описание* |
| [`GetErrorLog`](./LogManager.cs/Методы/GetErrorLog.md) | *Описание* |
| [`GetWorkLog`](./LogManager.cs/Методы/GetWorkLog.md) | *Описание* |
| [`WriteLogs`](./LogManager.cs/Методы/WriteLogs.md) | *Описание* |
| [`MG3jDBcyfJj`](./LogManager.cs/Методы/MG3jDBcyfJj.md) | *Описание* |
| [`yHPwACjDsbb5k519doWX`](./LogManager.cs/Методы/yHPwACjDsbb5k519doWX.md) | *Описание* |
| [`VNKjDc6qvia`](./LogManager.cs/Методы/VNKjDc6qvia.md) | *Описание* |
| [`MiKjDEE8ZWn`](./LogManager.cs/Методы/MiKjDEE8ZWn.md) | *Описание* |
| [`R6bjDetmRXl`](./LogManager.cs/Методы/R6bjDetmRXl.md) | *Описание* |
| [`BJ8cOSjDTKSexX17nQEk`](./LogManager.cs/Методы/BJ8cOSjDTKSexX17nQEk.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Type`](./LogManager.cs/Свойства/Type.md) | *Описание* |
| [`Message`](./LogManager.cs/Свойства/Message.md) | *Описание* |
| [`Message`](./LogManager.cs/Свойства/Message.md) | *Описание* |


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

