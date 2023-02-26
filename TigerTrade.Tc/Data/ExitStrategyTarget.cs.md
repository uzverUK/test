
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
| [`ExitStrategyTarget`](./ExitStrategyTarget.cs/metody/ExitStrategyTarget.md) | *Описание* |
| [`ClearSl`](./ExitStrategyTarget.cs/metody/ClearSl.md) | *Описание* |
| [`RemoveSlTrailing`](./ExitStrategyTarget.cs/metody/RemoveSlTrailing.md) | *Описание* |
| [`ClearTp`](./ExitStrategyTarget.cs/metody/ClearTp.md) | *Описание* |
| [`RemoveTpTrailing`](./ExitStrategyTarget.cs/metody/RemoveTpTrailing.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`UpdateTime`](./ExitStrategyTarget.cs/svoistva/UpdateTime.md) | *Описание* |
| [`ID`](./ExitStrategyTarget.cs/svoistva/ID.md) | *Описание* |
| [`Quantity`](./ExitStrategyTarget.cs/svoistva/Quantity.md) | *Описание* |
| [`StopLossPrice`](./ExitStrategyTarget.cs/svoistva/StopLossPrice.md) | *Описание* |
| [`StopLossSize`](./ExitStrategyTarget.cs/svoistva/StopLossSize.md) | *Описание* |
| [`StopLossTrailingRange`](./ExitStrategyTarget.cs/svoistva/StopLossTrailingRange.md) | *Описание* |
| [`StopLossTrailingStep`](./ExitStrategyTarget.cs/svoistva/StopLossTrailingStep.md) | *Описание* |
| [`StopLossBreakevenProfit`](./ExitStrategyTarget.cs/svoistva/StopLossBreakevenProfit.md) | *Описание* |
| [`StopLossBreakevenPlus`](./ExitStrategyTarget.cs/svoistva/StopLossBreakevenPlus.md) | *Описание* |
| [`StopLossOffset`](./ExitStrategyTarget.cs/svoistva/StopLossOffset.md) | *Описание* |
| [`SlOrderID`](./ExitStrategyTarget.cs/svoistva/SlOrderID.md) | *Описание* |
| [`SlSynchronized`](./ExitStrategyTarget.cs/svoistva/SlSynchronized.md) | *Описание* |
| [`TakeProfitPrice`](./ExitStrategyTarget.cs/svoistva/TakeProfitPrice.md) | *Описание* |
| [`TakeProfitSize`](./ExitStrategyTarget.cs/svoistva/TakeProfitSize.md) | *Описание* |
| [`TakeProfitRange`](./ExitStrategyTarget.cs/svoistva/TakeProfitRange.md) | *Описание* |
| [`TakeProfitOffset`](./ExitStrategyTarget.cs/svoistva/TakeProfitOffset.md) | *Описание* |
| [`TakeProfitStopActive`](./ExitStrategyTarget.cs/svoistva/TakeProfitStopActive.md) | *Описание* |
| [`TpOrderID`](./ExitStrategyTarget.cs/svoistva/TpOrderID.md) | *Описание* |
| [`TpSynchronized`](./ExitStrategyTarget.cs/svoistva/TpSynchronized.md) | *Описание* |
| [`SlTpUpdateTime`](./ExitStrategyTarget.cs/svoistva/SlTpUpdateTime.md) | *Описание* |
| [`IsServerOrderTP`](./ExitStrategyTarget.cs/svoistva/IsServerOrderTP.md) | *Описание* |
| [`IsServerOrderSl`](./ExitStrategyTarget.cs/svoistva/IsServerOrderSl.md) | *Описание* |


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

