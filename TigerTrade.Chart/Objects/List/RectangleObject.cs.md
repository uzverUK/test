
# public class RectangleObject : PolygonObjectBase
## Расположение
```csharp
namespace TigerTrade.Chart.Objects.List
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public class RectangleObject : PolygonObjectBase
```


## Методы
| Название | Описание |
| --- | --- |
| [`DrawControlPoints`](./RectangleObject.cs/Методы/DrawControlPoints.md) | *Описание* |
| [`GetControlPoint`](./RectangleObject.cs/Методы/GetControlPoint.md) | *Описание* |
| [`GetExtraPoint`](./RectangleObject.cs/Методы/GetExtraPoint.md) | *Описание* |
| [`ExtraPointChanged`](./RectangleObject.cs/Методы/ExtraPointChanged.md) | *Описание* |
| [`RectangleObject`](./RectangleObject.cs/Методы/RectangleObject.md) | *Описание* |
| [`x9Yyrp3RfkGdCbNTXU4b`](./RectangleObject.cs/Методы/x9Yyrp3RfkGdCbNTXU4b.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`xsuJlZ3bylFkXacpNF53`](./RectangleObject.cs/Свойства/xsuJlZ3bylFkXacpNF53.md) | *Описание* |
| [`RectInfo`](./RectangleObject.cs/Свойства/RectInfo.md) | *Описание* |
| [`mrI3RMYxIFC;`](./RectangleObject.cs/Свойства/mrI3RMYxIFC;.md) | *Описание* |
| [`mtO3Rj6ZJ6t;`](./RectangleObject.cs/Свойства/mtO3Rj6ZJ6t;.md) | *Описание* |
| [`qX73RVVvfB0;`](./RectangleObject.cs/Свойства/qX73RVVvfB0;.md) | *Описание* |
| [`cTQ3RQ5sOeg;`](./RectangleObject.cs/Свойства/cTQ3RQ5sOeg;.md) | *Описание* |
| [`Rectangle;`](./RectangleObject.cs/Свойства/Rectangle;.md) | *Описание* |


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

