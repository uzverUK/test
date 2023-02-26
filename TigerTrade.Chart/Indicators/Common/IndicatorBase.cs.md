
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
| [`Run`](./IndicatorBase.cs/metody/Run.md) | *Описание* |
| [`GetMinMax`](./IndicatorBase.cs/metody/GetMinMax.md) | *Описание* |
| [`GetDistance`](./IndicatorBase.cs/metody/GetDistance.md) | *Описание* |
| [`GetTitle`](./IndicatorBase.cs/metody/GetTitle.md) | *Описание* |
| [`GetValues`](./IndicatorBase.cs/metody/GetValues.md) | *Описание* |
| [`GetLabels`](./IndicatorBase.cs/metody/GetLabels.md) | *Описание* |
| [`Render`](./IndicatorBase.cs/metody/Render.md) | *Описание* |
| [`GetAlerts`](./IndicatorBase.cs/metody/GetAlerts.md) | *Описание* |
| [`ApplyColors`](./IndicatorBase.cs/metody/ApplyColors.md) | *Описание* |
| [`CopyTemplate`](./IndicatorBase.cs/metody/CopyTemplate.md) | *Описание* |
| [`ToString`](./IndicatorBase.cs/metody/ToString.md) | *Описание* |
| [`CheckNeedRedraw`](./IndicatorBase.cs/metody/CheckNeedRedraw.md) | *Описание* |
| [`SetSettingsParam`](./IndicatorBase.cs/metody/SetSettingsParam.md) | *Описание* |
| [`GetPropertyVisibility`](./IndicatorBase.cs/metody/GetPropertyVisibility.md) | *Описание* |
| [`GetPropertyHasStandardValues`](./IndicatorBase.cs/metody/GetPropertyHasStandardValues.md) | *Описание* |
| [`GetPropertyReadOnly`](./IndicatorBase.cs/metody/GetPropertyReadOnly.md) | *Описание* |
| [`GetPropertyStandardValues`](./IndicatorBase.cs/metody/GetPropertyStandardValues.md) | *Описание* |
| [`PropChanged`](./IndicatorBase.cs/metody/PropChanged.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Levels`](./IndicatorBase.cs/svoistva/Levels.md) | *Описание* |
| [`ID`](./IndicatorBase.cs/svoistva/ID.md) | *Описание* |
| [`Name`](./IndicatorBase.cs/svoistva/Name.md) | *Описание* |
| [`ChartDataType`](./IndicatorBase.cs/svoistva/ChartDataType.md) | *Описание* |
| [`IsStock`](./IndicatorBase.cs/svoistva/IsStock.md) | *Описание* |
| [`IntegerValues`](./IndicatorBase.cs/svoistva/IntegerValues.md) | *Описание* |
| [`DisableRender`](./IndicatorBase.cs/svoistva/DisableRender.md) | *Описание* |
| [`Canvas`](./IndicatorBase.cs/svoistva/Canvas.md) | *Описание* |
| [`ShowIndicatorParam`](./IndicatorBase.cs/svoistva/ShowIndicatorParam.md) | *Описание* |
| [`ShowIndicator`](./IndicatorBase.cs/svoistva/ShowIndicator.md) | *Описание* |
| [`ShowIndicatorTitleParam`](./IndicatorBase.cs/svoistva/ShowIndicatorTitleParam.md) | *Описание* |
| [`ShowIndicatorTitle`](./IndicatorBase.cs/svoistva/ShowIndicatorTitle.md) | *Описание* |
| [`ShowIndicatorValuesParam`](./IndicatorBase.cs/svoistva/ShowIndicatorValuesParam.md) | *Описание* |
| [`ShowIndicatorValues`](./IndicatorBase.cs/svoistva/ShowIndicatorValues.md) | *Описание* |
| [`ShowIndicatorLabelsParam`](./IndicatorBase.cs/svoistva/ShowIndicatorLabelsParam.md) | *Описание* |
| [`ShowIndicatorLabels`](./IndicatorBase.cs/svoistva/ShowIndicatorLabels.md) | *Описание* |
| [`DefaultCalculation`](./IndicatorBase.cs/svoistva/DefaultCalculation.md) | *Описание* |
| [`Calculation`](./IndicatorBase.cs/svoistva/Calculation.md) | *Описание* |
| [`Panel`](./IndicatorBase.cs/svoistva/Panel.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./IndicatorBase.cs/sobytiya/PropertyChanged.md) | *Описание* |


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

