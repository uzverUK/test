
# public sealed class DxVisualQueue
## Расположение
```csharp
namespace TigerTrade.Dx
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class DxVisualQueue
```


## Методы
| Название | Описание |
| --- | --- |
| [`DxVisualQueue`](./DxVisualQueue.cs/Методы/DxVisualQueue.md) | *Описание* |
| [`Clear`](./DxVisualQueue.cs/Методы/Clear.md) | *Описание* |
| [`SetClip`](./DxVisualQueue.cs/Методы/SetClip.md) | *Описание* |
| [`ResetClip`](./DxVisualQueue.cs/Методы/ResetClip.md) | *Описание* |
| [`DrawLine`](./DxVisualQueue.cs/Методы/DrawLine.md) | *Описание* |
| [`DrawLine`](./DxVisualQueue.cs/Методы/DrawLine.md) | *Описание* |
| [`DrawLines`](./DxVisualQueue.cs/Методы/DrawLines.md) | *Описание* |
| [`DrawLines`](./DxVisualQueue.cs/Методы/DrawLines.md) | *Описание* |
| [`DrawSmoothLines`](./DxVisualQueue.cs/Методы/DrawSmoothLines.md) | *Описание* |
| [`DrawRectangle`](./DxVisualQueue.cs/Методы/DrawRectangle.md) | *Описание* |
| [`FillRectangle`](./DxVisualQueue.cs/Методы/FillRectangle.md) | *Описание* |
| [`DrawRectangles`](./DxVisualQueue.cs/Методы/DrawRectangles.md) | *Описание* |
| [`FillRectangles`](./DxVisualQueue.cs/Методы/FillRectangles.md) | *Описание* |
| [`FillGradientRectangle`](./DxVisualQueue.cs/Методы/FillGradientRectangle.md) | *Описание* |
| [`DrawRoundedRectangle`](./DxVisualQueue.cs/Методы/DrawRoundedRectangle.md) | *Описание* |
| [`FillRoundedRectangle`](./DxVisualQueue.cs/Методы/FillRoundedRectangle.md) | *Описание* |
| [`DrawPolygon`](./DxVisualQueue.cs/Методы/DrawPolygon.md) | *Описание* |
| [`FillPolygon`](./DxVisualQueue.cs/Методы/FillPolygon.md) | *Описание* |
| [`DrawArc`](./DxVisualQueue.cs/Методы/DrawArc.md) | *Описание* |
| [`DrawEllipse`](./DxVisualQueue.cs/Методы/DrawEllipse.md) | *Описание* |
| [`FillEllipse`](./DxVisualQueue.cs/Методы/FillEllipse.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Empty`](./DxVisualQueue.cs/Свойства/Empty.md) | *Описание* |


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

