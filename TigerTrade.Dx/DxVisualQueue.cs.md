
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
| [`DxVisualQueue`](./DxVisualQueue.cs/metody/DxVisualQueue.md) | *Описание* |
| [`Clear`](./DxVisualQueue.cs/metody/Clear.md) | *Описание* |
| [`SetClip`](./DxVisualQueue.cs/metody/SetClip.md) | *Описание* |
| [`ResetClip`](./DxVisualQueue.cs/metody/ResetClip.md) | *Описание* |
| [`DrawLine`](./DxVisualQueue.cs/metody/DrawLine.md) | *Описание* |
| [`DrawLine`](./DxVisualQueue.cs/metody/DrawLine.md) | *Описание* |
| [`DrawLines`](./DxVisualQueue.cs/metody/DrawLines.md) | *Описание* |
| [`DrawLines`](./DxVisualQueue.cs/metody/DrawLines.md) | *Описание* |
| [`DrawSmoothLines`](./DxVisualQueue.cs/metody/DrawSmoothLines.md) | *Описание* |
| [`DrawRectangle`](./DxVisualQueue.cs/metody/DrawRectangle.md) | *Описание* |
| [`FillRectangle`](./DxVisualQueue.cs/metody/FillRectangle.md) | *Описание* |
| [`DrawRectangles`](./DxVisualQueue.cs/metody/DrawRectangles.md) | *Описание* |
| [`FillRectangles`](./DxVisualQueue.cs/metody/FillRectangles.md) | *Описание* |
| [`FillGradientRectangle`](./DxVisualQueue.cs/metody/FillGradientRectangle.md) | *Описание* |
| [`DrawRoundedRectangle`](./DxVisualQueue.cs/metody/DrawRoundedRectangle.md) | *Описание* |
| [`FillRoundedRectangle`](./DxVisualQueue.cs/metody/FillRoundedRectangle.md) | *Описание* |
| [`DrawPolygon`](./DxVisualQueue.cs/metody/DrawPolygon.md) | *Описание* |
| [`FillPolygon`](./DxVisualQueue.cs/metody/FillPolygon.md) | *Описание* |
| [`DrawArc`](./DxVisualQueue.cs/metody/DrawArc.md) | *Описание* |
| [`DrawEllipse`](./DxVisualQueue.cs/metody/DrawEllipse.md) | *Описание* |
| [`FillEllipse`](./DxVisualQueue.cs/metody/FillEllipse.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Empty`](./DxVisualQueue.cs/svoistva/Empty.md) | *Описание* |


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

