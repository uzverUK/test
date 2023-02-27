
# public sealed class ATRSource : IndicatorSourceBase
## Расположение
```csharp
namespace TigerTrade.Chart.Indicators.Sources
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class ATRSource : IndicatorSourceBase
```


## Методы
| Название | Описание |
| --- | --- |
| [`ATRSource`](./ATRSource.cs/Методы/ATRSource.md) | *Описание* |
| [`GetSeriesList`](./ATRSource.cs/Методы/GetSeriesList.md) | *Описание* |
| [`GetSeries`](./ATRSource.cs/Методы/GetSeries.md) | *Описание* |
| [`CopySettings`](./ATRSource.cs/Методы/CopySettings.md) | *Описание* |
| [`ToString`](./ATRSource.cs/Методы/ToString.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./ATRSource.cs/Свойства/Period.md) | *Описание* |


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

