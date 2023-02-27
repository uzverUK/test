
# internal class ConnectionIndicators : UserControl, IComponentConnector
## Расположение
```csharp
namespace TigerTrade.Tc.Config.UI
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
internal class ConnectionIndicators : UserControl, IComponentConnector
```


## Методы
| Название | Описание |
| --- | --- |
| [`ConnectionIndicators`](./ConnectionIndicators.cs/Методы/ConnectionIndicators.md) | *Описание* |
| [`roXwis3djh0(ogXycEOqcMglr0u6UVcN)`](./ConnectionIndicators.cs/Методы/roXwis3djh0(ogXycEOqcMglr0u6UVcN).md) | *Описание* |
| [`InitializeComponent`](./ConnectionIndicators.cs/Методы/InitializeComponent.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`DependencyProperty`](./ConnectionIndicators.cs/Свойства/DependencyProperty.md) | *Описание* |
| [`DependencyProperty`](./ConnectionIndicators.cs/Свойства/DependencyProperty.md) | *Описание* |
| [`ConnectionID`](./ConnectionIndicators.cs/Свойства/ConnectionID.md) | *Описание* |
| [`Indicator`](./ConnectionIndicators.cs/Свойства/Indicator.md) | *Описание* |
| [`IndicatorClickedCommand`](./ConnectionIndicators.cs/Свойства/IndicatorClickedCommand.md) | *Описание* |
| [`Indicators`](./ConnectionIndicators.cs/Свойства/Indicators.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`IndicatorChanged;`](./ConnectionIndicators.cs/События/IndicatorChanged;.md) | *Описание* |


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

