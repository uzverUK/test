# DataManager

`namespace` [TigerTrade.Tc](../).[Manager](./)

\===

#### Синтаксис

```csharp
public static class DataManager
```

## Список методов

| Название                                                                        | Описание |
| ------------------------------------------------------------------------------- | -------- |
| [`AutoConnect`](datamanager.cs.md#method-autoconnect)                           | _===_    |
| [`ClientCancelAllOrders`](datamanager.cs.md#method-clientcancelallorders)       | _===_    |
| [`ClientCancelOrder`](datamanager.cs.md#method-clientcancelorder)               | _===_    |
| [`ClientConnect`](datamanager.cs.md#method-clientconnect)                       | _===_    |
| [`ClientDisconnect`](datamanager.cs.md#method-clientdisconnect)                 | _===_    |
| [`ClientModifyOrder`](datamanager.cs.md#method-clientmodifyorder)               | _===_    |
| [`ClientPlaceOrder`](datamanager.cs.md#method-clientplaceorder)                 | _===_    |
| [`ClientUpdateUserPosition`](datamanager.cs.md#method-clientupdateuserposition) | _===_    |
| [`FilterAccount`](datamanager.cs.md#method-filteraccount)                       | _===_    |
| [`GetAccount`](datamanager.cs.md#method-getaccount)                             | _===_    |
| [`GetAccounts`](datamanager.cs.md#method-getaccounts)                           | _===_    |
| [`GetConnectionInfo`](datamanager.cs.md#method-getconnectioninfo)               | _===_    |
| [`GetConnectionsInfo`](datamanager.cs.md#method-getconnectionsinfo)             | _===_    |
| [`GetExecutions`](datamanager.cs.md#method-getexecutions)                       | _===_    |
| [`GetOrders`](datamanager.cs.md#method-getorders)                               | _===_    |
| [`GetOrdersCount`](datamanager.cs.md#method-getorderscount)                     | _===_    |
| [`GetPositionsCount`](datamanager.cs.md#method-getpositionscount)               | _===_    |
| [`GetSimAccounts`](datamanager.cs.md#method-getsimaccounts)                     | _===_    |
| [`GetUserPosition`](datamanager.cs.md#method-getuserposition)                   | _===_    |
| [`IsClientConnected`](datamanager.cs.md#method-isclientconnected)               | _===_    |
| [`IsTradeAllowed`](datamanager.cs.md#method-istradeallowed)                     | _===_    |
| [`LoadTrustAccounts`](datamanager.cs.md#method-loadtrustaccounts)               | _===_    |
| [`ProcessMarketData`](datamanager.cs.md#method-processmarketdata)               | _===_    |
| [`ProcessTradeData`](datamanager.cs.md#method-processtradedata)                 | _===_    |
| [`SetTradeMode`](datamanager.cs.md#method-settrademode)                         | _===_    |
| [`Subscribe`](datamanager.cs.md#method-subscribe)                               | _===_    |
| [`SyncSlTp`](datamanager.cs.md#method-syncsltp)                                 | _===_    |
| [`UnSubscribe`](datamanager.cs.md#method-unsubscribe)                           | _===_    |

## Список свойств

| Название                                            | Описание |
| --------------------------------------------------- | -------- |
| [`Player`](datamanager.cs.md#property-player)       | _===_    |
| [`Simulator`](datamanager.cs.md#property-simulator) | _===_    |

## Список событий

| Название                                                       | Описание |
| -------------------------------------------------------------- | -------- |
| [`Action`](datamanager.cs.md#event-action)                     | _===_    |
| [`Action`](datamanager.cs.md#event-action)                     | _===_    |
| [`Action`](datamanager.cs.md#event-action)                     | _===_    |
| [`Action`](datamanager.cs.md#event-action)                     | _===_    |
| [`OnAccountsReady;`](datamanager.cs.md#event-onaccountsready;) | _===_    |
| [`OnBarsObtained;`](datamanager.cs.md#event-onbarsobtained;)   | _===_    |
| [`OnConnected;`](datamanager.cs.md#event-onconnected;)         | _===_    |
| [`OnDisconnected;`](datamanager.cs.md#event-ondisconnected;)   | _===_    |
| [`OnDom;`](datamanager.cs.md#event-ondom;)                     | _===_    |
| [`OnError;`](datamanager.cs.md#event-onerror;)                 | _===_    |
| [`OnExecution;`](datamanager.cs.md#event-onexecution;)         | _===_    |
| [`OnInfo;`](datamanager.cs.md#event-oninfo;)                   | _===_    |
| [`OnOrder;`](datamanager.cs.md#event-onorder;)                 | _===_    |
| [`OnOrderInfo;`](datamanager.cs.md#event-onorderinfo;)         | _===_    |
| [`OnPortfolio;`](datamanager.cs.md#event-onportfolio;)         | _===_    |
| [`OnPosition;`](datamanager.cs.md#event-onposition;)           | _===_    |
| [`OnSecurity;`](datamanager.cs.md#event-onsecurity;)           | _===_    |
| [`OnTick;`](datamanager.cs.md#event-ontick;)                   | _===_    |
| [`OnTicksObtained;`](datamanager.cs.md#event-onticksobtained;) | _===_    |
| [`OnUserDeal;`](datamanager.cs.md#event-onuserdeal;)           | _===_    |
| [`OnUserPosition;`](datamanager.cs.md#event-onuserposition;)   | _===_    |

***

***

## Методы

### `AutoConnect` <a href="#method-autoconnect" id="method-autoconnect"></a>

\===

```csharp
public static void AutoConnect()
```

***

### `ClientCancelAllOrders` <a href="#method-clientcancelallorders" id="method-clientcancelallorders"></a>

\===

```csharp
public static void ClientCancelAllOrders(OrderGroup group)
```

`group` _<mark style="color:red;">`OrderGroup`</mark>_\
_===_

***

### `ClientCancelOrder` <a href="#method-clientcancelorder" id="method-clientcancelorder"></a>

\===

```csharp
public static void ClientCancelOrder(Order order)
```

`order` _<mark style="color:red;">`Order`</mark>_\
_===_

***

### `ClientConnect` <a href="#method-clientconnect" id="method-clientconnect"></a>

\===

```csharp
public static void ClientConnect(string connectionID)
```

`connectionID` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `ClientDisconnect` <a href="#method-clientdisconnect" id="method-clientdisconnect"></a>

\===

```csharp
public static void ClientDisconnect(string connectionID)
```

***

### `ClientModifyOrder` <a href="#method-clientmodifyorder" id="method-clientmodifyorder"></a>

\===

```csharp
public static void ClientModifyOrder(Order order)
```

`order` _<mark style="color:red;">`Order`</mark>_\
_===_

***

### `ClientPlaceOrder` <a href="#method-clientplaceorder" id="method-clientplaceorder"></a>

\===

```csharp
public static void ClientPlaceOrder(Order order)
```

***

### `ClientUpdateUserPosition` <a href="#method-clientupdateuserposition" id="method-clientupdateuserposition"></a>

\===

```csharp
public static void ClientUpdateUserPosition(UserPositionData position)
```

`position` _<mark style="color:red;">`UserPositionData`</mark>_\
_===_

***

### `FilterAccount` <a href="#method-filteraccount" id="method-filteraccount"></a>

\===

```csharp
public static bool FilterAccount(Account account)
```

`account` _<mark style="color:red;">`Account`</mark>_\
_===_

***

### `FilterAccount` <a href="#method-filteraccount" id="method-filteraccount"></a>

\===

```csharp
public static bool FilterAccount(Account account)
public static bool FilterAccount(string accountID)
```

`account` _<mark style="color:red;">`Account`</mark>_\
_===_

`accountID` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetAccount` <a href="#method-getaccount" id="method-getaccount"></a>

\===

```csharp
public static Account GetAccount(string accountID)
```

***

### `GetAccounts` <a href="#method-getaccounts" id="method-getaccounts"></a>

\===

```csharp
public static List<Account> GetAccounts(Symbol symbol, bool isOfflineAccount = false)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`isOfflineAccount` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `GetAccounts` <a href="#method-getaccounts" id="method-getaccounts"></a>

\===

```csharp
public static List<Account> GetAccounts(Symbol symbol, bool isOfflineAccount = false)
public static List<Account> GetAccounts()
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`isOfflineAccount` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `GetConnectionInfo` <a href="#method-getconnectioninfo" id="method-getconnectioninfo"></a>

\===

```csharp
public static ConnectionInfo GetConnectionInfo(string id)
```

`id` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetConnectionsInfo` <a href="#method-getconnectionsinfo" id="method-getconnectionsinfo"></a>

\===

```csharp
public static IEnumerable<ConnectionInfo> GetConnectionsInfo()
```

***

### `GetExecutions` <a href="#method-getexecutions" id="method-getexecutions"></a>

\===

```csharp
public static List<Execution> GetExecutions(Symbol symbol, Account account)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`account` _<mark style="color:red;">`Account`</mark>_\
_===_

***

### `GetOrders` <a href="#method-getorders" id="method-getorders"></a>

\===

```csharp
public static List<Order> GetOrders(Symbol symbol, Account account)
```

***

### `GetOrdersCount` <a href="#method-getorderscount" id="method-getorderscount"></a>

\===

```csharp
public static int GetOrdersCount()
```

***

### `GetPositionsCount` <a href="#method-getpositionscount" id="method-getpositionscount"></a>

\===

```csharp
public static int GetPositionsCount()
```

***

### `GetSimAccounts` <a href="#method-getsimaccounts" id="method-getsimaccounts"></a>

\===

```csharp
public static List<Account> GetSimAccounts()
```

`List` _<mark style="color:red;">`new`</mark>_\
_===_

***

### `GetUserPosition` <a href="#method-getuserposition" id="method-getuserposition"></a>

\===

```csharp
public static UserPosition GetUserPosition(Symbol symbol, Account account)
```

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

`account` _<mark style="color:red;">`Account`</mark>_\
_===_

***

### `IsClientConnected` <a href="#method-isclientconnected" id="method-isclientconnected"></a>

\===

```csharp
public static bool IsClientConnected(string connectionID)
```

`connectionID` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `IsTradeAllowed` <a href="#method-istradeallowed" id="method-istradeallowed"></a>

\===

```csharp
public static bool IsTradeAllowed(UserPosition position)
```

`position` _<mark style="color:red;">`UserPosition`</mark>_\
_===_

***

### `IsTradeAllowed` <a href="#method-istradeallowed" id="method-istradeallowed"></a>

\===

```csharp
public static bool IsTradeAllowed(UserPosition position)
public static bool IsTradeAllowed(Symbol symbol)
```

`position` _<mark style="color:red;">`UserPosition`</mark>_\
_===_

`symbol` _<mark style="color:red;">`Symbol`</mark>_\
_===_

***

### `LoadTrustAccounts` <a href="#method-loadtrustaccounts" id="method-loadtrustaccounts"></a>

\===

```csharp
public static void LoadTrustAccounts(List<TrustAccount> accounts)
```

***

### `ProcessMarketData` <a href="#method-processmarketdata" id="method-processmarketdata"></a>

\===

```csharp
public static void ProcessMarketData()
```

***

### `ProcessTradeData` <a href="#method-processtradedata" id="method-processtradedata"></a>

\===

```csharp
public static void ProcessTradeData()
```

***

### `SetTradeMode` <a href="#method-settrademode" id="method-settrademode"></a>

\===

```csharp
public static void SetTradeMode(int tradeMode, bool init)
```

`tradeMode` _<mark style="color:red;">`int`</mark>_\
_===_

`init` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `Subscribe` <a href="#method-subscribe" id="method-subscribe"></a>

\===

```csharp
public static void Subscribe(SubscriptionFlags flags, params Symbol[] symbols)
```

`flags` _<mark style="color:red;">`SubscriptionFlags`</mark>_\
_===_

`Symbol` _<mark style="color:red;">`params`</mark>_\
_===_

***

### `SyncSlTp` <a href="#method-syncsltp" id="method-syncsltp"></a>

\===

```csharp
public static void SyncSlTp()
```

***

### `UnSubscribe` <a href="#method-unsubscribe" id="method-unsubscribe"></a>

\===

```csharp
public static void UnSubscribe(SubscriptionFlags flags, params Symbol[] symbols)
```

`flags` _<mark style="color:red;">`SubscriptionFlags`</mark>_\
_===_

`Symbol` _<mark style="color:red;">`params`</mark>_\
_===_

***

***

***

## Свойства

### `Player` <a href="#property-player" id="property-player"></a>

\===

```csharp
public static bool Player { get; private set; }
```

***

### `Simulator` <a href="#property-simulator" id="property-simulator"></a>

\===

```csharp
public static bool Simulator { get; private set; }
```

***

***

***

## События

### `Action` <a href="#event-action" id="event-action"></a>

\===

```csharp
public static event Action OnUpdateAccount
```

### `Action` <a href="#event-action" id="event-action"></a>

\===

```csharp
public static event Action OnClearMarket
```

### `Action` <a href="#event-action" id="event-action"></a>

\===

```csharp
public static event Action OnUpdateFilters
```

### `Action` <a href="#event-action" id="event-action"></a>

\===

```csharp
public static event Action OnReferralDetected
```

### `OnAccountsReady;` <a href="#event-onaccountsready" id="event-onaccountsready"></a>

\===

```csharp
public static event Action<ConnectionInfo> OnAccountsReady;
```

### `OnBarsObtained;` <a href="#event-onbarsobtained" id="event-onbarsobtained"></a>

\===

```csharp
public static event Action<BarsResponce> OnBarsObtained;
```

### `OnConnected;` <a href="#event-onconnected" id="event-onconnected"></a>

\===

```csharp
public static event Action<ConnectionInfo> OnConnected;
```

### `OnDisconnected;` <a href="#event-ondisconnected" id="event-ondisconnected"></a>

\===

```csharp
public static event Action<ConnectionInfo> OnDisconnected;
```

### `OnDom;` <a href="#event-ondom" id="event-ondom"></a>

\===

```csharp
public static event Action<MarketDepth> OnDom;
```

### `OnError;` <a href="#event-onerror" id="event-onerror"></a>

\===

```csharp
public static event Action<ConnectionInfo, string> OnError;
```

### `OnExecution;` <a href="#event-onexecution" id="event-onexecution"></a>

\===

```csharp
public static event Action<Execution> OnExecution;
```

### `OnInfo;` <a href="#event-oninfo" id="event-oninfo"></a>

\===

```csharp
public static event Action<ConnectionInfo, string> OnInfo;
```

### `OnOrder;` <a href="#event-onorder" id="event-onorder"></a>

\===

```csharp
public static event Action<Order> OnOrder;
```

### `OnOrderInfo;` <a href="#event-onorderinfo" id="event-onorderinfo"></a>

\===

```csharp
public static event Action<OrderInfo> OnOrderInfo;
```

### `OnPortfolio;` <a href="#event-onportfolio" id="event-onportfolio"></a>

\===

```csharp
public static event Action<Portfolio> OnPortfolio;
```

### `OnPosition;` <a href="#event-onposition" id="event-onposition"></a>

\===

```csharp
public static event Action<Position> OnPosition;
```

### `OnSecurity;` <a href="#event-onsecurity" id="event-onsecurity"></a>

\===

```csharp
public static event Action<Security> OnSecurity;
```

### `OnTick;` <a href="#event-ontick" id="event-ontick"></a>

\===

```csharp
public static event Action<Tick> OnTick;
```

### `OnTicksObtained;` <a href="#event-onticksobtained" id="event-onticksobtained"></a>

\===

```csharp
public static event Action<TicksResponce> OnTicksObtained;
```

### `OnUserDeal;` <a href="#event-onuserdeal" id="event-onuserdeal"></a>

\===

```csharp
public static event Action<UserDeal> OnUserDeal;
```

### `OnUserPosition;` <a href="#event-onuserposition" id="event-onuserposition"></a>

\===

```csharp
public static event Action<UserPosition> OnUserPosition;
```
