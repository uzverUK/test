
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
| [`GetPrice`](./IChartSymbol.cs/Методы/GetPrice.md) | *Описание* |
| [`GetSize`](./IChartSymbol.cs/Методы/GetSize.md) | *Описание* |
| [`CorrectSizeFilter`](./IChartSymbol.cs/Методы/CorrectSizeFilter.md) | *Описание* |
| [`CorrectSizeFilter`](./IChartSymbol.cs/Методы/CorrectSizeFilter.md) | *Описание* |
| [`FormatPrice`](./IChartSymbol.cs/Методы/FormatPrice.md) | *Описание* |
| [`FormatRawPrice`](./IChartSymbol.cs/Методы/FormatRawPrice.md) | *Описание* |
| [`FormatSize`](./IChartSymbol.cs/Методы/FormatSize.md) | *Описание* |
| [`FormatSize`](./IChartSymbol.cs/Методы/FormatSize.md) | *Описание* |
| [`FormatSizeShort`](./IChartSymbol.cs/Методы/FormatSizeShort.md) | *Описание* |
| [`FormatSizeFull`](./IChartSymbol.cs/Методы/FormatSizeFull.md) | *Описание* |
| [`FormatRawSize`](./IChartSymbol.cs/Методы/FormatRawSize.md) | *Описание* |
| [`FormatRawSize`](./IChartSymbol.cs/Методы/FormatRawSize.md) | *Описание* |
| [`FormatRawSizeShort`](./IChartSymbol.cs/Методы/FormatRawSizeShort.md) | *Описание* |
| [`FormatRawSizeFull`](./IChartSymbol.cs/Методы/FormatRawSizeFull.md) | *Описание* |
| [`FormatTrades`](./IChartSymbol.cs/Методы/FormatTrades.md) | *Описание* |
| [`FormatTrades`](./IChartSymbol.cs/Методы/FormatTrades.md) | *Описание* |
| [`FormatTime`](./IChartSymbol.cs/Методы/FormatTime.md) | *Описание* |
| [`ConvertTimeToLocal`](./IChartSymbol.cs/Методы/ConvertTimeToLocal.md) | *Описание* |
| [`ConvertTimeFromLocal`](./IChartSymbol.cs/Методы/ConvertTimeFromLocal.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Code`](./IChartSymbol.cs/Свойства/Code.md) | *Описание* |
| [`Name`](./IChartSymbol.cs/Свойства/Name.md) | *Описание* |
| [`Exchange`](./IChartSymbol.cs/Свойства/Exchange.md) | *Описание* |
| [`Decimals`](./IChartSymbol.cs/Свойства/Decimals.md) | *Описание* |
| [`StepPrice`](./IChartSymbol.cs/Свойства/StepPrice.md) | *Описание* |


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

