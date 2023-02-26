
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
| [`GetItem`](./IRawCluster.cs/metody/GetItem.md) | *Описание* |
| [`GetValueArea`](./IRawCluster.cs/metody/GetValueArea.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Time`](./IRawCluster.cs/svoistva/Time.md) | *Описание* |
| [`OpenTime`](./IRawCluster.cs/svoistva/OpenTime.md) | *Описание* |
| [`CloseTime`](./IRawCluster.cs/svoistva/CloseTime.md) | *Описание* |
| [`Open`](./IRawCluster.cs/svoistva/Open.md) | *Описание* |
| [`High`](./IRawCluster.cs/svoistva/High.md) | *Описание* |
| [`Low`](./IRawCluster.cs/svoistva/Low.md) | *Описание* |
| [`Close`](./IRawCluster.cs/svoistva/Close.md) | *Описание* |
| [`Bid`](./IRawCluster.cs/svoistva/Bid.md) | *Описание* |
| [`Ask`](./IRawCluster.cs/svoistva/Ask.md) | *Описание* |
| [`Volume`](./IRawCluster.cs/svoistva/Volume.md) | *Описание* |
| [`Delta`](./IRawCluster.cs/svoistva/Delta.md) | *Описание* |
| [`BidTrades`](./IRawCluster.cs/svoistva/BidTrades.md) | *Описание* |
| [`AskTrades`](./IRawCluster.cs/svoistva/AskTrades.md) | *Описание* |
| [`Trades`](./IRawCluster.cs/svoistva/Trades.md) | *Описание* |
| [`OpenPos`](./IRawCluster.cs/svoistva/OpenPos.md) | *Описание* |
| [`OpenPosHigh`](./IRawCluster.cs/svoistva/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./IRawCluster.cs/svoistva/OpenPosLow.md) | *Описание* |
| [`OpenPosBidChg`](./IRawCluster.cs/svoistva/OpenPosBidChg.md) | *Описание* |
| [`OpenPosAskChg`](./IRawCluster.cs/svoistva/OpenPosAskChg.md) | *Описание* |
| [`OpenPosChg`](./IRawCluster.cs/svoistva/OpenPosChg.md) | *Описание* |
| [`DeltaHigh`](./IRawCluster.cs/svoistva/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./IRawCluster.cs/svoistva/DeltaLow.md) | *Описание* |
| [`IsUp`](./IRawCluster.cs/svoistva/IsUp.md) | *Описание* |
| [`MaxValues`](./IRawCluster.cs/svoistva/MaxValues.md) | *Описание* |


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

