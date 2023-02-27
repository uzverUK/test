
# public sealed class UserPosition
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class UserPosition
```


## Методы
| Название | Описание |
| --- | --- |
| [`UserPosition`](./UserPosition.cs/Методы/UserPosition.md) | *Описание* |
| [`UserPosition`](./UserPosition.cs/Методы/UserPosition.md) | *Описание* |
| [`GetPointsPnl`](./UserPosition.cs/Методы/GetPointsPnl.md) | *Описание* |
| [`GetMoneyPnl`](./UserPosition.cs/Методы/GetMoneyPnl.md) | *Описание* |
| [`GetPercentPnl`](./UserPosition.cs/Методы/GetPercentPnl.md) | *Описание* |
| [`GetPointsPnl`](./UserPosition.cs/Методы/GetPointsPnl.md) | *Описание* |
| [`GetMoneyPnl`](./UserPosition.cs/Методы/GetMoneyPnl.md) | *Описание* |
| [`GetMoneyPnl`](./UserPosition.cs/Методы/GetMoneyPnl.md) | *Описание* |
| [`GetPercentPnl`](./UserPosition.cs/Методы/GetPercentPnl.md) | *Описание* |
| [`InitStrategy`](./UserPosition.cs/Методы/InitStrategy.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Symbol`](./UserPosition.cs/Свойства/Symbol.md) | *Описание* |
| [`ConnectionID`](./UserPosition.cs/Свойства/ConnectionID.md) | *Описание* |
| [`ConnectionName`](./UserPosition.cs/Свойства/ConnectionName.md) | *Описание* |
| [`SymbolID`](./UserPosition.cs/Свойства/SymbolID.md) | *Описание* |
| [`SymbolName`](./UserPosition.cs/Свойства/SymbolName.md) | *Описание* |
| [`AccountID`](./UserPosition.cs/Свойства/AccountID.md) | *Описание* |
| [`AccountName`](./UserPosition.cs/Свойства/AccountName.md) | *Описание* |
| [`Price`](./UserPosition.cs/Свойства/Price.md) | *Описание* |
| [`PriceSum`](./UserPosition.cs/Свойства/PriceSum.md) | *Описание* |
| [`PriceSumLong`](./UserPosition.cs/Свойства/PriceSumLong.md) | *Описание* |
| [`Size`](./UserPosition.cs/Свойства/Size.md) | *Описание* |
| [`SizeStep`](./UserPosition.cs/Свойства/SizeStep.md) | *Описание* |
| [`TotalValue`](./UserPosition.cs/Свойства/TotalValue.md) | *Описание* |
| [`TotalValueLong`](./UserPosition.cs/Свойства/TotalValueLong.md) | *Описание* |
| [`TotalQuantity`](./UserPosition.cs/Свойства/TotalQuantity.md) | *Описание* |
| [`MaxQuantity`](./UserPosition.cs/Свойства/MaxQuantity.md) | *Описание* |
| [`Comission`](./UserPosition.cs/Свойства/Comission.md) | *Описание* |
| [`StartTime`](./UserPosition.cs/Свойства/StartTime.md) | *Описание* |
| [`OpenTime`](./UserPosition.cs/Свойства/OpenTime.md) | *Описание* |
| [`OpenPrice`](./UserPosition.cs/Свойства/OpenPrice.md) | *Описание* |
| [`LastTradeTime`](./UserPosition.cs/Свойства/LastTradeTime.md) | *Описание* |
| [`IsMt5TimeValid`](./UserPosition.cs/Свойства/IsMt5TimeValid.md) | *Описание* |
| [`LastTradeIDs`](./UserPosition.cs/Свойства/LastTradeIDs.md) | *Описание* |
| [`Hidden`](./UserPosition.cs/Свойства/Hidden.md) | *Описание* |
| [`Strategy`](./UserPosition.cs/Свойства/Strategy.md) | *Описание* |
| [`LastPrice`](./UserPosition.cs/Свойства/LastPrice.md) | *Описание* |
| [`Bid`](./UserPosition.cs/Свойства/Bid.md) | *Описание* |
| [`Ask`](./UserPosition.cs/Свойства/Ask.md) | *Описание* |
| [`PositionPnl`](./UserPosition.cs/Свойства/PositionPnl.md) | *Описание* |
| [`PositionTime`](./UserPosition.cs/Свойства/PositionTime.md) | *Описание* |


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

