
# public sealed class DxHwndHost : DxHwndHostBase
## Расположение
```csharp
namespace TigerTrade.Dx
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class DxHwndHost : DxHwndHostBase
```


## Методы
| Название | Описание |
| --- | --- |
| [`DxHwndHost`](./DxHwndHost.cs/metody/DxHwndHost.md) | *Описание* |
| [`StartTimer`](./DxHwndHost.cs/metody/StartTimer.md) | *Описание* |
| [`Render`](./DxHwndHost.cs/metody/Render.md) | *Описание* |
| [`InvalidateVisual`](./DxHwndHost.cs/metody/InvalidateVisual.md) | *Описание* |
| [`InvalidateSecondVisual`](./DxHwndHost.cs/metody/InvalidateSecondVisual.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`WaitRedraw`](./DxHwndHost.cs/svoistva/WaitRedraw.md) | *Описание* |
| [`ClientRect`](./DxHwndHost.cs/svoistva/ClientRect.md) | *Описание* |
| [`IsDisposed`](./DxHwndHost.cs/svoistva/IsDisposed.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`OnTimerTick`](./DxHwndHost.cs/sobytiya/OnTimerTick.md) | *Описание* |
| [`OnRenderVisual;`](./DxHwndHost.cs/sobytiya/OnRenderVisual;.md) | *Описание* |


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

