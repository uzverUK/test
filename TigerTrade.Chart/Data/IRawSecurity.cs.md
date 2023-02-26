
# public interface IRawSecurity
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public interface IRawSecurity
```


## Свойства
| Название | Описание |
| --- | --- |
| [`BidPrice`](./IRawSecurity.cs/svoistva/BidPrice.md) | *Описание* |
| [`BidSize`](./IRawSecurity.cs/svoistva/BidSize.md) | *Описание* |
| [`BidTime`](./IRawSecurity.cs/svoistva/BidTime.md) | *Описание* |
| [`BidDepthT`](./IRawSecurity.cs/svoistva/BidDepthT.md) | *Описание* |
| [`NumBids`](./IRawSecurity.cs/svoistva/NumBids.md) | *Описание* |
| [`AskPrice`](./IRawSecurity.cs/svoistva/AskPrice.md) | *Описание* |
| [`AskSize`](./IRawSecurity.cs/svoistva/AskSize.md) | *Описание* |
| [`AskTime`](./IRawSecurity.cs/svoistva/AskTime.md) | *Описание* |
| [`OfferDepthT`](./IRawSecurity.cs/svoistva/OfferDepthT.md) | *Описание* |
| [`NumOffers`](./IRawSecurity.cs/svoistva/NumOffers.md) | *Описание* |
| [`LastPrice`](./IRawSecurity.cs/svoistva/LastPrice.md) | *Описание* |
| [`LastSize`](./IRawSecurity.cs/svoistva/LastSize.md) | *Описание* |
| [`LastTime`](./IRawSecurity.cs/svoistva/LastTime.md) | *Описание* |
| [`HighPrice`](./IRawSecurity.cs/svoistva/HighPrice.md) | *Описание* |
| [`LowPrice`](./IRawSecurity.cs/svoistva/LowPrice.md) | *Описание* |
| [`OpenPrice`](./IRawSecurity.cs/svoistva/OpenPrice.md) | *Описание* |
| [`ClosePrice`](./IRawSecurity.cs/svoistva/ClosePrice.md) | *Описание* |
| [`Volume`](./IRawSecurity.cs/svoistva/Volume.md) | *Описание* |
| [`Trades`](./IRawSecurity.cs/svoistva/Trades.md) | *Описание* |
| [`OpenInt`](./IRawSecurity.cs/svoistva/OpenInt.md) | *Описание* |
| [`PriceMax`](./IRawSecurity.cs/svoistva/PriceMax.md) | *Описание* |
| [`PriceMin`](./IRawSecurity.cs/svoistva/PriceMin.md) | *Описание* |
| [`MarginBuy`](./IRawSecurity.cs/svoistva/MarginBuy.md) | *Описание* |
| [`MarginSell`](./IRawSecurity.cs/svoistva/MarginSell.md) | *Описание* |


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

