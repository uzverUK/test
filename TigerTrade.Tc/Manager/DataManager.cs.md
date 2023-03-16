
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


===

### Синтаксис
```csharp
public static class DataManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AutoConnect`](#method-autoconnect) | *===* |
| [`ClientCancelAllOrders`](#method-clientcancelallorders) | *===* |
| [`ClientCancelOrder`](#method-clientcancelorder) | *===* |
| [`ClientConnect`](#method-clientconnect) | *===* |
| [`ClientDisconnect`](#method-clientdisconnect) | *===* |
| [`ClientModifyOrder`](#method-clientmodifyorder) | *===* |
| [`ClientPlaceOrder`](#method-clientplaceorder) | *===* |
| [`ClientUpdateUserPosition`](#method-clientupdateuserposition) | *===* |
| [`FilterAccount`](#method-filteraccount) | *===* |
| [`GetAccount`](#method-getaccount) | *===* |
| [`GetAccounts`](#method-getaccounts) | *===* |
| [`GetConnectionInfo`](#method-getconnectioninfo) | *===* |
| [`GetConnectionsInfo`](#method-getconnectionsinfo) | *===* |
| [`GetExecutions`](#method-getexecutions) | *===* |
| [`GetOrders`](#method-getorders) | *===* |
| [`GetOrdersCount`](#method-getorderscount) | *===* |
| [`GetPositionsCount`](#method-getpositionscount) | *===* |
| [`GetSimAccounts`](#method-getsimaccounts) | *===* |
| [`GetUserPosition`](#method-getuserposition) | *===* |
| [`IsClientConnected`](#method-isclientconnected) | *===* |
| [`IsTradeAllowed`](#method-istradeallowed) | *===* |
| [`LoadTrustAccounts`](#method-loadtrustaccounts) | *===* |
| [`ProcessMarketData`](#method-processmarketdata) | *===* |
| [`ProcessTradeData`](#method-processtradedata) | *===* |
| [`SetTradeMode`](#method-settrademode) | *===* |
| [`Subscribe`](#method-subscribe) | *===* |
| [`SyncSlTp`](#method-syncsltp) | *===* |
| [`UnSubscribe`](#method-unsubscribe) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Player`](#property-player) | *===* |
| [`Simulator`](#property-simulator) | *===* |

# Список событий
| Название | Описание |
| --- | --- |
| [`Action`](#event-action) | *===* |
| [`Action`](#event-action) | *===* |
| [`Action`](#event-action) | *===* |
| [`Action`](#event-action) | *===* |
| [`OnAccountsReady;`](#event-onaccountsready;) | *===* |
| [`OnBarsObtained;`](#event-onbarsobtained;) | *===* |
| [`OnConnected;`](#event-onconnected;) | *===* |
| [`OnDisconnected;`](#event-ondisconnected;) | *===* |
| [`OnDom;`](#event-ondom;) | *===* |
| [`OnError;`](#event-onerror;) | *===* |
| [`OnExecution;`](#event-onexecution;) | *===* |
| [`OnInfo;`](#event-oninfo;) | *===* |
| [`OnOrder;`](#event-onorder;) | *===* |
| [`OnOrderInfo;`](#event-onorderinfo;) | *===* |
| [`OnPortfolio;`](#event-onportfolio;) | *===* |
| [`OnPosition;`](#event-onposition;) | *===* |
| [`OnSecurity;`](#event-onsecurity;) | *===* |
| [`OnTick;`](#event-ontick;) | *===* |
| [`OnTicksObtained;`](#event-onticksobtained;) | *===* |
| [`OnUserDeal;`](#event-onuserdeal;) | *===* |
| [`OnUserPosition;`](#event-onuserposition;) | *===* |





***  
***  
# Методы

## `AutoConnect`<a href="method-autoconnect" id="method-autoconnect"></a>
===
```csharp
public static void AutoConnect()
```

***  

## `ClientCancelAllOrders`<a href="method-clientcancelallorders" id="method-clientcancelallorders"></a>
===
```csharp
public static void ClientCancelAllOrders(OrderGroup group)
```

`group` <mark style="color:red;">*`OrderGroup`*</mark>  
 *===*  


***  

## `ClientCancelOrder`<a href="method-clientcancelorder" id="method-clientcancelorder"></a>
===
```csharp
public static void ClientCancelOrder(Order order)
```
`order` <mark style="color:red;">*`Order`*</mark>  
 *===*  


***  

## `ClientConnect`<a href="method-clientconnect" id="method-clientconnect"></a>
===
```csharp
public static void ClientConnect(string connectionID)
```
`connectionID` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `ClientDisconnect`<a href="method-clientdisconnect" id="method-clientdisconnect"></a>
===
```csharp
public static void ClientDisconnect(string connectionID)
```

***  

## `ClientModifyOrder`<a href="method-clientmodifyorder" id="method-clientmodifyorder"></a>
===
```csharp
public static void ClientModifyOrder(Order order)
```

`order` <mark style="color:red;">*`Order`*</mark>  
 *===*  


***  

## `ClientPlaceOrder`<a href="method-clientplaceorder" id="method-clientplaceorder"></a>
===
```csharp
public static void ClientPlaceOrder(Order order)
```

***  

## `ClientUpdateUserPosition`<a href="method-clientupdateuserposition" id="method-clientupdateuserposition"></a>
===
```csharp
public static void ClientUpdateUserPosition(UserPositionData position)
```

`position` <mark style="color:red;">*`UserPositionData`*</mark>  
 *===*  


***  

## `FilterAccount`<a href="method-filteraccount" id="method-filteraccount"></a>
===
```csharp
public static bool FilterAccount(Account account)
```
`account` <mark style="color:red;">*`Account`*</mark>  
 *===*  


***  

## `FilterAccount`<a href="method-filteraccount" id="method-filteraccount"></a>
===
```csharp
public static bool FilterAccount(Account account)
public static bool FilterAccount(string accountID)
```
`account` <mark style="color:red;">*`Account`*</mark>  
 *===*  

`accountID` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetAccount`<a href="method-getaccount" id="method-getaccount"></a>
===
```csharp
public static Account GetAccount(string accountID)
```

***  

## `GetAccounts`<a href="method-getaccounts" id="method-getaccounts"></a>
===
```csharp
public static List<Account> GetAccounts(Symbol symbol, bool isOfflineAccount = false)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  

`isOfflineAccount` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `GetAccounts`<a href="method-getaccounts" id="method-getaccounts"></a>
===
```csharp
public static List<Account> GetAccounts(Symbol symbol, bool isOfflineAccount = false)
public static List<Account> GetAccounts()
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  

`isOfflineAccount` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `GetConnectionInfo`<a href="method-getconnectioninfo" id="method-getconnectioninfo"></a>
===
```csharp
public static ConnectionInfo GetConnectionInfo(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `GetConnectionsInfo`<a href="method-getconnectionsinfo" id="method-getconnectionsinfo"></a>
===
```csharp
public static IEnumerable<ConnectionInfo> GetConnectionsInfo()
```

***  

## `GetExecutions`<a href="method-getexecutions" id="method-getexecutions"></a>
===
```csharp
public static List<Execution> GetExecutions(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *===*  


***  

## `GetOrders`<a href="method-getorders" id="method-getorders"></a>
===
```csharp
public static List<Order> GetOrders(Symbol symbol, Account account)
```

***  

## `GetOrdersCount`<a href="method-getorderscount" id="method-getorderscount"></a>
===
```csharp
public static int GetOrdersCount()
```

***  

## `GetPositionsCount`<a href="method-getpositionscount" id="method-getpositionscount"></a>
===
```csharp
public static int GetPositionsCount()
```

***  

## `GetSimAccounts`<a href="method-getsimaccounts" id="method-getsimaccounts"></a>
===
```csharp
public static List<Account> GetSimAccounts()
```

`List` <mark style="color:red;">*`new`*</mark>  
 *===*  


***  

## `GetUserPosition`<a href="method-getuserposition" id="method-getuserposition"></a>
===
```csharp
public static UserPosition GetUserPosition(Symbol symbol, Account account)
```
`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *===*  


***  

## `IsClientConnected`<a href="method-isclientconnected" id="method-isclientconnected"></a>
===
```csharp
public static bool IsClientConnected(string connectionID)
```
`connectionID` <mark style="color:red;">*`string`*</mark>  
 *===*  


***  

## `IsTradeAllowed`<a href="method-istradeallowed" id="method-istradeallowed"></a>
===
```csharp
public static bool IsTradeAllowed(UserPosition position)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *===*  


***  

## `IsTradeAllowed`<a href="method-istradeallowed" id="method-istradeallowed"></a>
===
```csharp
public static bool IsTradeAllowed(UserPosition position)
public static bool IsTradeAllowed(Symbol symbol)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *===*  

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *===*  


***  

## `LoadTrustAccounts`<a href="method-loadtrustaccounts" id="method-loadtrustaccounts"></a>
===
```csharp
public static void LoadTrustAccounts(List<TrustAccount> accounts)
```

***  

## `ProcessMarketData`<a href="method-processmarketdata" id="method-processmarketdata"></a>
===
```csharp
public static void ProcessMarketData()
```

***  

## `ProcessTradeData`<a href="method-processtradedata" id="method-processtradedata"></a>
===
```csharp
public static void ProcessTradeData()
```

***  

## `SetTradeMode`<a href="method-settrademode" id="method-settrademode"></a>
===
```csharp
public static void SetTradeMode(int tradeMode, bool init)
```

`tradeMode` <mark style="color:red;">*`int`*</mark>  
 *===*  

`init` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `Subscribe`<a href="method-subscribe" id="method-subscribe"></a>
===
```csharp
public static void Subscribe(SubscriptionFlags flags, params Symbol[] symbols)
```
`flags` <mark style="color:red;">*`SubscriptionFlags`*</mark>  
 *===*  

`Symbol` <mark style="color:red;">*`params`*</mark>  
 *===*  


***  

## `SyncSlTp`<a href="method-syncsltp" id="method-syncsltp"></a>
===
```csharp
public static void SyncSlTp()
```

***  

## `UnSubscribe`<a href="method-unsubscribe" id="method-unsubscribe"></a>
===
```csharp
public static void UnSubscribe(SubscriptionFlags flags, params Symbol[] symbols)
```

`flags` <mark style="color:red;">*`SubscriptionFlags`*</mark>  
 *===*  

`Symbol` <mark style="color:red;">*`params`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `Player`<a href="property-player" id="property-player"></a>
===
```csharp
public static bool Player { get; private set; }
```  
***

## `Simulator`<a href="property-simulator" id="property-simulator"></a>
===
```csharp
public static bool Simulator { get; private set; }
```  
***
***  
 ***  
# События

## `Action`<a href="event-action" id="event-action"></a>
===

```csharp
public static event Action OnUpdateAccount
```

## `Action`<a href="event-action" id="event-action"></a>
===

```csharp
public static event Action OnClearMarket
```

## `Action`<a href="event-action" id="event-action"></a>
===

```csharp
public static event Action OnUpdateFilters
```

## `Action`<a href="event-action" id="event-action"></a>
===

```csharp
public static event Action OnReferralDetected
```

## `OnAccountsReady;`<a href="event-onaccountsready;" id="event-onaccountsready;"></a>
===

```csharp
public static event Action<ConnectionInfo> OnAccountsReady;
```

## `OnBarsObtained;`<a href="event-onbarsobtained;" id="event-onbarsobtained;"></a>
===

```csharp
public static event Action<BarsResponce> OnBarsObtained;
```

## `OnConnected;`<a href="event-onconnected;" id="event-onconnected;"></a>
===

```csharp
public static event Action<ConnectionInfo> OnConnected;
```

## `OnDisconnected;`<a href="event-ondisconnected;" id="event-ondisconnected;"></a>
===

```csharp
public static event Action<ConnectionInfo> OnDisconnected;
```

## `OnDom;`<a href="event-ondom;" id="event-ondom;"></a>
===

```csharp
public static event Action<MarketDepth> OnDom;
```

## `OnError;`<a href="event-onerror;" id="event-onerror;"></a>
===

```csharp
public static event Action<ConnectionInfo, string> OnError;
```

## `OnExecution;`<a href="event-onexecution;" id="event-onexecution;"></a>
===

```csharp
public static event Action<Execution> OnExecution;
```

## `OnInfo;`<a href="event-oninfo;" id="event-oninfo;"></a>
===

```csharp
public static event Action<ConnectionInfo, string> OnInfo;
```

## `OnOrder;`<a href="event-onorder;" id="event-onorder;"></a>
===

```csharp
public static event Action<Order> OnOrder;
```

## `OnOrderInfo;`<a href="event-onorderinfo;" id="event-onorderinfo;"></a>
===

```csharp
public static event Action<OrderInfo> OnOrderInfo;
```

## `OnPortfolio;`<a href="event-onportfolio;" id="event-onportfolio;"></a>
===

```csharp
public static event Action<Portfolio> OnPortfolio;
```

## `OnPosition;`<a href="event-onposition;" id="event-onposition;"></a>
===

```csharp
public static event Action<Position> OnPosition;
```

## `OnSecurity;`<a href="event-onsecurity;" id="event-onsecurity;"></a>
===

```csharp
public static event Action<Security> OnSecurity;
```

## `OnTick;`<a href="event-ontick;" id="event-ontick;"></a>
===

```csharp
public static event Action<Tick> OnTick;
```

## `OnTicksObtained;`<a href="event-onticksobtained;" id="event-onticksobtained;"></a>
===

```csharp
public static event Action<TicksResponce> OnTicksObtained;
```

## `OnUserDeal;`<a href="event-onuserdeal;" id="event-onuserdeal;"></a>
===

```csharp
public static event Action<UserDeal> OnUserDeal;
```

## `OnUserPosition;`<a href="event-onuserposition;" id="event-onuserposition;"></a>
===

```csharp
public static event Action<UserPosition> OnUserPosition;
```

