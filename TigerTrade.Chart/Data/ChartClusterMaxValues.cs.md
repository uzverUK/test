
# public sealed class ChartClusterMaxValues : IChartClusterMaxValues
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class ChartClusterMaxValues : IChartClusterMaxValues
```


## Методы
| Название | Описание |
| --- | --- |
| [`ChartClusterMaxValues`](./ChartClusterMaxValues.cs/metody/ChartClusterMaxValues.md) | *Описание* |
| [`Update`](./ChartClusterMaxValues.cs/metody/Update.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`MaxBid`](./ChartClusterMaxValues.cs/svoistva/MaxBid.md) | *Описание* |
| [`MaxAsk`](./ChartClusterMaxValues.cs/svoistva/MaxAsk.md) | *Описание* |
| [`MaxVolume`](./ChartClusterMaxValues.cs/svoistva/MaxVolume.md) | *Описание* |
| [`MaxTrades`](./ChartClusterMaxValues.cs/svoistva/MaxTrades.md) | *Описание* |
| [`MaxDelta`](./ChartClusterMaxValues.cs/svoistva/MaxDelta.md) | *Описание* |
| [`MinDelta`](./ChartClusterMaxValues.cs/svoistva/MinDelta.md) | *Описание* |
| [`MaxOpenPos`](./ChartClusterMaxValues.cs/svoistva/MaxOpenPos.md) | *Описание* |
| [`MinOpenPos`](./ChartClusterMaxValues.cs/svoistva/MinOpenPos.md) | *Описание* |
| [`Poc`](./ChartClusterMaxValues.cs/svoistva/Poc.md) | *Описание* |


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

