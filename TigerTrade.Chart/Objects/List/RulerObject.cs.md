
# public sealed class RulerObject : LineObjectBase
## Расположение
```csharp
namespace TigerTrade.Chart.Objects.List
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class RulerObject : LineObjectBase
```


## Методы
| Название | Описание |
| --- | --- |
| [`RulerObject`](./RulerObject.cs/Методы/RulerObject.md) | *Описание* |
| [`PrettyFormatTimeSpan`](./RulerObject.cs/Методы/PrettyFormatTimeSpan.md) | *Описание* |
| [`ApplyTheme`](./RulerObject.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./RulerObject.cs/Методы/CopyTemplate.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`xsuJlZ3bylFkXacpNF53`](./RulerObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |
| [`ShowInfoBars`](./RulerObject.cs/Свойства/ShowInfoBars.md) | *Описание* |
| [`ShowInfoTime`](./RulerObject.cs/Свойства/ShowInfoTime.md) | *Описание* |
| [`ShowInfoPrice`](./RulerObject.cs/Свойства/ShowInfoPrice.md) | *Описание* |
| [`ShowInfoTicks`](./RulerObject.cs/Свойства/ShowInfoTicks.md) | *Описание* |
| [`ShowInfoChange`](./RulerObject.cs/Свойства/ShowInfoChange.md) | *Описание* |
| [`ShowInfoVolume`](./RulerObject.cs/Свойства/ShowInfoVolume.md) | *Описание* |
| [`ShowInfoTrades`](./RulerObject.cs/Свойства/ShowInfoTrades.md) | *Описание* |
| [`ShowInfoDelta`](./RulerObject.cs/Свойства/ShowInfoDelta.md) | *Описание* |
| [`ShowInfoBid`](./RulerObject.cs/Свойства/ShowInfoBid.md) | *Описание* |
| [`ShowInfoAsk`](./RulerObject.cs/Свойства/ShowInfoAsk.md) | *Описание* |
| [`TextColor`](./RulerObject.cs/Свойства/TextColor.md) | *Описание* |


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

