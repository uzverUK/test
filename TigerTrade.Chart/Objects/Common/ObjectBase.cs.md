
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
| [`SetDataProvider`](./ObjectBase.cs/Методы/SetDataProvider.md) | *Описание* |
| [`SetSettings`](./ObjectBase.cs/Методы/SetSettings.md) | *Описание* |
| [`SetCanvas`](./ObjectBase.cs/Методы/SetCanvas.md) | *Описание* |
| [`ControlPointEditing`](./ObjectBase.cs/Методы/ControlPointEditing.md) | *Описание* |
| [`DragObject`](./ObjectBase.cs/Методы/DragObject.md) | *Описание* |
| [`BeginDrag`](./ObjectBase.cs/Методы/BeginDrag.md) | *Описание* |
| [`DrawObject`](./ObjectBase.cs/Методы/DrawObject.md) | *Описание* |
| [`DrawControlPoints`](./ObjectBase.cs/Методы/DrawControlPoints.md) | *Описание* |
| [`ControlPointsChanged`](./ObjectBase.cs/Методы/ControlPointsChanged.md) | *Описание* |
| [`ExtraPointChanged`](./ObjectBase.cs/Методы/ExtraPointChanged.md) | *Описание* |
| [`GetControlPoint`](./ObjectBase.cs/Методы/GetControlPoint.md) | *Описание* |
| [`GetExtraPoint`](./ObjectBase.cs/Методы/GetExtraPoint.md) | *Описание* |
| [`GetMinDistance`](./ObjectBase.cs/Методы/GetMinDistance.md) | *Описание* |
| [`ToPoint`](./ObjectBase.cs/Методы/ToPoint.md) | *Описание* |
| [`ApplyTheme`](./ObjectBase.cs/Методы/ApplyTheme.md) | *Описание* |
| [`CopyTemplate`](./ObjectBase.cs/Методы/CopyTemplate.md) | *Описание* |
| [`CheckAlert`](./ObjectBase.cs/Методы/CheckAlert.md) | *Описание* |
| [`GetAlerts`](./ObjectBase.cs/Методы/GetAlerts.md) | *Описание* |
| [`GetPropertyVisibility`](./ObjectBase.cs/Методы/GetPropertyVisibility.md) | *Описание* |
| [`GetPropertyHasStandardValues`](./ObjectBase.cs/Методы/GetPropertyHasStandardValues.md) | *Описание* |
| [`GetPropertyReadOnly`](./ObjectBase.cs/Методы/GetPropertyReadOnly.md) | *Описание* |
| [`GetPropertyStandardValues`](./ObjectBase.cs/Методы/GetPropertyStandardValues.md) | *Описание* |
| [`ToString`](./ObjectBase.cs/Методы/ToString.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`InMove;`](./ObjectBase.cs/Свойства/InMove;.md) | *Описание* |
| [`InSetup;`](./ObjectBase.cs/Свойства/InSetup;.md) | *Описание* |
| [`ID`](./ObjectBase.cs/Свойства/ID.md) | *Описание* |
| [`Name`](./ObjectBase.cs/Свойства/Name.md) | *Описание* |
| [`ControlPointNum`](./ObjectBase.cs/Свойства/ControlPointNum.md) | *Описание* |
| [`ChartDataType`](./ObjectBase.cs/Свойства/ChartDataType.md) | *Описание* |
| [`SymbolID`](./ObjectBase.cs/Свойства/SymbolID.md) | *Описание* |
| [`ObjectID`](./ObjectBase.cs/Свойства/ObjectID.md) | *Описание* |
| [`ControlPoints`](./ObjectBase.cs/Свойства/ControlPoints.md) | *Описание* |
| [`Periods`](./ObjectBase.cs/Свойства/Periods.md) | *Описание* |
| [`Position`](./ObjectBase.cs/Свойства/Position.md) | *Описание* |
| [`Lock`](./ObjectBase.cs/Свойства/Lock.md) | *Описание* |
| [`SnapGrid`](./ObjectBase.cs/Свойства/SnapGrid.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ObjectBase.cs/События/PropertyChanged.md) | *Описание* |


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

