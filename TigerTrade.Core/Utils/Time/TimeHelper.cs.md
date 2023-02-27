
# public static class TimeHelper
## Расположение
```csharp
namespace TigerTrade.Core.Utils.Time
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public static class TimeHelper
```


## Методы
| Название | Описание |
| --- | --- |
| [`GetCurrTime`](./TimeHelper.cs/Методы/GetCurrTime.md) | *Описание* |
| [`GetCurrDate`](./TimeHelper.cs/Методы/GetCurrDate.md) | *Описание* |
| [`GetCityTime`](./TimeHelper.cs/Методы/GetCityTime.md) | *Описание* |
| [`GetSessionOffset`](./TimeHelper.cs/Методы/GetSessionOffset.md) | *Описание* |
| [`GetSessionOffsetTs`](./TimeHelper.cs/Методы/GetSessionOffsetTs.md) | *Описание* |
| [`GetSessionDate`](./TimeHelper.cs/Методы/GetSessionDate.md) | *Описание* |
| [`GetSessionDate`](./TimeHelper.cs/Методы/GetSessionDate.md) | *Описание* |
| [`IsInvalidTime`](./TimeHelper.cs/Методы/IsInvalidTime.md) | *Описание* |
| [`FormatTime`](./TimeHelper.cs/Методы/FormatTime.md) | *Описание* |
| [`ConvertFromExchangeTimeToUtc`](./TimeHelper.cs/Методы/ConvertFromExchangeTimeToUtc.md) | *Описание* |
| [`CorrectLocalTime`](./TimeHelper.cs/Методы/CorrectLocalTime.md) | *Описание* |
| [`CorrectUtcTime`](./TimeHelper.cs/Методы/CorrectUtcTime.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`PlayerTimeProvider`](./TimeHelper.cs/Свойства/PlayerTimeProvider.md) | *Описание* |
| [`MoscowTimeOffsetUtc`](./TimeHelper.cs/Свойства/MoscowTimeOffsetUtc.md) | *Описание* |
| [`EasternTimeOffsetUtc`](./TimeHelper.cs/Свойства/EasternTimeOffsetUtc.md) | *Описание* |
| [`CentralTimeOffsetUtc`](./TimeHelper.cs/Свойства/CentralTimeOffsetUtc.md) | *Описание* |
| [`LocalTime`](./TimeHelper.cs/Свойства/LocalTime.md) | *Описание* |
| [`AppLocalTime`](./TimeHelper.cs/Свойства/AppLocalTime.md) | *Описание* |


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

