
# public sealed class ObjectLine : INotifyPropertyChanged
## Расположение
```csharp
namespace TigerTrade.Chart.Objects.Common
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class ObjectLine : INotifyPropertyChanged
```


## Методы
| Название | Описание |
| --- | --- |
| [`ObjectLine`](./ObjectLine.cs/metody/ObjectLine.md) | *Описание* |
| [`ObjectLine`](./ObjectLine.cs/metody/ObjectLine.md) | *Описание* |
| [`ObjectLine`](./ObjectLine.cs/metody/ObjectLine.md) | *Описание* |
| [`ToString`](./ObjectLine.cs/metody/ToString.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`ShowLine`](./ObjectLine.cs/svoistva/ShowLine.md) | *Описание* |
| [`Value`](./ObjectLine.cs/svoistva/Value.md) | *Описание* |
| [`LineBrush`](./ObjectLine.cs/svoistva/LineBrush.md) | *Описание* |
| [`LinePen`](./ObjectLine.cs/svoistva/LinePen.md) | *Описание* |
| [`LineColor`](./ObjectLine.cs/svoistva/LineColor.md) | *Описание* |
| [`LineWidth`](./ObjectLine.cs/svoistva/LineWidth.md) | *Описание* |
| [`LineStyle`](./ObjectLine.cs/svoistva/LineStyle.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ObjectLine.cs/sobytiya/PropertyChanged.md) | *Описание* |


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

