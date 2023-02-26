
# public sealed class IchimokuSource : IndicatorSourceBase
## Расположение
```csharp
namespace TigerTrade.Chart.Indicators.Sources
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class IchimokuSource : IndicatorSourceBase
```


## Методы
| Название | Описание |
| --- | --- |
| [`IchimokuSource`](./IchimokuSource.cs/metody/IchimokuSource.md) | *Описание* |
| [`GetSeriesList`](./IchimokuSource.cs/metody/GetSeriesList.md) | *Описание* |
| [`GetSeries`](./IchimokuSource.cs/metody/GetSeries.md) | *Описание* |
| [`CopySettings`](./IchimokuSource.cs/metody/CopySettings.md) | *Описание* |
| [`ToString`](./IchimokuSource.cs/metody/ToString.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Period1`](./IchimokuSource.cs/svoistva/Period1.md) | *Описание* |
| [`Period2`](./IchimokuSource.cs/svoistva/Period2.md) | *Описание* |
| [`Period3`](./IchimokuSource.cs/svoistva/Period3.md) | *Описание* |
| [`Period4`](./IchimokuSource.cs/svoistva/Period4.md) | *Описание* |
| [`Period5`](./IchimokuSource.cs/svoistva/Period5.md) | *Описание* |


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

