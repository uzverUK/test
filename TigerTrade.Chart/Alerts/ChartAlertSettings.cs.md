
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
| [`Copy`](./ChartAlertSettings.cs/Методы/Copy.md) | *Описание* |
| [`Equals`](./ChartAlertSettings.cs/Методы/Equals.md) | *Описание* |
| [`GetHashCode`](./ChartAlertSettings.cs/Методы/GetHashCode.md) | *Описание* |
| [`ChartAlertSettings`](./ChartAlertSettings.cs/Методы/ChartAlertSettings.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Active`](./ChartAlertSettings.cs/Свойства/Active.md) | *Описание* |
| [`Execution`](./ChartAlertSettings.cs/Свойства/Execution.md) | *Описание* |
| [`Expiration`](./ChartAlertSettings.cs/Свойства/Expiration.md) | *Описание* |
| [`PlaySound`](./ChartAlertSettings.cs/Свойства/PlaySound.md) | *Описание* |
| [`Signal`](./ChartAlertSettings.cs/Свойства/Signal.md) | *Описание* |
| [`Duration`](./ChartAlertSettings.cs/Свойства/Duration.md) | *Описание* |
| [`ShowPopup`](./ChartAlertSettings.cs/Свойства/ShowPopup.md) | *Описание* |
| [`SendEmail`](./ChartAlertSettings.cs/Свойства/SendEmail.md) | *Описание* |
| [`SendTelegram`](./ChartAlertSettings.cs/Свойства/SendTelegram.md) | *Описание* |
| [`Message`](./ChartAlertSettings.cs/Свойства/Message.md) | *Описание* |
| [`Log`](./ChartAlertSettings.cs/Свойства/Log.md) | *Описание* |
| [`IsActive`](./ChartAlertSettings.cs/Свойства/IsActive.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ChartAlertSettings.cs/События/PropertyChanged.md) | *Описание* |


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

