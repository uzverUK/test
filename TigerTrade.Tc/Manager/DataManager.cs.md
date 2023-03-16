
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


Описание

### Синтаксис
```csharp
public static class DataManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AutoConnect`](./DataManager.cs/Методы/AutoConnect.md) | *Описание* |
| [`ClientCancelAllOrders`](./DataManager.cs/Методы/ClientCancelAllOrders.md) | *Описание* |
| [`ClientCancelOrder`](./DataManager.cs/Методы/ClientCancelOrder.md) | *Описание* |
| [`ClientConnect`](./DataManager.cs/Методы/ClientConnect.md) | *Описание* |
| [`ClientDisconnect`](./DataManager.cs/Методы/ClientDisconnect.md) | *Описание* |
| [`ClientModifyOrder`](./DataManager.cs/Методы/ClientModifyOrder.md) | *Описание* |
| [`ClientPlaceOrder`](./DataManager.cs/Методы/ClientPlaceOrder.md) | *Описание* |
| [`ClientUpdateUserPosition`](./DataManager.cs/Методы/ClientUpdateUserPosition.md) | *Описание* |
| [`FilterAccount`](./DataManager.cs/Методы/FilterAccount.md) | *Описание* |
| [`GetAccount`](./DataManager.cs/Методы/GetAccount.md) | *Описание* |
| [`GetAccounts`](./DataManager.cs/Методы/GetAccounts.md) | *Описание* |
| [`GetConnectionInfo`](./DataManager.cs/Методы/GetConnectionInfo.md) | *Описание* |
| [`GetConnectionsInfo`](./DataManager.cs/Методы/GetConnectionsInfo.md) | *Описание* |
| [`GetExecutions`](./DataManager.cs/Методы/GetExecutions.md) | *Описание* |
| [`GetOrders`](./DataManager.cs/Методы/GetOrders.md) | *Описание* |
| [`GetOrdersCount`](./DataManager.cs/Методы/GetOrdersCount.md) | *Описание* |
| [`GetPositionsCount`](./DataManager.cs/Методы/GetPositionsCount.md) | *Описание* |
| [`GetSimAccounts`](./DataManager.cs/Методы/GetSimAccounts.md) | *Описание* |
| [`GetUserPosition`](./DataManager.cs/Методы/GetUserPosition.md) | *Описание* |
| [`IsClientConnected`](./DataManager.cs/Методы/IsClientConnected.md) | *Описание* |
| [`IsTradeAllowed`](./DataManager.cs/Методы/IsTradeAllowed.md) | *Описание* |
| [`LoadTrustAccounts`](./DataManager.cs/Методы/LoadTrustAccounts.md) | *Описание* |
| [`ProcessMarketData`](./DataManager.cs/Методы/ProcessMarketData.md) | *Описание* |
| [`ProcessTradeData`](./DataManager.cs/Методы/ProcessTradeData.md) | *Описание* |
| [`SetTradeMode`](./DataManager.cs/Методы/SetTradeMode.md) | *Описание* |
| [`Subscribe`](./DataManager.cs/Методы/Subscribe.md) | *Описание* |
| [`SyncSlTp`](./DataManager.cs/Методы/SyncSlTp.md) | *Описание* |
| [`UnSubscribe`](./DataManager.cs/Методы/UnSubscribe.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Player`](./DataManager.cs/Свойства/Player.md) | *Описание* |
| [`Simulator`](./DataManager.cs/Свойства/Simulator.md) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`Action`](./DataManager.cs/События/Action.md) | *Описание* |
| [`Action`](./DataManager.cs/События/Action.md) | *Описание* |
| [`Action`](./DataManager.cs/События/Action.md) | *Описание* |
| [`Action`](./DataManager.cs/События/Action.md) | *Описание* |
| [`OnAccountsReady;`](./DataManager.cs/События/OnAccountsReady;.md) | *Описание* |
| [`OnBarsObtained;`](./DataManager.cs/События/OnBarsObtained;.md) | *Описание* |
| [`OnConnected;`](./DataManager.cs/События/OnConnected;.md) | *Описание* |
| [`OnDisconnected;`](./DataManager.cs/События/OnDisconnected;.md) | *Описание* |
| [`OnDom;`](./DataManager.cs/События/OnDom;.md) | *Описание* |
| [`OnError;`](./DataManager.cs/События/OnError;.md) | *Описание* |
| [`OnExecution;`](./DataManager.cs/События/OnExecution;.md) | *Описание* |
| [`OnInfo;`](./DataManager.cs/События/OnInfo;.md) | *Описание* |
| [`OnOrder;`](./DataManager.cs/События/OnOrder;.md) | *Описание* |
| [`OnOrderInfo;`](./DataManager.cs/События/OnOrderInfo;.md) | *Описание* |
| [`OnPortfolio;`](./DataManager.cs/События/OnPortfolio;.md) | *Описание* |
| [`OnPosition;`](./DataManager.cs/События/OnPosition;.md) | *Описание* |
| [`OnSecurity;`](./DataManager.cs/События/OnSecurity;.md) | *Описание* |
| [`OnTick;`](./DataManager.cs/События/OnTick;.md) | *Описание* |
| [`OnTicksObtained;`](./DataManager.cs/События/OnTicksObtained;.md) | *Описание* |
| [`OnUserDeal;`](./DataManager.cs/События/OnUserDeal;.md) | *Описание* |
| [`OnUserPosition;`](./DataManager.cs/События/OnUserPosition;.md) | *Описание* |





***  
***  
# Методы

## `AutoConnect<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void AutoConnect()
```

***  

## `ClientCancelAllOrders<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientCancelAllOrders(OrderGroup group)
```

`group` <mark style="color:red;">*`OrderGroup`*</mark>  
 *Описание*  


***  

## `ClientCancelOrder<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientCancelOrder(Order order)
```
`order` <mark style="color:red;">*`Order`*</mark>  
 *Описание*  


***  

## `ClientConnect<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientConnect(string connectionID)
```
`connectionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ClientDisconnect<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientDisconnect(string connectionID)
```

***  

## `ClientModifyOrder<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientModifyOrder(Order order)
```

`order` <mark style="color:red;">*`Order`*</mark>  
 *Описание*  


***  

## `ClientPlaceOrder<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientPlaceOrder(Order order)
```

***  

## `ClientUpdateUserPosition<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientUpdateUserPosition(UserPositionData position)
```

`position` <mark style="color:red;">*`UserPositionData`*</mark>  
 *Описание*  


***  

## `FilterAccount<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool FilterAccount(Account account)
```
`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `FilterAccount<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool FilterAccount(Account account)
public static bool FilterAccount(string accountID)
```
`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  

`accountID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetAccount<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Account GetAccount(string accountID)
```

***  

## `GetAccounts<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Account> GetAccounts(Symbol symbol, bool isOfflineAccount = false)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`isOfflineAccount` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetAccounts<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Account> GetAccounts(Symbol symbol, bool isOfflineAccount = false)
public static List<Account> GetAccounts()
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`isOfflineAccount` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetConnectionInfo<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static ConnectionInfo GetConnectionInfo(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetConnectionsInfo<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static IEnumerable<ConnectionInfo> GetConnectionsInfo()
```

***  

## `GetExecutions<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Execution> GetExecutions(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `GetOrders<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Order> GetOrders(Symbol symbol, Account account)
```

***  

## `GetOrdersCount<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static int GetOrdersCount()
```

***  

## `GetPositionsCount<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static int GetPositionsCount()
```

***  

## `GetSimAccounts<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Account> GetSimAccounts()
```

`List` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `GetUserPosition<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static UserPosition GetUserPosition(Symbol symbol, Account account)
```
`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `IsClientConnected<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsClientConnected(string connectionID)
```
`connectionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `IsTradeAllowed<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsTradeAllowed(UserPosition position)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `IsTradeAllowed<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsTradeAllowed(UserPosition position)
public static bool IsTradeAllowed(Symbol symbol)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  


***  

## `LoadTrustAccounts<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void LoadTrustAccounts(List<TrustAccount> accounts)
```

***  

## `ProcessMarketData<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ProcessMarketData()
```

***  

## `ProcessTradeData<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ProcessTradeData()
```

***  

## `SetTradeMode<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetTradeMode(int tradeMode, bool init)
```

`tradeMode` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`init` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Subscribe<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Subscribe(SubscriptionFlags flags, params Symbol[] symbols)
```
`flags` <mark style="color:red;">*`SubscriptionFlags`*</mark>  
 *Описание*  

`Symbol` <mark style="color:red;">*`params`*</mark>  
 *Описание*  


***  

## `SyncSlTp<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SyncSlTp()
```

***  

## `UnSubscribe<a href="test" id="test"></a>`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void UnSubscribe(SubscriptionFlags flags, params Symbol[] symbols)
```

`flags` <mark style="color:red;">*`SubscriptionFlags`*</mark>  
 *Описание*  

`Symbol` <mark style="color:red;">*`params`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Player`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool Player { get; private set; }
```  
***

## `Simulator`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool Simulator { get; private set; }
```  
***
***  
 ***  
# События

## `Action`
Описание

```csharp
public static event Action OnUpdateAccount
```

## `Action`
Описание

```csharp
public static event Action OnClearMarket
```

## `Action`
Описание

```csharp
public static event Action OnUpdateFilters
```

## `Action`
Описание

```csharp
public static event Action OnReferralDetected
```

## `OnAccountsReady;`
Описание

```csharp
public static event Action<ConnectionInfo> OnAccountsReady;
```

## `OnBarsObtained;`
Описание

```csharp
public static event Action<BarsResponce> OnBarsObtained;
```

## `OnConnected;`
Описание

```csharp
public static event Action<ConnectionInfo> OnConnected;
```

## `OnDisconnected;`
Описание

```csharp
public static event Action<ConnectionInfo> OnDisconnected;
```

## `OnDom;`
Описание

```csharp
public static event Action<MarketDepth> OnDom;
```

## `OnError;`
Описание

```csharp
public static event Action<ConnectionInfo, string> OnError;
```

## `OnExecution;`
Описание

```csharp
public static event Action<Execution> OnExecution;
```

## `OnInfo;`
Описание

```csharp
public static event Action<ConnectionInfo, string> OnInfo;
```

## `OnOrder;`
Описание

```csharp
public static event Action<Order> OnOrder;
```

## `OnOrderInfo;`
Описание

```csharp
public static event Action<OrderInfo> OnOrderInfo;
```

## `OnPortfolio;`
Описание

```csharp
public static event Action<Portfolio> OnPortfolio;
```

## `OnPosition;`
Описание

```csharp
public static event Action<Position> OnPosition;
```

## `OnSecurity;`
Описание

```csharp
public static event Action<Security> OnSecurity;
```

## `OnTick;`
Описание

```csharp
public static event Action<Tick> OnTick;
```

## `OnTicksObtained;`
Описание

```csharp
public static event Action<TicksResponce> OnTicksObtained;
```

## `OnUserDeal;`
Описание

```csharp
public static event Action<UserDeal> OnUserDeal;
```

## `OnUserPosition;`
Описание

```csharp
public static event Action<UserPosition> OnUserPosition;
```

