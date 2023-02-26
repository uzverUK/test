
# public sealed class ConnectionInfo : INotifyPropertyChanged
## Расположение
```csharp
namespace TigerTrade.Tc
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class ConnectionInfo : INotifyPropertyChanged
```


## Методы
| Название | Описание |
| --- | --- |
| [`SetLogsPath`](./ConnectionInfo.cs/metody/SetLogsPath.md) | *Описание* |
| [`ToString`](./ConnectionInfo.cs/metody/ToString.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`TradeClientID`](./ConnectionInfo.cs/svoistva/TradeClientID.md) | *Описание* |
| [`TradeClientName`](./ConnectionInfo.cs/svoistva/TradeClientName.md) | *Описание* |
| [`TradeClientExtra`](./ConnectionInfo.cs/svoistva/TradeClientExtra.md) | *Описание* |
| [`ConnectionID`](./ConnectionInfo.cs/svoistva/ConnectionID.md) | *Описание* |
| [`ConnectionName`](./ConnectionInfo.cs/svoistva/ConnectionName.md) | *Описание* |
| [`Simulator`](./ConnectionInfo.cs/svoistva/Simulator.md) | *Описание* |
| [`Trust`](./ConnectionInfo.cs/svoistva/Trust.md) | *Описание* |
| [`MarketType`](./ConnectionInfo.cs/svoistva/MarketType.md) | *Описание* |
| [`MarketData`](./ConnectionInfo.cs/svoistva/MarketData.md) | *Описание* |
| [`AutoConnect`](./ConnectionInfo.cs/svoistva/AutoConnect.md) | *Описание* |
| [`IsConnected`](./ConnectionInfo.cs/svoistva/IsConnected.md) | *Описание* |
| [`IsConnecting`](./ConnectionInfo.cs/svoistva/IsConnecting.md) | *Описание* |
| [`ConnectState`](./ConnectionInfo.cs/svoistva/ConnectState.md) | *Описание* |
| [`AllowConnect`](./ConnectionInfo.cs/svoistva/AllowConnect.md) | *Описание* |
| [`AllowMarketData`](./ConnectionInfo.cs/svoistva/AllowMarketData.md) | *Описание* |
| [`Indicator`](./ConnectionInfo.cs/svoistva/Indicator.md) | *Описание* |
| [`Proxy`](./ConnectionInfo.cs/svoistva/Proxy.md) | *Описание* |
| [`HasProxy`](./ConnectionInfo.cs/svoistva/HasProxy.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`PropertyChanged`](./ConnectionInfo.cs/sobytiya/PropertyChanged.md) | *Описание* |


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

