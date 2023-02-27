
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
| [`ProcessMarketData`](./DataManager.cs/Методы/ProcessMarketData.md) | *Описание* |
| [`ProcessTradeData`](./DataManager.cs/Методы/ProcessTradeData.md) | *Описание* |
| [`Subscribe`](./DataManager.cs/Методы/Subscribe.md) | *Описание* |
| [`UnSubscribe`](./DataManager.cs/Методы/UnSubscribe.md) | *Описание* |
| [`GetConnectionsInfo`](./DataManager.cs/Методы/GetConnectionsInfo.md) | *Описание* |
| [`GetConnectionInfo`](./DataManager.cs/Методы/GetConnectionInfo.md) | *Описание* |
| [`GetSimAccounts`](./DataManager.cs/Методы/GetSimAccounts.md) | *Описание* |
| [`GetAccount`](./DataManager.cs/Методы/GetAccount.md) | *Описание* |
| [`GetAccounts`](./DataManager.cs/Методы/GetAccounts.md) | *Описание* |
| [`GetAccounts`](./DataManager.cs/Методы/GetAccounts.md) | *Описание* |
| [`GetUserPosition`](./DataManager.cs/Методы/GetUserPosition.md) | *Описание* |
| [`IsTradeAllowed`](./DataManager.cs/Методы/IsTradeAllowed.md) | *Описание* |
| [`IsTradeAllowed`](./DataManager.cs/Методы/IsTradeAllowed.md) | *Описание* |
| [`IsClientConnected`](./DataManager.cs/Методы/IsClientConnected.md) | *Описание* |
| [`ClientConnect`](./DataManager.cs/Методы/ClientConnect.md) | *Описание* |
| [`ClientDisconnect`](./DataManager.cs/Методы/ClientDisconnect.md) | *Описание* |
| [`ClientPlaceOrder`](./DataManager.cs/Методы/ClientPlaceOrder.md) | *Описание* |
| [`ClientModifyOrder`](./DataManager.cs/Методы/ClientModifyOrder.md) | *Описание* |
| [`ClientCancelOrder`](./DataManager.cs/Методы/ClientCancelOrder.md) | *Описание* |
| [`ClientCancelAllOrders`](./DataManager.cs/Методы/ClientCancelAllOrders.md) | *Описание* |
| [`ClientUpdateUserPosition`](./DataManager.cs/Методы/ClientUpdateUserPosition.md) | *Описание* |
| [`GetOrders`](./DataManager.cs/Методы/GetOrders.md) | *Описание* |
| [`GetExecutions`](./DataManager.cs/Методы/GetExecutions.md) | *Описание* |
| [`GetOrdersCount`](./DataManager.cs/Методы/GetOrdersCount.md) | *Описание* |
| [`GetPositionsCount`](./DataManager.cs/Методы/GetPositionsCount.md) | *Описание* |
| [`SyncSlTp`](./DataManager.cs/Методы/SyncSlTp.md) | *Описание* |
| [`LoadTrustAccounts`](./DataManager.cs/Методы/LoadTrustAccounts.md) | *Описание* |
| [`SetTradeMode`](./DataManager.cs/Методы/SetTradeMode.md) | *Описание* |
| [`FilterAccount`](./DataManager.cs/Методы/FilterAccount.md) | *Описание* |
| [`FilterAccount`](./DataManager.cs/Методы/FilterAccount.md) | *Описание* |
| [`AutoConnect`](./DataManager.cs/Методы/AutoConnect.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`Simulator`](./DataManager.cs/Свойства/Simulator.md) | *Описание* |
| [`Player`](./DataManager.cs/Свойства/Player.md) | *Описание* |

## События
| Название | Описание |
| --- | --- |
| [`OnError;`](./DataManager.cs/События/OnError;.md) | *Описание* |
| [`OnInfo;`](./DataManager.cs/События/OnInfo;.md) | *Описание* |
| [`OnConnected;`](./DataManager.cs/События/OnConnected;.md) | *Описание* |
| [`OnDisconnected;`](./DataManager.cs/События/OnDisconnected;.md) | *Описание* |
| [`OnAccountsReady;`](./DataManager.cs/События/OnAccountsReady;.md) | *Описание* |
| [`Action`](./DataManager.cs/События/Action.md) | *Описание* |
| [`Action`](./DataManager.cs/События/Action.md) | *Описание* |
| [`Action`](./DataManager.cs/События/Action.md) | *Описание* |
| [`Action`](./DataManager.cs/События/Action.md) | *Описание* |
| [`OnTick;`](./DataManager.cs/События/OnTick;.md) | *Описание* |
| [`OnDom;`](./DataManager.cs/События/OnDom;.md) | *Описание* |
| [`OnSecurity;`](./DataManager.cs/События/OnSecurity;.md) | *Описание* |
| [`OnOrder;`](./DataManager.cs/События/OnOrder;.md) | *Описание* |
| [`OnOrderInfo;`](./DataManager.cs/События/OnOrderInfo;.md) | *Описание* |
| [`OnExecution;`](./DataManager.cs/События/OnExecution;.md) | *Описание* |
| [`OnPosition;`](./DataManager.cs/События/OnPosition;.md) | *Описание* |
| [`OnUserPosition;`](./DataManager.cs/События/OnUserPosition;.md) | *Описание* |
| [`OnUserDeal;`](./DataManager.cs/События/OnUserDeal;.md) | *Описание* |
| [`OnPortfolio;`](./DataManager.cs/События/OnPortfolio;.md) | *Описание* |
| [`OnTicksObtained;`](./DataManager.cs/События/OnTicksObtained;.md) | *Описание* |
| [`OnBarsObtained;`](./DataManager.cs/События/OnBarsObtained;.md) | *Описание* |


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

