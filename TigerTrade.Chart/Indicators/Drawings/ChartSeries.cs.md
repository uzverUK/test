
# public sealed class ChartSeries : INotifyPropertyChanged, IDynamicProperty
## Расположение
```csharp
namespace TigerTrade.Chart.Indicators.Drawings
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class ChartSeries : INotifyPropertyChanged, IDynamicProperty
```


## Методы
| Название | Описание |
| --- | --- |
| [`ChartSeries`](./ChartSeries.cs/metody/ChartSeries.md) | *Описание* |
| [`ChartSeries`](./ChartSeries.cs/metody/ChartSeries.md) | *Описание* |
| [`ChartSeries`](./ChartSeries.cs/metody/ChartSeries.md) | *Описание* |
| [`CopyTheme`](./ChartSeries.cs/metody/CopyTheme.md) | *Описание* |
| [`ToString`](./ChartSeries.cs/metody/ToString.md) | *Описание* |
| [`GetPropertyVisibility`](./ChartSeries.cs/metody/GetPropertyVisibility.md) | *Описание* |
| [`GetPropertyHasStandardValues`](./ChartSeries.cs/metody/GetPropertyHasStandardValues.md) | *Описание* |
| [`GetPropertyReadOnly`](./ChartSeries.cs/metody/GetPropertyReadOnly.md) | *Описание* |
| [`GetPropertyStandardValues`](./ChartSeries.cs/metody/GetPropertyStandardValues.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Visible`](./ChartSeries.cs/svoistva/Visible.md) | *Описание* |
| [`ShowMarker`](./ChartSeries.cs/svoistva/ShowMarker.md) | *Описание* |
| [`Type`](./ChartSeries.cs/svoistva/Type.md) | *Описание* |
| [`ColorSplit`](./ChartSeries.cs/svoistva/ColorSplit.md) | *Описание* |
| [`AllColors`](./ChartSeries.cs/svoistva/AllColors.md) | *Описание* |
| [`Color`](./ChartSeries.cs/svoistva/Color.md) | *Описание* |
| [`Color2`](./ChartSeries.cs/svoistva/Color2.md) | *Описание* |
| [`Width`](./ChartSeries.cs/svoistva/Width.md) | *Описание* |
| [`Style`](./ChartSeries.cs/svoistva/Style.md) | *Описание* |
| [`DotStyle`](./ChartSeries.cs/svoistva/DotStyle.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ChartSeries.cs/sobytiya/PropertyChanged.md) | *Описание* |


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

