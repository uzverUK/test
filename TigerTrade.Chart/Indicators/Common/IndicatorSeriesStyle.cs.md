
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
| [`IndicatorSeriesStyle`](./IndicatorSeriesStyle.cs/Методы/IndicatorSeriesStyle.md) | *Описание* |
| [`Set`](./IndicatorSeriesStyle.cs/Методы/Set.md) | *Описание* |
| [`Set`](./IndicatorSeriesStyle.cs/Методы/Set.md) | *Описание* |
| [`Set`](./IndicatorSeriesStyle.cs/Методы/Set.md) | *Описание* |
| [`DisableAll`](./IndicatorSeriesStyle.cs/Методы/DisableAll.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Visible;`](./IndicatorSeriesStyle.cs/Свойства/Visible;.md) | *Описание* |
| [`Name;`](./IndicatorSeriesStyle.cs/Свойства/Name;.md) | *Описание* |
| [`DisableMinMax;`](./IndicatorSeriesStyle.cs/Свойства/DisableMinMax;.md) | *Описание* |
| [`DisableSelect;`](./IndicatorSeriesStyle.cs/Свойства/DisableSelect;.md) | *Описание* |
| [`DisableLabel;`](./IndicatorSeriesStyle.cs/Свойства/DisableLabel;.md) | *Описание* |
| [`DisableValue;`](./IndicatorSeriesStyle.cs/Свойства/DisableValue;.md) | *Описание* |
| [`HighPercent;`](./IndicatorSeriesStyle.cs/Свойства/HighPercent;.md) | *Описание* |
| [`LowPercent;`](./IndicatorSeriesStyle.cs/Свойства/LowPercent;.md) | *Описание* |
| [`RenderType;`](./IndicatorSeriesStyle.cs/Свойства/RenderType;.md) | *Описание* |
| [`DotType;`](./IndicatorSeriesStyle.cs/Свойства/DotType;.md) | *Описание* |
| [`ColorSplit;`](./IndicatorSeriesStyle.cs/Свойства/ColorSplit;.md) | *Описание* |
| [`Color;`](./IndicatorSeriesStyle.cs/Свойства/Color;.md) | *Описание* |
| [`Color2;`](./IndicatorSeriesStyle.cs/Свойства/Color2;.md) | *Описание* |
| [`LineWidth;`](./IndicatorSeriesStyle.cs/Свойства/LineWidth;.md) | *Описание* |
| [`LineStyle;`](./IndicatorSeriesStyle.cs/Свойства/LineStyle;.md) | *Описание* |
| [`StraightLine;`](./IndicatorSeriesStyle.cs/Свойства/StraightLine;.md) | *Описание* |


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

