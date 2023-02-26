
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
| [`BidPrice`](./IChartSecurity.cs/svoistva/BidPrice.md) | *Описание* |
| [`BidSize`](./IChartSecurity.cs/svoistva/BidSize.md) | *Описание* |
| [`BidTime`](./IChartSecurity.cs/svoistva/BidTime.md) | *Описание* |
| [`BidDepthT`](./IChartSecurity.cs/svoistva/BidDepthT.md) | *Описание* |
| [`NumBids`](./IChartSecurity.cs/svoistva/NumBids.md) | *Описание* |
| [`AskPrice`](./IChartSecurity.cs/svoistva/AskPrice.md) | *Описание* |
| [`AskSize`](./IChartSecurity.cs/svoistva/AskSize.md) | *Описание* |
| [`AskTime`](./IChartSecurity.cs/svoistva/AskTime.md) | *Описание* |
| [`OfferDepthT`](./IChartSecurity.cs/svoistva/OfferDepthT.md) | *Описание* |
| [`NumOffers`](./IChartSecurity.cs/svoistva/NumOffers.md) | *Описание* |
| [`LastPrice`](./IChartSecurity.cs/svoistva/LastPrice.md) | *Описание* |
| [`LastSize`](./IChartSecurity.cs/svoistva/LastSize.md) | *Описание* |
| [`LastTime`](./IChartSecurity.cs/svoistva/LastTime.md) | *Описание* |
| [`HighPrice`](./IChartSecurity.cs/svoistva/HighPrice.md) | *Описание* |
| [`LowPrice`](./IChartSecurity.cs/svoistva/LowPrice.md) | *Описание* |
| [`OpenPrice`](./IChartSecurity.cs/svoistva/OpenPrice.md) | *Описание* |
| [`ClosePrice`](./IChartSecurity.cs/svoistva/ClosePrice.md) | *Описание* |
| [`Volume`](./IChartSecurity.cs/svoistva/Volume.md) | *Описание* |
| [`Trades`](./IChartSecurity.cs/svoistva/Trades.md) | *Описание* |
| [`OpenInt`](./IChartSecurity.cs/svoistva/OpenInt.md) | *Описание* |
| [`PriceMax`](./IChartSecurity.cs/svoistva/PriceMax.md) | *Описание* |
| [`PriceMin`](./IChartSecurity.cs/svoistva/PriceMin.md) | *Описание* |
| [`MarginBuy`](./IChartSecurity.cs/svoistva/MarginBuy.md) | *Описание* |
| [`MarginSell`](./IChartSecurity.cs/svoistva/MarginSell.md) | *Описание* |


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

