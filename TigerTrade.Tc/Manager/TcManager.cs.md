
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
| [`Load`](./TcManager.cs/metody/Load.md) | *Описание* |
| [`LoadSimulator`](./TcManager.cs/metody/LoadSimulator.md) | *Описание* |
| [`Save`](./TcManager.cs/metody/Save.md) | *Описание* |
| [`SaveSettings`](./TcManager.cs/metody/SaveSettings.md) | *Описание* |
| [`SetPositionPartClose`](./TcManager.cs/metody/SetPositionPartClose.md) | *Описание* |
| [`SetDynamicStopLoss`](./TcManager.cs/metody/SetDynamicStopLoss.md) | *Описание* |
| [`SetDynamicTakeProfit`](./TcManager.cs/metody/SetDynamicTakeProfit.md) | *Описание* |
| [`SetServerStopLoss`](./TcManager.cs/metody/SetServerStopLoss.md) | *Описание* |
| [`SetServerTakeProfit`](./TcManager.cs/metody/SetServerTakeProfit.md) | *Описание* |
| [`SetCancelOrdersOnClose`](./TcManager.cs/metody/SetCancelOrdersOnClose.md) | *Описание* |
| [`SetViewDeletedSymbols`](./TcManager.cs/metody/SetViewDeletedSymbols.md) | *Описание* |
| [`SetViewOptionsSymbols`](./TcManager.cs/metody/SetViewOptionsSymbols.md) | *Описание* |
| [`GetMarketDataConnections`](./TcManager.cs/metody/GetMarketDataConnections.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`CommonDataPath;`](./TcManager.cs/svoistva/CommonDataPath;.md) | *Описание* |
| [`AccountValidator`](./TcManager.cs/svoistva/AccountValidator.md) | *Описание* |
| [`SortSettings`](./TcManager.cs/svoistva/SortSettings.md) | *Описание* |


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

