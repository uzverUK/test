
# public sealed class IndicatorSeriesStyle
## Расположение
```csharp
namespace TigerTrade.Chart.Indicators.Common
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class IndicatorSeriesStyle
```


## Методы
| Название | Описание |
| --- | --- |
| [`IndicatorSeriesStyle`](./IndicatorSeriesStyle.cs/metody/IndicatorSeriesStyle.md) | *Описание* |
| [`Set`](./IndicatorSeriesStyle.cs/metody/Set.md) | *Описание* |
| [`Set`](./IndicatorSeriesStyle.cs/metody/Set.md) | *Описание* |
| [`Set`](./IndicatorSeriesStyle.cs/metody/Set.md) | *Описание* |
| [`DisableAll`](./IndicatorSeriesStyle.cs/metody/DisableAll.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Visible;`](./IndicatorSeriesStyle.cs/svoistva/Visible;.md) | *Описание* |
| [`Name;`](./IndicatorSeriesStyle.cs/svoistva/Name;.md) | *Описание* |
| [`DisableMinMax;`](./IndicatorSeriesStyle.cs/svoistva/DisableMinMax;.md) | *Описание* |
| [`DisableSelect;`](./IndicatorSeriesStyle.cs/svoistva/DisableSelect;.md) | *Описание* |
| [`DisableLabel;`](./IndicatorSeriesStyle.cs/svoistva/DisableLabel;.md) | *Описание* |
| [`DisableValue;`](./IndicatorSeriesStyle.cs/svoistva/DisableValue;.md) | *Описание* |
| [`HighPercent;`](./IndicatorSeriesStyle.cs/svoistva/HighPercent;.md) | *Описание* |
| [`LowPercent;`](./IndicatorSeriesStyle.cs/svoistva/LowPercent;.md) | *Описание* |
| [`RenderType;`](./IndicatorSeriesStyle.cs/svoistva/RenderType;.md) | *Описание* |
| [`DotType;`](./IndicatorSeriesStyle.cs/svoistva/DotType;.md) | *Описание* |
| [`ColorSplit;`](./IndicatorSeriesStyle.cs/svoistva/ColorSplit;.md) | *Описание* |
| [`Color;`](./IndicatorSeriesStyle.cs/svoistva/Color;.md) | *Описание* |
| [`Color2;`](./IndicatorSeriesStyle.cs/svoistva/Color2;.md) | *Описание* |
| [`LineWidth;`](./IndicatorSeriesStyle.cs/svoistva/LineWidth;.md) | *Описание* |
| [`LineStyle;`](./IndicatorSeriesStyle.cs/svoistva/LineStyle;.md) | *Описание* |
| [`StraightLine;`](./IndicatorSeriesStyle.cs/svoistva/StraightLine;.md) | *Описание* |


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

