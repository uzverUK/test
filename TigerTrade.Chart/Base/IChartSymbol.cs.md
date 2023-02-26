
# public interface IChartSymbol
## Расположение
```csharp
namespace TigerTrade.Chart.Base
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public interface IChartSymbol
```


## Методы
| Название | Описание |
| --- | --- |
| [`GetPrice`](./IChartSymbol.cs/metody/GetPrice.md) | *Описание* |
| [`GetSize`](./IChartSymbol.cs/metody/GetSize.md) | *Описание* |
| [`CorrectSizeFilter`](./IChartSymbol.cs/metody/CorrectSizeFilter.md) | *Описание* |
| [`CorrectSizeFilter`](./IChartSymbol.cs/metody/CorrectSizeFilter.md) | *Описание* |
| [`FormatPrice`](./IChartSymbol.cs/metody/FormatPrice.md) | *Описание* |
| [`FormatRawPrice`](./IChartSymbol.cs/metody/FormatRawPrice.md) | *Описание* |
| [`FormatSize`](./IChartSymbol.cs/metody/FormatSize.md) | *Описание* |
| [`FormatSize`](./IChartSymbol.cs/metody/FormatSize.md) | *Описание* |
| [`FormatSizeShort`](./IChartSymbol.cs/metody/FormatSizeShort.md) | *Описание* |
| [`FormatSizeFull`](./IChartSymbol.cs/metody/FormatSizeFull.md) | *Описание* |
| [`FormatRawSize`](./IChartSymbol.cs/metody/FormatRawSize.md) | *Описание* |
| [`FormatRawSize`](./IChartSymbol.cs/metody/FormatRawSize.md) | *Описание* |
| [`FormatRawSizeShort`](./IChartSymbol.cs/metody/FormatRawSizeShort.md) | *Описание* |
| [`FormatRawSizeFull`](./IChartSymbol.cs/metody/FormatRawSizeFull.md) | *Описание* |
| [`FormatTrades`](./IChartSymbol.cs/metody/FormatTrades.md) | *Описание* |
| [`FormatTrades`](./IChartSymbol.cs/metody/FormatTrades.md) | *Описание* |
| [`FormatTime`](./IChartSymbol.cs/metody/FormatTime.md) | *Описание* |
| [`ConvertTimeToLocal`](./IChartSymbol.cs/metody/ConvertTimeToLocal.md) | *Описание* |
| [`ConvertTimeFromLocal`](./IChartSymbol.cs/metody/ConvertTimeFromLocal.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Code`](./IChartSymbol.cs/svoistva/Code.md) | *Описание* |
| [`Name`](./IChartSymbol.cs/svoistva/Name.md) | *Описание* |
| [`Exchange`](./IChartSymbol.cs/svoistva/Exchange.md) | *Описание* |
| [`Decimals`](./IChartSymbol.cs/svoistva/Decimals.md) | *Описание* |
| [`StepPrice`](./IChartSymbol.cs/svoistva/StepPrice.md) | *Описание* |


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

