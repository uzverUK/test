
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
| [`ChartSeries`](./ChartSeries.cs/Методы/ChartSeries.md) | *Описание* |
| [`ChartSeries`](./ChartSeries.cs/Методы/ChartSeries.md) | *Описание* |
| [`ChartSeries`](./ChartSeries.cs/Методы/ChartSeries.md) | *Описание* |
| [`CopyTheme`](./ChartSeries.cs/Методы/CopyTheme.md) | *Описание* |
| [`ToString`](./ChartSeries.cs/Методы/ToString.md) | *Описание* |
| [`GetPropertyVisibility`](./ChartSeries.cs/Методы/GetPropertyVisibility.md) | *Описание* |
| [`GetPropertyHasStandardValues`](./ChartSeries.cs/Методы/GetPropertyHasStandardValues.md) | *Описание* |
| [`GetPropertyReadOnly`](./ChartSeries.cs/Методы/GetPropertyReadOnly.md) | *Описание* |
| [`GetPropertyStandardValues`](./ChartSeries.cs/Методы/GetPropertyStandardValues.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Visible`](./ChartSeries.cs/Свойства/Visible.md) | *Описание* |
| [`ShowMarker`](./ChartSeries.cs/Свойства/ShowMarker.md) | *Описание* |
| [`Type`](./ChartSeries.cs/Свойства/Type.md) | *Описание* |
| [`ColorSplit`](./ChartSeries.cs/Свойства/ColorSplit.md) | *Описание* |
| [`AllColors`](./ChartSeries.cs/Свойства/AllColors.md) | *Описание* |
| [`Color`](./ChartSeries.cs/Свойства/Color.md) | *Описание* |
| [`Color2`](./ChartSeries.cs/Свойства/Color2.md) | *Описание* |
| [`Width`](./ChartSeries.cs/Свойства/Width.md) | *Описание* |
| [`Style`](./ChartSeries.cs/Свойства/Style.md) | *Описание* |
| [`DotStyle`](./ChartSeries.cs/Свойства/DotStyle.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ChartSeries.cs/События/PropertyChanged.md) | *Описание* |


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

