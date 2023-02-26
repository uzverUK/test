
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
| [`Order`](./Order.cs/metody/Order.md) | *Описание* |
| [`Order`](./Order.cs/metody/Order.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`ID`](./Order.cs/svoistva/ID.md) | *Описание* |
| [`OrderID`](./Order.cs/svoistva/OrderID.md) | *Описание* |
| [`TransID`](./Order.cs/svoistva/TransID.md) | *Описание* |
| [`Symbol`](./Order.cs/svoistva/Symbol.md) | *Описание* |
| [`Account`](./Order.cs/svoistva/Account.md) | *Описание* |
| [`Type`](./Order.cs/svoistva/Type.md) | *Описание* |
| [`State`](./Order.cs/svoistva/State.md) | *Описание* |
| [`Validity`](./Order.cs/svoistva/Validity.md) | *Описание* |
| [`Time`](./Order.cs/svoistva/Time.md) | *Описание* |
| [`Price`](./Order.cs/svoistva/Price.md) | *Описание* |
| [`StopPrice`](./Order.cs/svoistva/StopPrice.md) | *Описание* |
| [`TakePrice`](./Order.cs/svoistva/TakePrice.md) | *Описание* |
| [`Quantity`](./Order.cs/svoistva/Quantity.md) | *Описание* |
| [`QuantityReal`](./Order.cs/svoistva/QuantityReal.md) | *Описание* |
| [`DisplayQty`](./Order.cs/svoistva/DisplayQty.md) | *Описание* |
| [`Filled`](./Order.cs/svoistva/Filled.md) | *Описание* |
| [`Remaining`](./Order.cs/svoistva/Remaining.md) | *Описание* |
| [`AvgFillPrice`](./Order.cs/svoistva/AvgFillPrice.md) | *Описание* |
| [`Side`](./Order.cs/svoistva/Side.md) | *Описание* |
| [`Comment`](./Order.cs/svoistva/Comment.md) | *Описание* |
| [`Options`](./Order.cs/svoistva/Options.md) | *Описание* |
| [`ModifyParams`](./Order.cs/svoistva/ModifyParams.md) | *Описание* |
| [`RoundTrip`](./Order.cs/svoistva/RoundTrip.md) | *Описание* |
| [`PosClose`](./Order.cs/svoistva/PosClose.md) | *Описание* |
| [`PlaceInitiator`](./Order.cs/svoistva/PlaceInitiator.md) | *Описание* |
| [`ModifyInitiator`](./Order.cs/svoistva/ModifyInitiator.md) | *Описание* |
| [`CancelInitiator`](./Order.cs/svoistva/CancelInitiator.md) | *Описание* |
| [`IsSplicedFuturesSymbol`](./Order.cs/svoistva/IsSplicedFuturesSymbol.md) | *Описание* |
| [`IsActive`](./Order.cs/svoistva/IsActive.md) | *Описание* |
| [`IsInactive`](./Order.cs/svoistva/IsInactive.md) | *Описание* |


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

