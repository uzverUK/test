
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
| [`RulerObject`](./RulerObject.cs/metody/RulerObject.md) | *Описание* |
| [`PrettyFormatTimeSpan`](./RulerObject.cs/metody/PrettyFormatTimeSpan.md) | *Описание* |
| [`ApplyTheme`](./RulerObject.cs/metody/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./RulerObject.cs/metody/CopyTemplate.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`xsuJlZ3bylFkXacpNF53`](./RulerObject.cs/svoistva/xsuJlZ3bylFkXacpNF53.md) | *Описание* |
| [`ShowInfoBars`](./RulerObject.cs/svoistva/ShowInfoBars.md) | *Описание* |
| [`ShowInfoTime`](./RulerObject.cs/svoistva/ShowInfoTime.md) | *Описание* |
| [`ShowInfoPrice`](./RulerObject.cs/svoistva/ShowInfoPrice.md) | *Описание* |
| [`ShowInfoTicks`](./RulerObject.cs/svoistva/ShowInfoTicks.md) | *Описание* |
| [`ShowInfoChange`](./RulerObject.cs/svoistva/ShowInfoChange.md) | *Описание* |
| [`ShowInfoVolume`](./RulerObject.cs/svoistva/ShowInfoVolume.md) | *Описание* |
| [`ShowInfoTrades`](./RulerObject.cs/svoistva/ShowInfoTrades.md) | *Описание* |
| [`ShowInfoDelta`](./RulerObject.cs/svoistva/ShowInfoDelta.md) | *Описание* |
| [`ShowInfoBid`](./RulerObject.cs/svoistva/ShowInfoBid.md) | *Описание* |
| [`ShowInfoAsk`](./RulerObject.cs/svoistva/ShowInfoAsk.md) | *Описание* |
| [`TextColor`](./RulerObject.cs/svoistva/TextColor.md) | *Описание* |


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

