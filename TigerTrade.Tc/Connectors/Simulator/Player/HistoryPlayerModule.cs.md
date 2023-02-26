
# public static class HistoryPlayerModule
## Расположение
```csharp
namespace TigerTrade.Tc.Connectors.Simulator.Player
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public static class HistoryPlayerModule
```


## Методы
| Название | Описание |
| --- | --- |
| [`Init`](./HistoryPlayerModule.cs/metody/Init.md) | *Описание* |
| [`Init`](./HistoryPlayerModule.cs/metody/Init.md) | *Описание* |
| [`Clear`](./HistoryPlayerModule.cs/metody/Clear.md) | *Описание* |
| [`Play`](./HistoryPlayerModule.cs/metody/Play.md) | *Описание* |
| [`Stop`](./HistoryPlayerModule.cs/metody/Stop.md) | *Описание* |
| [`Pause`](./HistoryPlayerModule.cs/metody/Pause.md) | *Описание* |
| [`Skip`](./HistoryPlayerModule.cs/metody/Skip.md) | *Описание* |
| [`SkipTo`](./HistoryPlayerModule.cs/metody/SkipTo.md) | *Описание* |
| [`SetSpeed`](./HistoryPlayerModule.cs/metody/SetSpeed.md) | *Описание* |
| [`GetState`](./HistoryPlayerModule.cs/metody/GetState.md) | *Описание* |
| [`GetStats`](./HistoryPlayerModule.cs/metody/GetStats.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`RecordDate`](./HistoryPlayerModule.cs/svoistva/RecordDate.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`StatsChanged;`](./HistoryPlayerModule.cs/sobytiya/StatsChanged;.md) | *Описание* |
| [`StateChanged;`](./HistoryPlayerModule.cs/sobytiya/StateChanged;.md) | *Описание* |


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

