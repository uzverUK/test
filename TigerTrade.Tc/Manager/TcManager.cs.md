
# public static class TcManager
## Расположение
```csharp
namespace TigerTrade.Tc.Manager
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public static class TcManager
```


## Методы
| Название | Описание |
| --- | --- |
| [`Load`](./TcManager.cs/Методы/Load.md) | *Описание* |
| [`LoadSimulator`](./TcManager.cs/Методы/LoadSimulator.md) | *Описание* |
| [`Save`](./TcManager.cs/Методы/Save.md) | *Описание* |
| [`SaveSettings`](./TcManager.cs/Методы/SaveSettings.md) | *Описание* |
| [`SetPositionPartClose`](./TcManager.cs/Методы/SetPositionPartClose.md) | *Описание* |
| [`SetDynamicStopLoss`](./TcManager.cs/Методы/SetDynamicStopLoss.md) | *Описание* |
| [`SetDynamicTakeProfit`](./TcManager.cs/Методы/SetDynamicTakeProfit.md) | *Описание* |
| [`SetServerStopLoss`](./TcManager.cs/Методы/SetServerStopLoss.md) | *Описание* |
| [`SetServerTakeProfit`](./TcManager.cs/Методы/SetServerTakeProfit.md) | *Описание* |
| [`SetCancelOrdersOnClose`](./TcManager.cs/Методы/SetCancelOrdersOnClose.md) | *Описание* |
| [`SetViewDeletedSymbols`](./TcManager.cs/Методы/SetViewDeletedSymbols.md) | *Описание* |
| [`SetViewOptionsSymbols`](./TcManager.cs/Методы/SetViewOptionsSymbols.md) | *Описание* |
| [`GetMarketDataConnections`](./TcManager.cs/Методы/GetMarketDataConnections.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`CommonDataPath;`](./TcManager.cs/Свойства/CommonDataPath;.md) | *Описание* |
| [`AccountValidator`](./TcManager.cs/Свойства/AccountValidator.md) | *Описание* |
| [`SortSettings`](./TcManager.cs/Свойства/SortSettings.md) | *Описание* |


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

