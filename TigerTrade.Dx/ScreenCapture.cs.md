
# public static class ScreenCapture
## Расположение
```csharp
namespace TigerTrade.Dx
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public static class ScreenCapture
```


## Методы
| Название | Описание |
| --- | --- |
| [`CaptureWindow`](./ScreenCapture.cs/Методы/CaptureWindow.md) | *Описание* |
| [`FewjcWVZLPm`](./ScreenCapture.cs/Методы/FewjcWVZLPm.md) | *Описание* |
| [`DwmjcitxLDp`](./ScreenCapture.cs/Методы/DwmjcitxLDp.md) | *Описание* |
| [`qYnjc2kmd1w`](./ScreenCapture.cs/Методы/qYnjc2kmd1w.md) | *Описание* |
| [`s1pjc9RD0u3`](./ScreenCapture.cs/Методы/s1pjc9RD0u3.md) | *Описание* |
| [`mZwjcXYDejQ`](./ScreenCapture.cs/Методы/mZwjcXYDejQ.md) | *Описание* |
| [`qL1C1PjcbfSt1jRc4poB`](./ScreenCapture.cs/Методы/qL1C1PjcbfSt1jRc4poB.md) | *Описание* |
| [`ReQjc4BwG6e`](./ScreenCapture.cs/Методы/ReQjc4BwG6e.md) | *Описание* |
| [`rV4jcN5vdat`](./ScreenCapture.cs/Методы/rV4jcN5vdat.md) | *Описание* |
| [`MI4B91jctfcyGZHN2j65`](./ScreenCapture.cs/Методы/MI4B91jctfcyGZHN2j65.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Lih7BdjIykOwQHbXkmse`](./ScreenCapture.cs/Свойства/Lih7BdjIykOwQHbXkmse.md) | *Описание* |
| [`M7hjIq2CkDG;`](./ScreenCapture.cs/Свойства/M7hjIq2CkDG;.md) | *Описание* |
| [`UjGjIfBfPQ0;`](./ScreenCapture.cs/Свойства/UjGjIfBfPQ0;.md) | *Описание* |
| [`ktDjIMg1ZJN;`](./ScreenCapture.cs/Свойства/ktDjIMg1ZJN;.md) | *Описание* |
| [`TNyjIj7U16k;`](./ScreenCapture.cs/Свойства/TNyjIj7U16k;.md) | *Описание* |


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

