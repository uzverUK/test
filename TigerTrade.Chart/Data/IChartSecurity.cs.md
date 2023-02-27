
# public interface IChartSecurity
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public interface IChartSecurity
```


## Свойства
| Название | Описание |
| --- | --- |
| [`BidPrice`](./IChartSecurity.cs/Свойства/BidPrice.md) | *Описание* |
| [`BidSize`](./IChartSecurity.cs/Свойства/BidSize.md) | *Описание* |
| [`BidTime`](./IChartSecurity.cs/Свойства/BidTime.md) | *Описание* |
| [`BidDepthT`](./IChartSecurity.cs/Свойства/BidDepthT.md) | *Описание* |
| [`NumBids`](./IChartSecurity.cs/Свойства/NumBids.md) | *Описание* |
| [`AskPrice`](./IChartSecurity.cs/Свойства/AskPrice.md) | *Описание* |
| [`AskSize`](./IChartSecurity.cs/Свойства/AskSize.md) | *Описание* |
| [`AskTime`](./IChartSecurity.cs/Свойства/AskTime.md) | *Описание* |
| [`OfferDepthT`](./IChartSecurity.cs/Свойства/OfferDepthT.md) | *Описание* |
| [`NumOffers`](./IChartSecurity.cs/Свойства/NumOffers.md) | *Описание* |
| [`LastPrice`](./IChartSecurity.cs/Свойства/LastPrice.md) | *Описание* |
| [`LastSize`](./IChartSecurity.cs/Свойства/LastSize.md) | *Описание* |
| [`LastTime`](./IChartSecurity.cs/Свойства/LastTime.md) | *Описание* |
| [`HighPrice`](./IChartSecurity.cs/Свойства/HighPrice.md) | *Описание* |
| [`LowPrice`](./IChartSecurity.cs/Свойства/LowPrice.md) | *Описание* |
| [`OpenPrice`](./IChartSecurity.cs/Свойства/OpenPrice.md) | *Описание* |
| [`ClosePrice`](./IChartSecurity.cs/Свойства/ClosePrice.md) | *Описание* |
| [`Volume`](./IChartSecurity.cs/Свойства/Volume.md) | *Описание* |
| [`Trades`](./IChartSecurity.cs/Свойства/Trades.md) | *Описание* |
| [`OpenInt`](./IChartSecurity.cs/Свойства/OpenInt.md) | *Описание* |
| [`PriceMax`](./IChartSecurity.cs/Свойства/PriceMax.md) | *Описание* |
| [`PriceMin`](./IChartSecurity.cs/Свойства/PriceMin.md) | *Описание* |
| [`MarginBuy`](./IChartSecurity.cs/Свойства/MarginBuy.md) | *Описание* |
| [`MarginSell`](./IChartSecurity.cs/Свойства/MarginSell.md) | *Описание* |


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

