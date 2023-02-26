
# public sealed class ChartAlertSettings : INotifyPropertyChanged
## Расположение
```csharp
namespace TigerTrade.Chart.Alerts
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class ChartAlertSettings : INotifyPropertyChanged
```


## Методы
| Название | Описание |
| --- | --- |
| [`Copy`](./ChartAlertSettings.cs/metody/Copy.md) | *Описание* |
| [`Equals`](./ChartAlertSettings.cs/metody/Equals.md) | *Описание* |
| [`GetHashCode`](./ChartAlertSettings.cs/metody/GetHashCode.md) | *Описание* |
| [`ChartAlertSettings`](./ChartAlertSettings.cs/metody/ChartAlertSettings.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Active`](./ChartAlertSettings.cs/svoistva/Active.md) | *Описание* |
| [`Execution`](./ChartAlertSettings.cs/svoistva/Execution.md) | *Описание* |
| [`Expiration`](./ChartAlertSettings.cs/svoistva/Expiration.md) | *Описание* |
| [`PlaySound`](./ChartAlertSettings.cs/svoistva/PlaySound.md) | *Описание* |
| [`Signal`](./ChartAlertSettings.cs/svoistva/Signal.md) | *Описание* |
| [`Duration`](./ChartAlertSettings.cs/svoistva/Duration.md) | *Описание* |
| [`ShowPopup`](./ChartAlertSettings.cs/svoistva/ShowPopup.md) | *Описание* |
| [`SendEmail`](./ChartAlertSettings.cs/svoistva/SendEmail.md) | *Описание* |
| [`SendTelegram`](./ChartAlertSettings.cs/svoistva/SendTelegram.md) | *Описание* |
| [`Message`](./ChartAlertSettings.cs/svoistva/Message.md) | *Описание* |
| [`Log`](./ChartAlertSettings.cs/svoistva/Log.md) | *Описание* |
| [`IsActive`](./ChartAlertSettings.cs/svoistva/IsActive.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ChartAlertSettings.cs/sobytiya/PropertyChanged.md) | *Описание* |


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

