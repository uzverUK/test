
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
| [`GetX`](./IChartCanvas.cs/metody/GetX.md) | *Описание* |
| [`GetXX`](./IChartCanvas.cs/metody/GetXX.md) | *Описание* |
| [`GetXScreen`](./IChartCanvas.cs/metody/GetXScreen.md) | *Описание* |
| [`GetIndex`](./IChartCanvas.cs/metody/GetIndex.md) | *Описание* |
| [`GetY`](./IChartCanvas.cs/metody/GetY.md) | *Описание* |
| [`GetValue`](./IChartCanvas.cs/metody/GetValue.md) | *Описание* |
| [`GetValueFromPos`](./IChartCanvas.cs/metody/GetValueFromPos.md) | *Описание* |
| [`GetValueFromPos`](./IChartCanvas.cs/metody/GetValueFromPos.md) | *Описание* |
| [`IndexToDate`](./IChartCanvas.cs/metody/IndexToDate.md) | *Описание* |
| [`DateToIndex`](./IChartCanvas.cs/metody/DateToIndex.md) | *Описание* |
| [`DateToIndex`](./IChartCanvas.cs/metody/DateToIndex.md) | *Описание* |
| [`ConvertTimeFromLocal`](./IChartCanvas.cs/metody/ConvertTimeFromLocal.md) | *Описание* |
| [`ConvertTimeToLocal`](./IChartCanvas.cs/metody/ConvertTimeToLocal.md) | *Описание* |
| [`FormatValue`](./IChartCanvas.cs/metody/FormatValue.md) | *Описание* |
| [`FormatTime`](./IChartCanvas.cs/metody/FormatTime.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Theme`](./IChartCanvas.cs/svoistva/Theme.md) | *Описание* |
| [`ChartFont`](./IChartCanvas.cs/svoistva/ChartFont.md) | *Описание* |
| [`ChartFontBold`](./IChartCanvas.cs/svoistva/ChartFontBold.md) | *Описание* |
| [`Rect`](./IChartCanvas.cs/svoistva/Rect.md) | *Описание* |
| [`StockType`](./IChartCanvas.cs/svoistva/StockType.md) | *Описание* |
| [`IsStock`](./IChartCanvas.cs/svoistva/IsStock.md) | *Описание* |
| [`ColumnPercent`](./IChartCanvas.cs/svoistva/ColumnPercent.md) | *Описание* |
| [`ColumnWidth`](./IChartCanvas.cs/svoistva/ColumnWidth.md) | *Описание* |
| [`StepHeight`](./IChartCanvas.cs/svoistva/StepHeight.md) | *Описание* |
| [`MaxY`](./IChartCanvas.cs/svoistva/MaxY.md) | *Описание* |
| [`MinY`](./IChartCanvas.cs/svoistva/MinY.md) | *Описание* |
| [`Start`](./IChartCanvas.cs/svoistva/Start.md) | *Описание* |
| [`Count`](./IChartCanvas.cs/svoistva/Count.md) | *Описание* |
| [`Stop`](./IChartCanvas.cs/svoistva/Stop.md) | *Описание* |
| [`AfterBars`](./IChartCanvas.cs/svoistva/AfterBars.md) | *Описание* |


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

