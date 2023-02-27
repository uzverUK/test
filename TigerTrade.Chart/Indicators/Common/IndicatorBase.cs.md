
# public abstract class IndicatorBase : INotifyPropertyChanged, IDynamicProperty
## Расположение
```csharp
namespace TigerTrade.Chart.Indicators.Common
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public abstract class IndicatorBase : INotifyPropertyChanged, IDynamicProperty
```


## Методы
| Название | Описание |
| --- | --- |
| [`Run`](./IndicatorBase.cs/Методы/Run.md) | *Описание* |
| [`GetMinMax`](./IndicatorBase.cs/Методы/GetMinMax.md) | *Описание* |
| [`GetDistance`](./IndicatorBase.cs/Методы/GetDistance.md) | *Описание* |
| [`GetTitle`](./IndicatorBase.cs/Методы/GetTitle.md) | *Описание* |
| [`GetValues`](./IndicatorBase.cs/Методы/GetValues.md) | *Описание* |
| [`GetLabels`](./IndicatorBase.cs/Методы/GetLabels.md) | *Описание* |
| [`Render`](./IndicatorBase.cs/Методы/Render.md) | *Описание* |
| [`GetAlerts`](./IndicatorBase.cs/Методы/GetAlerts.md) | *Описание* |
| [`ApplyColors`](./IndicatorBase.cs/Методы/ApplyColors.md) | *Описание* |
| [`CopyTemplate`](./IndicatorBase.cs/Методы/CopyTemplate.md) | *Описание* |
| [`ToString`](./IndicatorBase.cs/Методы/ToString.md) | *Описание* |
| [`CheckNeedRedraw`](./IndicatorBase.cs/Методы/CheckNeedRedraw.md) | *Описание* |
| [`SetSettingsParam`](./IndicatorBase.cs/Методы/SetSettingsParam.md) | *Описание* |
| [`GetPropertyVisibility`](./IndicatorBase.cs/Методы/GetPropertyVisibility.md) | *Описание* |
| [`GetPropertyHasStandardValues`](./IndicatorBase.cs/Методы/GetPropertyHasStandardValues.md) | *Описание* |
| [`GetPropertyReadOnly`](./IndicatorBase.cs/Методы/GetPropertyReadOnly.md) | *Описание* |
| [`GetPropertyStandardValues`](./IndicatorBase.cs/Методы/GetPropertyStandardValues.md) | *Описание* |
| [`PropChanged`](./IndicatorBase.cs/Методы/PropChanged.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Levels`](./IndicatorBase.cs/Свойства/Levels.md) | *Описание* |
| [`ID`](./IndicatorBase.cs/Свойства/ID.md) | *Описание* |
| [`Name`](./IndicatorBase.cs/Свойства/Name.md) | *Описание* |
| [`ChartDataType`](./IndicatorBase.cs/Свойства/ChartDataType.md) | *Описание* |
| [`IsStock`](./IndicatorBase.cs/Свойства/IsStock.md) | *Описание* |
| [`IntegerValues`](./IndicatorBase.cs/Свойства/IntegerValues.md) | *Описание* |
| [`DisableRender`](./IndicatorBase.cs/Свойства/DisableRender.md) | *Описание* |
| [`Canvas`](./IndicatorBase.cs/Свойства/Canvas.md) | *Описание* |
| [`ShowIndicatorParam`](./IndicatorBase.cs/Свойства/ShowIndicatorParam.md) | *Описание* |
| [`ShowIndicator`](./IndicatorBase.cs/Свойства/ShowIndicator.md) | *Описание* |
| [`ShowIndicatorTitleParam`](./IndicatorBase.cs/Свойства/ShowIndicatorTitleParam.md) | *Описание* |
| [`ShowIndicatorTitle`](./IndicatorBase.cs/Свойства/ShowIndicatorTitle.md) | *Описание* |
| [`ShowIndicatorValuesParam`](./IndicatorBase.cs/Свойства/ShowIndicatorValuesParam.md) | *Описание* |
| [`ShowIndicatorValues`](./IndicatorBase.cs/Свойства/ShowIndicatorValues.md) | *Описание* |
| [`ShowIndicatorLabelsParam`](./IndicatorBase.cs/Свойства/ShowIndicatorLabelsParam.md) | *Описание* |
| [`ShowIndicatorLabels`](./IndicatorBase.cs/Свойства/ShowIndicatorLabels.md) | *Описание* |
| [`DefaultCalculation`](./IndicatorBase.cs/Свойства/DefaultCalculation.md) | *Описание* |
| [`Calculation`](./IndicatorBase.cs/Свойства/Calculation.md) | *Описание* |
| [`Panel`](./IndicatorBase.cs/Свойства/Panel.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./IndicatorBase.cs/События/PropertyChanged.md) | *Описание* |


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

