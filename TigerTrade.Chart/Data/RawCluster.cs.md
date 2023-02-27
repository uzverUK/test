
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
| [`RawCluster`](./RawCluster.cs/Методы/RawCluster.md) | *Описание* |
| [`AddTick`](./RawCluster.cs/Методы/AddTick.md) | *Описание* |
| [`AddCluster`](./RawCluster.cs/Методы/AddCluster.md) | *Описание* |
| [`AddItem`](./RawCluster.cs/Методы/AddItem.md) | *Описание* |
| [`UpdateData`](./RawCluster.cs/Методы/UpdateData.md) | *Описание* |
| [`GetValueArea`](./RawCluster.cs/Методы/GetValueArea.md) | *Описание* |
| [`GetItem`](./RawCluster.cs/Методы/GetItem.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Time`](./RawCluster.cs/Свойства/Time.md) | *Описание* |
| [`OpenTime`](./RawCluster.cs/Свойства/OpenTime.md) | *Описание* |
| [`CloseTime`](./RawCluster.cs/Свойства/CloseTime.md) | *Описание* |
| [`Open`](./RawCluster.cs/Свойства/Open.md) | *Описание* |
| [`High`](./RawCluster.cs/Свойства/High.md) | *Описание* |
| [`Low`](./RawCluster.cs/Свойства/Low.md) | *Описание* |
| [`Close`](./RawCluster.cs/Свойства/Close.md) | *Описание* |
| [`Bid`](./RawCluster.cs/Свойства/Bid.md) | *Описание* |
| [`Ask`](./RawCluster.cs/Свойства/Ask.md) | *Описание* |
| [`BidTrades`](./RawCluster.cs/Свойства/BidTrades.md) | *Описание* |
| [`AskTrades`](./RawCluster.cs/Свойства/AskTrades.md) | *Описание* |
| [`OpenPos`](./RawCluster.cs/Свойства/OpenPos.md) | *Описание* |
| [`OpenPosHigh`](./RawCluster.cs/Свойства/OpenPosHigh.md) | *Описание* |
| [`OpenPosLow`](./RawCluster.cs/Свойства/OpenPosLow.md) | *Описание* |
| [`OpenPosBidChg`](./RawCluster.cs/Свойства/OpenPosBidChg.md) | *Описание* |
| [`OpenPosAskChg`](./RawCluster.cs/Свойства/OpenPosAskChg.md) | *Описание* |
| [`DeltaHigh`](./RawCluster.cs/Свойства/DeltaHigh.md) | *Описание* |
| [`DeltaLow`](./RawCluster.cs/Свойства/DeltaLow.md) | *Описание* |
| [`Volume`](./RawCluster.cs/Свойства/Volume.md) | *Описание* |
| [`Delta`](./RawCluster.cs/Свойства/Delta.md) | *Описание* |
| [`Trades`](./RawCluster.cs/Свойства/Trades.md) | *Описание* |
| [`OpenPosChg`](./RawCluster.cs/Свойства/OpenPosChg.md) | *Описание* |
| [`IsUp`](./RawCluster.cs/Свойства/IsUp.md) | *Описание* |
| [`MaxValues`](./RawCluster.cs/Свойства/MaxValues.md) | *Описание* |
| [`Items`](./RawCluster.cs/Свойства/Items.md) | *Описание* |


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

