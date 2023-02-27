
# public sealed class TimeRangeObject : PolygonObjectBase
## Расположение
```csharp
namespace TigerTrade.Chart.Objects.List
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class TimeRangeObject : PolygonObjectBase
```


## Методы
| Название | Описание |
| --- | --- |
| [`DrawControlPoints`](./TimeRangeObject.cs/Методы/DrawControlPoints.md) | *Описание* |
| [`GetControlPoint`](./TimeRangeObject.cs/Методы/GetControlPoint.md) | *Описание* |
| [`TimeRangeObject`](./TimeRangeObject.cs/Методы/TimeRangeObject.md) | *Описание* |
| [`ey9wOk3RwAcjmml8vF1J`](./TimeRangeObject.cs/Методы/ey9wOk3RwAcjmml8vF1J.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`xsuJlZ3bylFkXacpNF53`](./TimeRangeObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |
| [`m0E3R3eeWT4;`](./TimeRangeObject.cs/Свойства/m0E3R3eeWT4;.md) | *Описание* |
| [`IkF3RsY9b11;`](./TimeRangeObject.cs/Свойства/IkF3RsY9b11;.md) | *Описание* |
| [`Center;`](./TimeRangeObject.cs/Свойства/Center;.md) | *Описание* |
| [`qsf3RUZXhNl;`](./TimeRangeObject.cs/Свойства/qsf3RUZXhNl;.md) | *Описание* |
| [`Dhq3RBLC45X;`](./TimeRangeObject.cs/Свойства/Dhq3RBLC45X;.md) | *Описание* |


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

