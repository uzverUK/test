
# public static class DataManager
## Расположение
```csharp
namespace TigerTrade.Tc.Manager
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public static class DataManager
```


## Методы
| Название | Описание |
| --- | --- |
| [`ProcessMarketData`](./DataManager.cs/metody/ProcessMarketData.md) | *Описание* |
| [`ProcessTradeData`](./DataManager.cs/metody/ProcessTradeData.md) | *Описание* |
| [`Subscribe`](./DataManager.cs/metody/Subscribe.md) | *Описание* |
| [`UnSubscribe`](./DataManager.cs/metody/UnSubscribe.md) | *Описание* |
| [`GetConnectionsInfo`](./DataManager.cs/metody/GetConnectionsInfo.md) | *Описание* |
| [`GetConnectionInfo`](./DataManager.cs/metody/GetConnectionInfo.md) | *Описание* |
| [`GetSimAccounts`](./DataManager.cs/metody/GetSimAccounts.md) | *Описание* |
| [`GetAccount`](./DataManager.cs/metody/GetAccount.md) | *Описание* |
| [`GetAccounts`](./DataManager.cs/metody/GetAccounts.md) | *Описание* |
| [`GetAccounts`](./DataManager.cs/metody/GetAccounts.md) | *Описание* |
| [`GetUserPosition`](./DataManager.cs/metody/GetUserPosition.md) | *Описание* |
| [`IsTradeAllowed`](./DataManager.cs/metody/IsTradeAllowed.md) | *Описание* |
| [`IsTradeAllowed`](./DataManager.cs/metody/IsTradeAllowed.md) | *Описание* |
| [`IsClientConnected`](./DataManager.cs/metody/IsClientConnected.md) | *Описание* |
| [`ClientConnect`](./DataManager.cs/metody/ClientConnect.md) | *Описание* |
| [`ClientDisconnect`](./DataManager.cs/metody/ClientDisconnect.md) | *Описание* |
| [`ClientPlaceOrder`](./DataManager.cs/metody/ClientPlaceOrder.md) | *Описание* |
| [`ClientModifyOrder`](./DataManager.cs/metody/ClientModifyOrder.md) | *Описание* |
| [`ClientCancelOrder`](./DataManager.cs/metody/ClientCancelOrder.md) | *Описание* |
| [`ClientCancelAllOrders`](./DataManager.cs/metody/ClientCancelAllOrders.md) | *Описание* |
| [`ClientUpdateUserPosition`](./DataManager.cs/metody/ClientUpdateUserPosition.md) | *Описание* |
| [`GetOrders`](./DataManager.cs/metody/GetOrders.md) | *Описание* |
| [`GetExecutions`](./DataManager.cs/metody/GetExecutions.md) | *Описание* |
| [`GetOrdersCount`](./DataManager.cs/metody/GetOrdersCount.md) | *Описание* |
| [`GetPositionsCount`](./DataManager.cs/metody/GetPositionsCount.md) | *Описание* |
| [`SyncSlTp`](./DataManager.cs/metody/SyncSlTp.md) | *Описание* |
| [`LoadTrustAccounts`](./DataManager.cs/metody/LoadTrustAccounts.md) | *Описание* |
| [`SetTradeMode`](./DataManager.cs/metody/SetTradeMode.md) | *Описание* |
| [`FilterAccount`](./DataManager.cs/metody/FilterAccount.md) | *Описание* |
| [`FilterAccount`](./DataManager.cs/metody/FilterAccount.md) | *Описание* |
| [`AutoConnect`](./DataManager.cs/metody/AutoConnect.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Simulator`](./DataManager.cs/svoistva/Simulator.md) | *Описание* |
| [`Player`](./DataManager.cs/svoistva/Player.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`OnError;`](./DataManager.cs/sobytiya/OnError;.md) | *Описание* |
| [`OnInfo;`](./DataManager.cs/sobytiya/OnInfo;.md) | *Описание* |
| [`OnConnected;`](./DataManager.cs/sobytiya/OnConnected;.md) | *Описание* |
| [`OnDisconnected;`](./DataManager.cs/sobytiya/OnDisconnected;.md) | *Описание* |
| [`OnAccountsReady;`](./DataManager.cs/sobytiya/OnAccountsReady;.md) | *Описание* |
| [`Action`](./DataManager.cs/sobytiya/Action.md) | *Описание* |
| [`Action`](./DataManager.cs/sobytiya/Action.md) | *Описание* |
| [`Action`](./DataManager.cs/sobytiya/Action.md) | *Описание* |
| [`Action`](./DataManager.cs/sobytiya/Action.md) | *Описание* |
| [`OnTick;`](./DataManager.cs/sobytiya/OnTick;.md) | *Описание* |
| [`OnDom;`](./DataManager.cs/sobytiya/OnDom;.md) | *Описание* |
| [`OnSecurity;`](./DataManager.cs/sobytiya/OnSecurity;.md) | *Описание* |
| [`OnOrder;`](./DataManager.cs/sobytiya/OnOrder;.md) | *Описание* |
| [`OnOrderInfo;`](./DataManager.cs/sobytiya/OnOrderInfo;.md) | *Описание* |
| [`OnExecution;`](./DataManager.cs/sobytiya/OnExecution;.md) | *Описание* |
| [`OnPosition;`](./DataManager.cs/sobytiya/OnPosition;.md) | *Описание* |
| [`OnUserPosition;`](./DataManager.cs/sobytiya/OnUserPosition;.md) | *Описание* |
| [`OnUserDeal;`](./DataManager.cs/sobytiya/OnUserDeal;.md) | *Описание* |
| [`OnPortfolio;`](./DataManager.cs/sobytiya/OnPortfolio;.md) | *Описание* |
| [`OnTicksObtained;`](./DataManager.cs/sobytiya/OnTicksObtained;.md) | *Описание* |
| [`OnBarsObtained;`](./DataManager.cs/sobytiya/OnBarsObtained;.md) | *Описание* |


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

