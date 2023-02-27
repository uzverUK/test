
# public interface IChartDataProvider
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public interface IChartDataProvider
```


## Методы
| Название | Описание |
| --- | --- |
| [`GetCluster`](./IChartDataProvider.cs/Методы/GetCluster.md) | *Описание* |
| [`GetRawCluster`](./IChartDataProvider.cs/Методы/GetRawCluster.md) | *Описание* |
| [`GetSecurity`](./IChartDataProvider.cs/Методы/GetSecurity.md) | *Описание* |
| [`GetRawSecurity`](./IChartDataProvider.cs/Методы/GetRawSecurity.md) | *Описание* |
| [`GetMarketDepth`](./IChartDataProvider.cs/Методы/GetMarketDepth.md) | *Описание* |
| [`GetRawMarketDepth`](./IChartDataProvider.cs/Методы/GetRawMarketDepth.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Period`](./IChartDataProvider.cs/Свойства/Period.md) | *Описание* |
| [`Symbol`](./IChartDataProvider.cs/Свойства/Symbol.md) | *Описание* |
| [`Step`](./IChartDataProvider.cs/Свойства/Step.md) | *Описание* |
| [`Scale`](./IChartDataProvider.cs/Свойства/Scale.md) | *Описание* |
| [`Count`](./IChartDataProvider.cs/Свойства/Count.md) | *Описание* |


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

