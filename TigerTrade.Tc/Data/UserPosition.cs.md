
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
| [`UserPosition`](./UserPosition.cs/metody/UserPosition.md) | *Описание* |
| [`UserPosition`](./UserPosition.cs/metody/UserPosition.md) | *Описание* |
| [`GetPointsPnl`](./UserPosition.cs/metody/GetPointsPnl.md) | *Описание* |
| [`GetMoneyPnl`](./UserPosition.cs/metody/GetMoneyPnl.md) | *Описание* |
| [`GetPercentPnl`](./UserPosition.cs/metody/GetPercentPnl.md) | *Описание* |
| [`GetPointsPnl`](./UserPosition.cs/metody/GetPointsPnl.md) | *Описание* |
| [`GetMoneyPnl`](./UserPosition.cs/metody/GetMoneyPnl.md) | *Описание* |
| [`GetMoneyPnl`](./UserPosition.cs/metody/GetMoneyPnl.md) | *Описание* |
| [`GetPercentPnl`](./UserPosition.cs/metody/GetPercentPnl.md) | *Описание* |
| [`InitStrategy`](./UserPosition.cs/metody/InitStrategy.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Symbol`](./UserPosition.cs/svoistva/Symbol.md) | *Описание* |
| [`ConnectionID`](./UserPosition.cs/svoistva/ConnectionID.md) | *Описание* |
| [`ConnectionName`](./UserPosition.cs/svoistva/ConnectionName.md) | *Описание* |
| [`SymbolID`](./UserPosition.cs/svoistva/SymbolID.md) | *Описание* |
| [`SymbolName`](./UserPosition.cs/svoistva/SymbolName.md) | *Описание* |
| [`AccountID`](./UserPosition.cs/svoistva/AccountID.md) | *Описание* |
| [`AccountName`](./UserPosition.cs/svoistva/AccountName.md) | *Описание* |
| [`Price`](./UserPosition.cs/svoistva/Price.md) | *Описание* |
| [`PriceSum`](./UserPosition.cs/svoistva/PriceSum.md) | *Описание* |
| [`PriceSumLong`](./UserPosition.cs/svoistva/PriceSumLong.md) | *Описание* |
| [`Size`](./UserPosition.cs/svoistva/Size.md) | *Описание* |
| [`SizeStep`](./UserPosition.cs/svoistva/SizeStep.md) | *Описание* |
| [`TotalValue`](./UserPosition.cs/svoistva/TotalValue.md) | *Описание* |
| [`TotalValueLong`](./UserPosition.cs/svoistva/TotalValueLong.md) | *Описание* |
| [`TotalQuantity`](./UserPosition.cs/svoistva/TotalQuantity.md) | *Описание* |
| [`MaxQuantity`](./UserPosition.cs/svoistva/MaxQuantity.md) | *Описание* |
| [`Comission`](./UserPosition.cs/svoistva/Comission.md) | *Описание* |
| [`StartTime`](./UserPosition.cs/svoistva/StartTime.md) | *Описание* |
| [`OpenTime`](./UserPosition.cs/svoistva/OpenTime.md) | *Описание* |
| [`OpenPrice`](./UserPosition.cs/svoistva/OpenPrice.md) | *Описание* |
| [`LastTradeTime`](./UserPosition.cs/svoistva/LastTradeTime.md) | *Описание* |
| [`IsMt5TimeValid`](./UserPosition.cs/svoistva/IsMt5TimeValid.md) | *Описание* |
| [`LastTradeIDs`](./UserPosition.cs/svoistva/LastTradeIDs.md) | *Описание* |
| [`Hidden`](./UserPosition.cs/svoistva/Hidden.md) | *Описание* |
| [`Strategy`](./UserPosition.cs/svoistva/Strategy.md) | *Описание* |
| [`LastPrice`](./UserPosition.cs/svoistva/LastPrice.md) | *Описание* |
| [`Bid`](./UserPosition.cs/svoistva/Bid.md) | *Описание* |
| [`Ask`](./UserPosition.cs/svoistva/Ask.md) | *Описание* |
| [`PositionPnl`](./UserPosition.cs/svoistva/PositionPnl.md) | *Описание* |
| [`PositionTime`](./UserPosition.cs/svoistva/PositionTime.md) | *Описание* |


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

