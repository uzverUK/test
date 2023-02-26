
# public sealed class ChaikinMoneyFlowSource : IndicatorSourceBase
## Расположение
```csharp
namespace TigerTrade.Chart.Indicators.Sources
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class ChaikinMoneyFlowSource : IndicatorSourceBase
```


## Методы
| Название | Описание |
| --- | --- |
| [`ChaikinMoneyFlowSource`](./ChaikinMoneyFlowSource.cs/metody/ChaikinMoneyFlowSource.md) | *Описание* |
| [`GetSeriesList`](./ChaikinMoneyFlowSource.cs/metody/GetSeriesList.md) | *Описание* |
| [`GetSeries`](./ChaikinMoneyFlowSource.cs/metody/GetSeries.md) | *Описание* |
| [`CopySettings`](./ChaikinMoneyFlowSource.cs/metody/CopySettings.md) | *Описание* |
| [`ToString`](./ChaikinMoneyFlowSource.cs/metody/ToString.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./ChaikinMoneyFlowSource.cs/svoistva/Period.md) | *Описание* |


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

