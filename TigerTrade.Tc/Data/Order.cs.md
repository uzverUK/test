
# public sealed class Order
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class Order
```


## Методы
| Название | Описание |
| --- | --- |
| [`Order`](./Order.cs/Методы/Order.md) | *Описание* |
| [`Order`](./Order.cs/Методы/Order.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`ID`](./Order.cs/Свойства/ID.md) | *Описание* |
| [`OrderID`](./Order.cs/Свойства/OrderID.md) | *Описание* |
| [`TransID`](./Order.cs/Свойства/TransID.md) | *Описание* |
| [`Symbol`](./Order.cs/Свойства/Symbol.md) | *Описание* |
| [`Account`](./Order.cs/Свойства/Account.md) | *Описание* |
| [`Type`](./Order.cs/Свойства/Type.md) | *Описание* |
| [`State`](./Order.cs/Свойства/State.md) | *Описание* |
| [`Validity`](./Order.cs/Свойства/Validity.md) | *Описание* |
| [`Time`](./Order.cs/Свойства/Time.md) | *Описание* |
| [`Price`](./Order.cs/Свойства/Price.md) | *Описание* |
| [`StopPrice`](./Order.cs/Свойства/StopPrice.md) | *Описание* |
| [`TakePrice`](./Order.cs/Свойства/TakePrice.md) | *Описание* |
| [`Quantity`](./Order.cs/Свойства/Quantity.md) | *Описание* |
| [`QuantityReal`](./Order.cs/Свойства/QuantityReal.md) | *Описание* |
| [`DisplayQty`](./Order.cs/Свойства/DisplayQty.md) | *Описание* |
| [`Filled`](./Order.cs/Свойства/Filled.md) | *Описание* |
| [`Remaining`](./Order.cs/Свойства/Remaining.md) | *Описание* |
| [`AvgFillPrice`](./Order.cs/Свойства/AvgFillPrice.md) | *Описание* |
| [`Side`](./Order.cs/Свойства/Side.md) | *Описание* |
| [`Comment`](./Order.cs/Свойства/Comment.md) | *Описание* |
| [`Options`](./Order.cs/Свойства/Options.md) | *Описание* |
| [`ModifyParams`](./Order.cs/Свойства/ModifyParams.md) | *Описание* |
| [`RoundTrip`](./Order.cs/Свойства/RoundTrip.md) | *Описание* |
| [`PosClose`](./Order.cs/Свойства/PosClose.md) | *Описание* |
| [`PlaceInitiator`](./Order.cs/Свойства/PlaceInitiator.md) | *Описание* |
| [`ModifyInitiator`](./Order.cs/Свойства/ModifyInitiator.md) | *Описание* |
| [`CancelInitiator`](./Order.cs/Свойства/CancelInitiator.md) | *Описание* |
| [`IsSplicedFuturesSymbol`](./Order.cs/Свойства/IsSplicedFuturesSymbol.md) | *Описание* |
| [`IsActive`](./Order.cs/Свойства/IsActive.md) | *Описание* |
| [`IsInactive`](./Order.cs/Свойства/IsInactive.md) | *Описание* |


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

