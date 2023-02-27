
# public sealed class LineObject : LineObjectBase
## Расположение
```csharp
namespace TigerTrade.Chart.Objects.List
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class LineObject : LineObjectBase
```


## Методы
| Название | Описание |
| --- | --- |
| [`LineObject`](./LineObject.cs/Методы/LineObject.md) | *Описание* |
| [`CopyTemplate`](./LineObject.cs/Методы/CopyTemplate.md) | *Описание* |
| [`CheckAlert`](./LineObject.cs/Методы/CheckAlert.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`xsuJlZ3bylFkXacpNF53`](./LineObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |
| [`Alert`](./LineObject.cs/Свойства/Alert.md) | *Описание* |
| [`AlertMinDistance`](./LineObject.cs/Свойства/AlertMinDistance.md) | *Описание* |
| [`OpenStart`](./LineObject.cs/Свойства/OpenStart.md) | *Описание* |
| [`OpenEnd`](./LineObject.cs/Свойства/OpenEnd.md) | *Описание* |
| [`RefPoint`](./LineObject.cs/Свойства/RefPoint.md) | *Описание* |


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

