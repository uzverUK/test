
# public interface IChartCanvas
## Расположение
```csharp
namespace TigerTrade.Chart.Base
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public interface IChartCanvas
```


## Методы
| Название | Описание |
| --- | --- |
| [`GetX`](./IChartCanvas.cs/Методы/GetX.md) | *Описание* |
| [`GetXX`](./IChartCanvas.cs/Методы/GetXX.md) | *Описание* |
| [`GetXScreen`](./IChartCanvas.cs/Методы/GetXScreen.md) | *Описание* |
| [`GetIndex`](./IChartCanvas.cs/Методы/GetIndex.md) | *Описание* |
| [`GetY`](./IChartCanvas.cs/Методы/GetY.md) | *Описание* |
| [`GetValue`](./IChartCanvas.cs/Методы/GetValue.md) | *Описание* |
| [`GetValueFromPos`](./IChartCanvas.cs/Методы/GetValueFromPos.md) | *Описание* |
| [`GetValueFromPos`](./IChartCanvas.cs/Методы/GetValueFromPos.md) | *Описание* |
| [`IndexToDate`](./IChartCanvas.cs/Методы/IndexToDate.md) | *Описание* |
| [`DateToIndex`](./IChartCanvas.cs/Методы/DateToIndex.md) | *Описание* |
| [`DateToIndex`](./IChartCanvas.cs/Методы/DateToIndex.md) | *Описание* |
| [`ConvertTimeFromLocal`](./IChartCanvas.cs/Методы/ConvertTimeFromLocal.md) | *Описание* |
| [`ConvertTimeToLocal`](./IChartCanvas.cs/Методы/ConvertTimeToLocal.md) | *Описание* |
| [`FormatValue`](./IChartCanvas.cs/Методы/FormatValue.md) | *Описание* |
| [`FormatTime`](./IChartCanvas.cs/Методы/FormatTime.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Theme`](./IChartCanvas.cs/Свойства/Theme.md) | *Описание* |
| [`ChartFont`](./IChartCanvas.cs/Свойства/ChartFont.md) | *Описание* |
| [`ChartFontBold`](./IChartCanvas.cs/Свойства/ChartFontBold.md) | *Описание* |
| [`Rect`](./IChartCanvas.cs/Свойства/Rect.md) | *Описание* |
| [`StockType`](./IChartCanvas.cs/Свойства/StockType.md) | *Описание* |
| [`IsStock`](./IChartCanvas.cs/Свойства/IsStock.md) | *Описание* |
| [`ColumnPercent`](./IChartCanvas.cs/Свойства/ColumnPercent.md) | *Описание* |
| [`ColumnWidth`](./IChartCanvas.cs/Свойства/ColumnWidth.md) | *Описание* |
| [`StepHeight`](./IChartCanvas.cs/Свойства/StepHeight.md) | *Описание* |
| [`MaxY`](./IChartCanvas.cs/Свойства/MaxY.md) | *Описание* |
| [`MinY`](./IChartCanvas.cs/Свойства/MinY.md) | *Описание* |
| [`Start`](./IChartCanvas.cs/Свойства/Start.md) | *Описание* |
| [`Count`](./IChartCanvas.cs/Свойства/Count.md) | *Описание* |
| [`Stop`](./IChartCanvas.cs/Свойства/Stop.md) | *Описание* |
| [`AfterBars`](./IChartCanvas.cs/Свойства/AfterBars.md) | *Описание* |


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

