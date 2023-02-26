
# public abstract class ObjectBase : INotifyPropertyChanged, IDynamicProperty
## Расположение
```csharp
namespace TigerTrade.Chart.Objects.Common
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public abstract class ObjectBase : INotifyPropertyChanged, IDynamicProperty
```


## Методы
| Название | Описание |
| --- | --- |
| [`SetDataProvider`](./ObjectBase.cs/metody/SetDataProvider.md) | *Описание* |
| [`SetSettings`](./ObjectBase.cs/metody/SetSettings.md) | *Описание* |
| [`SetCanvas`](./ObjectBase.cs/metody/SetCanvas.md) | *Описание* |
| [`ControlPointEditing`](./ObjectBase.cs/metody/ControlPointEditing.md) | *Описание* |
| [`DragObject`](./ObjectBase.cs/metody/DragObject.md) | *Описание* |
| [`BeginDrag`](./ObjectBase.cs/metody/BeginDrag.md) | *Описание* |
| [`DrawObject`](./ObjectBase.cs/metody/DrawObject.md) | *Описание* |
| [`DrawControlPoints`](./ObjectBase.cs/metody/DrawControlPoints.md) | *Описание* |
| [`ControlPointsChanged`](./ObjectBase.cs/metody/ControlPointsChanged.md) | *Описание* |
| [`ExtraPointChanged`](./ObjectBase.cs/metody/ExtraPointChanged.md) | *Описание* |
| [`GetControlPoint`](./ObjectBase.cs/metody/GetControlPoint.md) | *Описание* |
| [`GetExtraPoint`](./ObjectBase.cs/metody/GetExtraPoint.md) | *Описание* |
| [`GetMinDistance`](./ObjectBase.cs/metody/GetMinDistance.md) | *Описание* |
| [`ToPoint`](./ObjectBase.cs/metody/ToPoint.md) | *Описание* |
| [`ApplyTheme`](./ObjectBase.cs/metody/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./ObjectBase.cs/metody/CopyTemplate.md) | *Описание* |
| [`CheckAlert`](./ObjectBase.cs/metody/CheckAlert.md) | *Описание* |
| [`GetAlerts`](./ObjectBase.cs/metody/GetAlerts.md) | *Описание* |
| [`GetPropertyVisibility`](./ObjectBase.cs/metody/GetPropertyVisibility.md) | *Описание* |
| [`GetPropertyHasStandardValues`](./ObjectBase.cs/metody/GetPropertyHasStandardValues.md) | *Описание* |
| [`GetPropertyReadOnly`](./ObjectBase.cs/metody/GetPropertyReadOnly.md) | *Описание* |
| [`GetPropertyStandardValues`](./ObjectBase.cs/metody/GetPropertyStandardValues.md) | *Описание* |
| [`ToString`](./ObjectBase.cs/metody/ToString.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`InMove;`](./ObjectBase.cs/svoistva/InMove;.md) | *Описание* |
| [`InSetup;`](./ObjectBase.cs/svoistva/InSetup;.md) | *Описание* |
| [`ID`](./ObjectBase.cs/svoistva/ID.md) | *Описание* |
| [`Name`](./ObjectBase.cs/svoistva/Name.md) | *Описание* |
| [`ControlPointNum`](./ObjectBase.cs/svoistva/ControlPointNum.md) | *Описание* |
| [`ChartDataType`](./ObjectBase.cs/svoistva/ChartDataType.md) | *Описание* |
| [`SymbolID`](./ObjectBase.cs/svoistva/SymbolID.md) | *Описание* |
| [`ObjectID`](./ObjectBase.cs/svoistva/ObjectID.md) | *Описание* |
| [`ControlPoints`](./ObjectBase.cs/svoistva/ControlPoints.md) | *Описание* |
| [`Periods`](./ObjectBase.cs/svoistva/Periods.md) | *Описание* |
| [`Position`](./ObjectBase.cs/svoistva/Position.md) | *Описание* |
| [`Lock`](./ObjectBase.cs/svoistva/Lock.md) | *Описание* |
| [`SnapGrid`](./ObjectBase.cs/svoistva/SnapGrid.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ObjectBase.cs/sobytiya/PropertyChanged.md) | *Описание* |


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

