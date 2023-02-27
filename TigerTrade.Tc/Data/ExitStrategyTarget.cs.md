
# public sealed class ExitStrategyTarget
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class ExitStrategyTarget
```


## Методы
| Название | Описание |
| --- | --- |
| [`ExitStrategyTarget`](./ExitStrategyTarget.cs/Методы/ExitStrategyTarget.md) | *Описание* |
| [`ClearSl`](./ExitStrategyTarget.cs/Методы/ClearSl.md) | *Описание* |
| [`RemoveSlTrailing`](./ExitStrategyTarget.cs/Методы/RemoveSlTrailing.md) | *Описание* |
| [`ClearTp`](./ExitStrategyTarget.cs/Методы/ClearTp.md) | *Описание* |
| [`RemoveTpTrailing`](./ExitStrategyTarget.cs/Методы/RemoveTpTrailing.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`UpdateTime`](./ExitStrategyTarget.cs/Свойства/UpdateTime.md) | *Описание* |
| [`ID`](./ExitStrategyTarget.cs/Свойства/ID.md) | *Описание* |
| [`Quantity`](./ExitStrategyTarget.cs/Свойства/Quantity.md) | *Описание* |
| [`StopLossPrice`](./ExitStrategyTarget.cs/Свойства/StopLossPrice.md) | *Описание* |
| [`StopLossSize`](./ExitStrategyTarget.cs/Свойства/StopLossSize.md) | *Описание* |
| [`StopLossTrailingRange`](./ExitStrategyTarget.cs/Свойства/StopLossTrailingRange.md) | *Описание* |
| [`StopLossTrailingStep`](./ExitStrategyTarget.cs/Свойства/StopLossTrailingStep.md) | *Описание* |
| [`StopLossBreakevenProfit`](./ExitStrategyTarget.cs/Свойства/StopLossBreakevenProfit.md) | *Описание* |
| [`StopLossBreakevenPlus`](./ExitStrategyTarget.cs/Свойства/StopLossBreakevenPlus.md) | *Описание* |
| [`StopLossOffset`](./ExitStrategyTarget.cs/Свойства/StopLossOffset.md) | *Описание* |
| [`SlOrderID`](./ExitStrategyTarget.cs/Свойства/SlOrderID.md) | *Описание* |
| [`SlSynchronized`](./ExitStrategyTarget.cs/Свойства/SlSynchronized.md) | *Описание* |
| [`TakeProfitPrice`](./ExitStrategyTarget.cs/Свойства/TakeProfitPrice.md) | *Описание* |
| [`TakeProfitSize`](./ExitStrategyTarget.cs/Свойства/TakeProfitSize.md) | *Описание* |
| [`TakeProfitRange`](./ExitStrategyTarget.cs/Свойства/TakeProfitRange.md) | *Описание* |
| [`TakeProfitOffset`](./ExitStrategyTarget.cs/Свойства/TakeProfitOffset.md) | *Описание* |
| [`TakeProfitStopActive`](./ExitStrategyTarget.cs/Свойства/TakeProfitStopActive.md) | *Описание* |
| [`TpOrderID`](./ExitStrategyTarget.cs/Свойства/TpOrderID.md) | *Описание* |
| [`TpSynchronized`](./ExitStrategyTarget.cs/Свойства/TpSynchronized.md) | *Описание* |
| [`SlTpUpdateTime`](./ExitStrategyTarget.cs/Свойства/SlTpUpdateTime.md) | *Описание* |
| [`IsServerOrderTP`](./ExitStrategyTarget.cs/Свойства/IsServerOrderTP.md) | *Описание* |
| [`IsServerOrderSl`](./ExitStrategyTarget.cs/Свойства/IsServerOrderSl.md) | *Описание* |


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

