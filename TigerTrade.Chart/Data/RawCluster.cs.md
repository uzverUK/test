
# public sealed class RawCluster : IRawCluster
## Расположение
```csharp
namespace TigerTrade.Chart.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class RawCluster : IRawCluster
```


## Методы
| Название | Описание |
| --- | --- |
| [`RawCluster`](./RawCluster.cs/metody/RawCluster.md) | *Описание* |
| [`AddTick`](./RawCluster.cs/metody/AddTick.md) | *Описание* |
| [`AddCluster`](./RawCluster.cs/metody/AddCluster.md) | *Описание* |
| [`AddItem`](./RawCluster.cs/metody/AddItem.md) | *Описание* |
| [`UpdateData`](./RawCluster.cs/metody/UpdateData.md) | *Описание* |
| [`GetValueArea`](./RawCluster.cs/metody/GetValueArea.md) | *Описание* |
| [`GetItem`](./RawCluster.cs/metody/GetItem.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Time`](./RawCluster.cs/svoistva/Time.md) | *Описание* |
| [`OpenTime`](./RawCluster.cs/svoistva/OpenTime.md) | *Описание* |
| [`CloseTime`](./RawCluster.cs/svoistva/CloseTime.md) | *Описание* |
| [`Open`](./RawCluster.cs/svoistva/Open.md) | *Описание* |
| [`High`](./RawCluster.cs/svoistva/High.md) | *Описание* |
| [`Low`](./RawCluster.cs/svoistva/Low.md) | *Описание* |
| [`Close`](./RawCluster.cs/svoistva/Close.md) | *Описание* |
| [`Bid`](./RawCluster.cs/svoistva/Bid.md) | *Описание* |
| [`Ask`](./RawCluster.cs/svoistva/Ask.md) | *Описание* |
| [`BidTrades`](./RawCluster.cs/svoistva/BidTrades.md) | *Описание* |
| [`AskTrades`](./RawCluster.cs/svoistva/AskTrades.md) | *Описание* |
| [`OpenPos`](./RawCluster.cs/svoistva/OpenPos.md) | *Описание* |
| [`OpenPosHigh`](./RawCluster.cs/svoistva/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./RawCluster.cs/svoistva/OpenPosLow.md) | *Описание* |
| [`OpenPosBidChg`](./RawCluster.cs/svoistva/OpenPosBidChg.md) | *Описание* |
| [`OpenPosAskChg`](./RawCluster.cs/svoistva/OpenPosAskChg.md) | *Описание* |
| [`DeltaHigh`](./RawCluster.cs/svoistva/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./RawCluster.cs/svoistva/DeltaLow.md) | *Описание* |
| [`Volume`](./RawCluster.cs/svoistva/Volume.md) | *Описание* |
| [`Delta`](./RawCluster.cs/svoistva/Delta.md) | *Описание* |
| [`Trades`](./RawCluster.cs/svoistva/Trades.md) | *Описание* |
| [`OpenPosChg`](./RawCluster.cs/svoistva/OpenPosChg.md) | *Описание* |
| [`IsUp`](./RawCluster.cs/svoistva/IsUp.md) | *Описание* |
| [`MaxValues`](./RawCluster.cs/svoistva/MaxValues.md) | *Описание* |
| [`Items`](./RawCluster.cs/svoistva/Items.md) | *Описание* |


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

