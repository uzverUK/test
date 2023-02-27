
# public interface IRawCluster
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public interface IRawCluster
```


## Методы
| Название | Описание |
| --- | --- |
| [`GetItem`](./IRawCluster.cs/Методы/GetItem.md) | *Описание* |
| [`GetValueArea`](./IRawCluster.cs/Методы/GetValueArea.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Time`](./IRawCluster.cs/Свойства/Time.md) | *Описание* |
| [`OpenTime`](./IRawCluster.cs/Свойства/OpenTime.md) | *Описание* |
| [`CloseTime`](./IRawCluster.cs/Свойства/CloseTime.md) | *Описание* |
| [`Open`](./IRawCluster.cs/Свойства/Open.md) | *Описание* |
| [`High`](./IRawCluster.cs/Свойства/High.md) | *Описание* |
| [`Low`](./IRawCluster.cs/Свойства/Low.md) | *Описание* |
| [`Close`](./IRawCluster.cs/Свойства/Close.md) | *Описание* |
| [`Bid`](./IRawCluster.cs/Свойства/Bid.md) | *Описание* |
| [`Ask`](./IRawCluster.cs/Свойства/Ask.md) | *Описание* |
| [`Volume`](./IRawCluster.cs/Свойства/Volume.md) | *Описание* |
| [`Delta`](./IRawCluster.cs/Свойства/Delta.md) | *Описание* |
| [`BidTrades`](./IRawCluster.cs/Свойства/BidTrades.md) | *Описание* |
| [`AskTrades`](./IRawCluster.cs/Свойства/AskTrades.md) | *Описание* |
| [`Trades`](./IRawCluster.cs/Свойства/Trades.md) | *Описание* |
| [`OpenPos`](./IRawCluster.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosHigh`](./IRawCluster.cs/Свойства/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./IRawCluster.cs/Свойства/OpenPosLow.md) | *Описание* |
| [`OpenPosBidChg`](./IRawCluster.cs/Свойства/OpenPosBidChg.md) | *Описание* |
| [`OpenPosAskChg`](./IRawCluster.cs/Свойства/OpenPosAskChg.md) | *Описание* |
| [`OpenPosChg`](./IRawCluster.cs/Свойства/OpenPosChg.md) | *Описание* |
| [`DeltaHigh`](./IRawCluster.cs/Свойства/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./IRawCluster.cs/Свойства/DeltaLow.md) | *Описание* |
| [`IsUp`](./IRawCluster.cs/Свойства/IsUp.md) | *Описание* |
| [`MaxValues`](./IRawCluster.cs/Свойства/MaxValues.md) | *Описание* |


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

