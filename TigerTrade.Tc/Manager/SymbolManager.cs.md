
# public static class SymbolManager
## Расположение
```csharp
namespace TigerTrade.Tc.Manager
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public static class SymbolManager
```


## Методы
| Название | Описание |
| --- | --- |
| [`LoadOrUpdate`](./SymbolManager.cs/Методы/LoadOrUpdate.md) | *Описание* |
| [`FireSymbolUpdatedEvent`](./SymbolManager.cs/Методы/FireSymbolUpdatedEvent.md) | *Описание* |
| [`Get`](./SymbolManager.cs/Методы/Get.md) | *Описание* |
| [`Get`](./SymbolManager.cs/Методы/Get.md) | *Описание* |
| [`GetAll`](./SymbolManager.cs/Методы/GetAll.md) | *Описание* |
| [`GetAllOptions`](./SymbolManager.cs/Методы/GetAllOptions.md) | *Описание* |
| [`Clear`](./SymbolManager.cs/Методы/Clear.md) | *Описание* |
| [`RiseSymbolsReady`](./SymbolManager.cs/Методы/RiseSymbolsReady.md) | *Описание* |
| [`RiseFavoritesReady`](./SymbolManager.cs/Методы/RiseFavoritesReady.md) | *Описание* |
| [`FindSwitchPair`](./SymbolManager.cs/Методы/FindSwitchPair.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`ClientSpecLastUpdate`](./SymbolManager.cs/Свойства/ClientSpecLastUpdate.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`Action`](./SymbolManager.cs/События/Action.md) | *Описание* |
| [`Action`](./SymbolManager.cs/События/Action.md) | *Описание* |
| [`SymbolUpdated;`](./SymbolManager.cs/События/SymbolUpdated;.md) | *Описание* |
| [`Action`](./SymbolManager.cs/События/Action.md) | *Описание* |


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

