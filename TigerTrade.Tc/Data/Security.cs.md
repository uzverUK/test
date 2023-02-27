
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
| [`Security`](./Security.cs/Методы/Security.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`SecurityID`](./Security.cs/Свойства/SecurityID.md) | *Описание* |
| [`Symbol`](./Security.cs/Свойства/Symbol.md) | *Описание* |
| [`BidPrice`](./Security.cs/Свойства/BidPrice.md) | *Описание* |
| [`BidSize`](./Security.cs/Свойства/BidSize.md) | *Описание* |
| [`BidTime`](./Security.cs/Свойства/BidTime.md) | *Описание* |
| [`BidDepthT`](./Security.cs/Свойства/BidDepthT.md) | *Описание* |
| [`NumBids`](./Security.cs/Свойства/NumBids.md) | *Описание* |
| [`AskPrice`](./Security.cs/Свойства/AskPrice.md) | *Описание* |
| [`AskSize`](./Security.cs/Свойства/AskSize.md) | *Описание* |
| [`AskTime`](./Security.cs/Свойства/AskTime.md) | *Описание* |
| [`OfferDepthT`](./Security.cs/Свойства/OfferDepthT.md) | *Описание* |
| [`NumOffers`](./Security.cs/Свойства/NumOffers.md) | *Описание* |
| [`LastPrice`](./Security.cs/Свойства/LastPrice.md) | *Описание* |
| [`LastSize`](./Security.cs/Свойства/LastSize.md) | *Описание* |
| [`LastTime`](./Security.cs/Свойства/LastTime.md) | *Описание* |
| [`LastSide`](./Security.cs/Свойства/LastSide.md) | *Описание* |
| [`LastMarketCenter`](./Security.cs/Свойства/LastMarketCenter.md) | *Описание* |
| [`LastMarket`](./Security.cs/Свойства/LastMarket.md) | *Описание* |
| [`LastConditions`](./Security.cs/Свойства/LastConditions.md) | *Описание* |
| [`LastIsNotQualified`](./Security.cs/Свойства/LastIsNotQualified.md) | *Описание* |
| [`HighPrice`](./Security.cs/Свойства/HighPrice.md) | *Описание* |
| [`LowPrice`](./Security.cs/Свойства/LowPrice.md) | *Описание* |
| [`OpenPrice`](./Security.cs/Свойства/OpenPrice.md) | *Описание* |
| [`ClosePrice`](./Security.cs/Свойства/ClosePrice.md) | *Описание* |
| [`Volume`](./Security.cs/Свойства/Volume.md) | *Описание* |
| [`Trades`](./Security.cs/Свойства/Trades.md) | *Описание* |
| [`Value`](./Security.cs/Свойства/Value.md) | *Описание* |
| [`OpenInt`](./Security.cs/Свойства/OpenInt.md) | *Описание* |
| [`PriceMax`](./Security.cs/Свойства/PriceMax.md) | *Описание* |
| [`PriceMin`](./Security.cs/Свойства/PriceMin.md) | *Описание* |
| [`MarginBuy`](./Security.cs/Свойства/MarginBuy.md) | *Описание* |
| [`MarginSell`](./Security.cs/Свойства/MarginSell.md) | *Описание* |
| [`Volatility`](./Security.cs/Свойства/Volatility.md) | *Описание* |
| [`TheoreticalPrice`](./Security.cs/Свойства/TheoreticalPrice.md) | *Описание* |
| [`NetChange`](./Security.cs/Свойства/NetChange.md) | *Описание* |
| [`Change`](./Security.cs/Свойства/Change.md) | *Описание* |


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

