
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
| [`BidPrice`](./IRawSecurity.cs/Свойства/BidPrice.md) | *Описание* |
| [`BidSize`](./IRawSecurity.cs/Свойства/BidSize.md) | *Описание* |
| [`BidTime`](./IRawSecurity.cs/Свойства/BidTime.md) | *Описание* |
| [`BidDepthT`](./IRawSecurity.cs/Свойства/BidDepthT.md) | *Описание* |
| [`NumBids`](./IRawSecurity.cs/Свойства/NumBids.md) | *Описание* |
| [`AskPrice`](./IRawSecurity.cs/Свойства/AskPrice.md) | *Описание* |
| [`AskSize`](./IRawSecurity.cs/Свойства/AskSize.md) | *Описание* |
| [`AskTime`](./IRawSecurity.cs/Свойства/AskTime.md) | *Описание* |
| [`OfferDepthT`](./IRawSecurity.cs/Свойства/OfferDepthT.md) | *Описание* |
| [`NumOffers`](./IRawSecurity.cs/Свойства/NumOffers.md) | *Описание* |
| [`LastPrice`](./IRawSecurity.cs/Свойства/LastPrice.md) | *Описание* |
| [`LastSize`](./IRawSecurity.cs/Свойства/LastSize.md) | *Описание* |
| [`LastTime`](./IRawSecurity.cs/Свойства/LastTime.md) | *Описание* |
| [`HighPrice`](./IRawSecurity.cs/Свойства/HighPrice.md) | *Описание* |
| [`LowPrice`](./IRawSecurity.cs/Свойства/LowPrice.md) | *Описание* |
| [`OpenPrice`](./IRawSecurity.cs/Свойства/OpenPrice.md) | *Описание* |
| [`ClosePrice`](./IRawSecurity.cs/Свойства/ClosePrice.md) | *Описание* |
| [`Volume`](./IRawSecurity.cs/Свойства/Volume.md) | *Описание* |
| [`Trades`](./IRawSecurity.cs/Свойства/Trades.md) | *Описание* |
| [`OpenInt`](./IRawSecurity.cs/Свойства/OpenInt.md) | *Описание* |
| [`PriceMax`](./IRawSecurity.cs/Свойства/PriceMax.md) | *Описание* |
| [`PriceMin`](./IRawSecurity.cs/Свойства/PriceMin.md) | *Описание* |
| [`MarginBuy`](./IRawSecurity.cs/Свойства/MarginBuy.md) | *Описание* |
| [`MarginSell`](./IRawSecurity.cs/Свойства/MarginSell.md) | *Описание* |


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

