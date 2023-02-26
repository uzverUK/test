
# public sealed class Security
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class Security
```


## Методы
| Название | Описание |
| --- | --- |
| [`Security`](./Security.cs/metody/Security.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`SecurityID`](./Security.cs/svoistva/SecurityID.md) | *Описание* |
| [`Symbol`](./Security.cs/svoistva/Symbol.md) | *Описание* |
| [`BidPrice`](./Security.cs/svoistva/BidPrice.md) | *Описание* |
| [`BidSize`](./Security.cs/svoistva/BidSize.md) | *Описание* |
| [`BidTime`](./Security.cs/svoistva/BidTime.md) | *Описание* |
| [`BidDepthT`](./Security.cs/svoistva/BidDepthT.md) | *Описание* |
| [`NumBids`](./Security.cs/svoistva/NumBids.md) | *Описание* |
| [`AskPrice`](./Security.cs/svoistva/AskPrice.md) | *Описание* |
| [`AskSize`](./Security.cs/svoistva/AskSize.md) | *Описание* |
| [`AskTime`](./Security.cs/svoistva/AskTime.md) | *Описание* |
| [`OfferDepthT`](./Security.cs/svoistva/OfferDepthT.md) | *Описание* |
| [`NumOffers`](./Security.cs/svoistva/NumOffers.md) | *Описание* |
| [`LastPrice`](./Security.cs/svoistva/LastPrice.md) | *Описание* |
| [`LastSize`](./Security.cs/svoistva/LastSize.md) | *Описание* |
| [`LastTime`](./Security.cs/svoistva/LastTime.md) | *Описание* |
| [`LastSide`](./Security.cs/svoistva/LastSide.md) | *Описание* |
| [`LastMarketCenter`](./Security.cs/svoistva/LastMarketCenter.md) | *Описание* |
| [`LastMarket`](./Security.cs/svoistva/LastMarket.md) | *Описание* |
| [`LastConditions`](./Security.cs/svoistva/LastConditions.md) | *Описание* |
| [`LastIsNotQualified`](./Security.cs/svoistva/LastIsNotQualified.md) | *Описание* |
| [`HighPrice`](./Security.cs/svoistva/HighPrice.md) | *Описание* |
| [`LowPrice`](./Security.cs/svoistva/LowPrice.md) | *Описание* |
| [`OpenPrice`](./Security.cs/svoistva/OpenPrice.md) | *Описание* |
| [`ClosePrice`](./Security.cs/svoistva/ClosePrice.md) | *Описание* |
| [`Volume`](./Security.cs/svoistva/Volume.md) | *Описание* |
| [`Trades`](./Security.cs/svoistva/Trades.md) | *Описание* |
| [`Value`](./Security.cs/svoistva/Value.md) | *Описание* |
| [`OpenInt`](./Security.cs/svoistva/OpenInt.md) | *Описание* |
| [`PriceMax`](./Security.cs/svoistva/PriceMax.md) | *Описание* |
| [`PriceMin`](./Security.cs/svoistva/PriceMin.md) | *Описание* |
| [`MarginBuy`](./Security.cs/svoistva/MarginBuy.md) | *Описание* |
| [`MarginSell`](./Security.cs/svoistva/MarginSell.md) | *Описание* |
| [`Volatility`](./Security.cs/svoistva/Volatility.md) | *Описание* |
| [`TheoreticalPrice`](./Security.cs/svoistva/TheoreticalPrice.md) | *Описание* |
| [`NetChange`](./Security.cs/svoistva/NetChange.md) | *Описание* |
| [`Change`](./Security.cs/svoistva/Change.md) | *Описание* |


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

