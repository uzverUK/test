
# public abstract class IndicatorSourceBase : INotifyPropertyChanged
## Расположение
```csharp
namespace TigerTrade.Chart.Indicators.Common
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public abstract class IndicatorSourceBase : INotifyPropertyChanged
```


## Методы
| Название | Описание |
| --- | --- |
| [`GetSeriesList`](./IndicatorSourceBase.cs/Методы/GetSeriesList.md) | *Описание* |
| [`GetSeries`](./IndicatorSourceBase.cs/Методы/GetSeries.md) | *Описание* |
| [`CopySettings`](./IndicatorSourceBase.cs/Методы/CopySettings.md) | *Описание* |
| [`ToString`](./IndicatorSourceBase.cs/Методы/ToString.md) | *Описание* |
| [`CloneSource`](./IndicatorSourceBase.cs/Методы/CloneSource.md) | *Описание* |
| [`SetSources`](./IndicatorSourceBase.cs/Методы/SetSources.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Name`](./IndicatorSourceBase.cs/Свойства/Name.md) | *Описание* |
| [`SelectedSeries`](./IndicatorSourceBase.cs/Свойства/SelectedSeries.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./IndicatorSourceBase.cs/События/PropertyChanged.md) | *Описание* |


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

