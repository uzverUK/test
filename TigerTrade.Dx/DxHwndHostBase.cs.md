
# public class DxHwndHostBase : HwndHost
## Расположение
```csharp
namespace TigerTrade.Dx
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public class DxHwndHostBase : HwndHost
```


## Методы
| Название | Описание |
| --- | --- |
| [`DxHwndHostBase`](./DxHwndHostBase.cs/Методы/DxHwndHostBase.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`JhZjcrtFS5G;`](./DxHwndHostBase.cs/Свойства/JhZjcrtFS5G;.md) | *Описание* |
| [`AmRjcZuMlRk;`](./DxHwndHostBase.cs/Свойства/AmRjcZuMlRk;.md) | *Описание* |
| [`J1XjcmvFG6Q;`](./DxHwndHostBase.cs/Свойства/J1XjcmvFG6Q;.md) | *Описание* |
| [`QgujcpdwuL2;`](./DxHwndHostBase.cs/Свойства/QgujcpdwuL2;.md) | *Описание* |
| [`RbpjcKgQmhW;`](./DxHwndHostBase.cs/Свойства/RbpjcKgQmhW;.md) | *Описание* |
| [`i5NjclyGDO6;`](./DxHwndHostBase.cs/Свойства/i5NjclyGDO6;.md) | *Описание* |
| [`UIrjcLP9CAY;`](./DxHwndHostBase.cs/Свойства/UIrjcLP9CAY;.md) | *Описание* |
| [`Lfrjcnq3MxI;`](./DxHwndHostBase.cs/Свойства/Lfrjcnq3MxI;.md) | *Описание* |
| [`MSIjcksg8fF;`](./DxHwndHostBase.cs/Свойства/MSIjcksg8fF;.md) | *Описание* |
| [`rEWjc6mm0du;`](./DxHwndHostBase.cs/Свойства/rEWjc6mm0du;.md) | *Описание* |


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

