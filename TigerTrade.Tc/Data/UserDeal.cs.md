
# public sealed class UserDeal
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class UserDeal
```


## Методы
| Название | Описание |
| --- | --- |
| [`UserDeal`](./UserDeal.cs/metody/UserDeal.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`DealID`](./UserDeal.cs/svoistva/DealID.md) | *Описание* |
| [`SymbolID`](./UserDeal.cs/svoistva/SymbolID.md) | *Описание* |
| [`SymbolName`](./UserDeal.cs/svoistva/SymbolName.md) | *Описание* |
| [`AccountID`](./UserDeal.cs/svoistva/AccountID.md) | *Описание* |
| [`AccountName`](./UserDeal.cs/svoistva/AccountName.md) | *Описание* |
| [`OpenTime`](./UserDeal.cs/svoistva/OpenTime.md) | *Описание* |
| [`OpenPrice`](./UserDeal.cs/svoistva/OpenPrice.md) | *Описание* |
| [`CloseTime`](./UserDeal.cs/svoistva/CloseTime.md) | *Описание* |
| [`ClosePrice`](./UserDeal.cs/svoistva/ClosePrice.md) | *Описание* |
| [`Side`](./UserDeal.cs/svoistva/Side.md) | *Описание* |
| [`Quantity`](./UserDeal.cs/svoistva/Quantity.md) | *Описание* |
| [`MaxQuantity`](./UserDeal.cs/svoistva/MaxQuantity.md) | *Описание* |
| [`TotalValue`](./UserDeal.cs/svoistva/TotalValue.md) | *Описание* |
| [`Points`](./UserDeal.cs/svoistva/Points.md) | *Описание* |
| [`Profit`](./UserDeal.cs/svoistva/Profit.md) | *Описание* |
| [`Comission`](./UserDeal.cs/svoistva/Comission.md) | *Описание* |
| [`Tags`](./UserDeal.cs/svoistva/Tags.md) | *Описание* |
| [`Description`](./UserDeal.cs/svoistva/Description.md) | *Описание* |
| [`LocalTime`](./UserDeal.cs/svoistva/LocalTime.md) | *Описание* |
| [`IsMt5TimeValid`](./UserDeal.cs/svoistva/IsMt5TimeValid.md) | *Описание* |


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

